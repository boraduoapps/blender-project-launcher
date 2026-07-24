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
it stops letting you create, edit, or render anything **48 hours after
install** so you're always running something current — a read-only view of
your projects (and any render still finishing) stays available even after
that. Just download the newest release to keep going. Your projects, render
output, and settings are never touched by this.

## What it does

- **Finds your projects automatically** — point it at a folder (or scan
  every drive) and it indexes every `.blend` file, grouping different
  versions of the same project together and figuring out the real project
  folder even through nested subfolders.
- **Always opens the right Blender version** — no more guessing which
  install a file needs, or accidentally re-saving it in the wrong one.
- **Background render queue** — queue up renders (including a real,
  queueable 360° Orbit option) with live progress and ETA, keep working
  while they run, and step through several finished outputs in sequence
  with a built-in dailies viewer.
- **Version Snapshots** — one-click save points for a project's history,
  with no git knowledge required, the option to flag a specific snapshot
  as a milestone worth coming back to, and revert to any past snapshot
  when you need to.
- **Collections** — group projects together by hand (a client, a shot list,
  whatever makes sense to you), separate from how they're organized on disk.
- **Produced assets, automatically** — renders, packed textures, and
  snapshot previews your projects generate show up as real assets, linked
  back to the project that made them, right alongside your shared asset
  library.
- **Shared asset library** — materials, HDRIs, models, and rigs
  cross-referenced against which of your projects actually use them.
- **Duplicate detection** — flags projects that share an exact name
  elsewhere, with an on-demand deep scan to confirm true byte-for-byte
  duplicates and a one-click way to keep one copy and discard the rest.
- **Finds and fixes broken file references** — spot missing linked textures
  or libraries per project (including files that are just an undownloaded
  OneDrive placeholder, not actually broken) and relink them straight from
  the app once you've tracked the file back down.
- **Task boards & notes** — a lightweight checklist and review-note thread
  per project, with a status badge per task.
- **Quick turntable previews** — spin a project's geometry around on demand
  without opening Blender, right from its project page.
- **Trash with recovery** — projects are never deleted outright; restore
  anything removed by mistake.

## Status

Actively developed, pre-1.0 — expect rough edges, and expect things to
keep changing between releases.

## Contact

Questions or feedback? Reach out to **oldmike** on Discord.

## License

No license file yet — all rights reserved by default until one is added.
