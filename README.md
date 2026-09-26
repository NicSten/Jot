# Jot

Daily three habit tracker and quick notes (projects, notes, subtasks) in one offline app. Everything is stored on the device.

## Install
1. Create a GitHub repo (e.g. `jot`) and upload every file in this folder to the root.
2. Settings → Pages → Deploy from branch → `main`, `/ (root)` → Save.
3. After a minute, open `https://<your-username>.github.io/jot/` in Chrome on your phone → ⋮ → **Install app** (or Add to Home screen).

Long-press the home-screen icon for **Quick note** and **Daily three** shortcuts.

## Moving your data over
Data doesn't follow between the Claude artifact and this installed version (or the old Daily Three app).
In the artifact: ⋯ → Export backup. In the installed app: ⋯ → Import backup and pick that file.

## Tips
- `#projectname` in a quick note files it under that project (a prefix works: `#rap` → Raptor).
- The calendar button on a note or subtask puts it into a daily three slot; flipping the breaker checks it off.
- ⋯ → Edit task lists changes the morning, evening small and big-task menus.
- Export a backup now and then.

## Updating
After changing any file, bump `CACHE` in `sw.js` (`jot-v3`, …) so the phone picks up the new version. It may take one app restart.
