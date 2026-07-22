# Blender Project Launcher

A desktop companion app for Blender artists and small studios. It indexes
your local `.blend` files, remembers which Blender version each project was
saved with, launches the right one automatically, and gives you a render
queue and shared asset library without any setup.

Windows, no installer — download the zip, extract it, and run.

## Download

Grab the latest build from the [Releases page](https://github.com/boraduoapps/blender-project-launcher/releases),
extract the zip, and run `Blender Project Launcher.exe` from inside it.

This is a preview build: it works fully offline with no account needed, but
it stops launching **48 hours after install** so you're always running
something current — just download the newest release to keep going. Your
projects, render output, and settings are never touched by this.

## What it does

- **Finds your projects automatically** — point it at a folder (or scan
  every drive) and it indexes every `.blend` file, grouping different
  versions of the same project together and figuring out the real project
  folder even through nested subfolders.
- **Always opens the right Blender version** — no more guessing which
  install a file needs, or accidentally re-saving it in the wrong one.
- **Background render queue** — queue up renders with live progress and
  ETA, and keep working while they run.
- **Version Snapshots** — one-click save points for a project's history,
  with no git knowledge required.
- **Collections** — group projects together by hand (a client, a shot list,
  whatever makes sense to you), separate from how they're organized on disk.
- **Shared asset library** — materials, HDRIs, models, and rigs
  cross-referenced against which of your projects actually use them.
- **Task boards & notes** — a lightweight checklist and review-note thread
  per project.
- **Trash with recovery** — projects are never deleted outright; restore
  anything removed by mistake.

## Status

Actively developed, pre-1.0 — expect rough edges, and expect things to
keep changing between releases.

## License

No license file yet — all rights reserved by default until one is added.
