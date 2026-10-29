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
- ⋯ → Edit task lists changes the morning, evening small and big-task menus, plus "Your tasks" (the ones you've typed yourself, which show first in the picker).
- **+ Add a task** adds an extra slot for that day; **Remove this slot** in the picker drops one. ⋯ → Reset slots puts the day back to the default.
- **All-day events** (Daily → Events → + Event, or ⋯): hunting trips, holidays, travel. "Pause daily tasks" makes it a day off that doesn't break your streak (you can still plan tasks anyway). "Repeats every year" for holidays.
- **Goals**: each goal has a date countdown and any mix of trackers (Edit → + Add a tracker): Checklist (topics/milestones), Count (problems, chapters), Score (practice exams vs. a passing mark), Consistency (days a week, tap the day dots) and Time (hours). The first tracker with progress also shows on the Daily tab.
- **Standards**: workouts, recipes, grocery lists. Switch a doc to Checklist for things like groceries, then "Uncheck all" to reuse it.
- Notes → ⋯ → Reorder projects changes the order of the project chips.
- `?tab=work`, `?tab=goals` or `?tab=docs` opens straight to that tab.
- Export a backup now and then.

## Updating
After changing any file, bump `CACHE` in `sw.js` (`jot-v3`, …) so the phone picks up the new version. It may take one app restart.
