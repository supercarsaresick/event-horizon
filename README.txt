EVENT HORIZON / v1.4
A local-first Chrome New Tab workstation.

INSTALL (Chrome on desktop)
1. Extract the ZIP to a permanent folder. Do not load the ZIP itself.
2. Open chrome://extensions/ in Chrome.
3. Enable Developer mode in the top-right corner.
4. Click Load unpacked, then select the event-horizon folder containing manifest.json.
5. Open a new tab (Ctrl+T). If Chrome asks whether to keep the new tab change, choose Keep it.
   Disable other new-tab extensions if they conflict. A managed Chrome profile may prohibit unpacked extensions.

UPDATE FROM v1.0 OR v1.1
Export your JSON backup in Settings first. Extract v1.10 separately. Copy the CONTENTS of its event-horizon folder into your existing installed extension folder, replacing matching files. Do not remove the extension or change its installed path. Open chrome://extensions/ and click Reload on the existing Event Horizon card. Open a new tab. The storage key is unchanged and the new fields are optional; existing records should remain in place. If they do not, import the backup.

START
Home opens by default and contains the editable welcome, clock, world clocks and web search. Settings > Home display name changes the greeting; leave blank to hide it. Overview contains the original task queue, goals, focus timer, recorded activity, launchpad and capture panels. All sections are accessible from the top navigation.
Ctrl+K: command palette. /: web search. Alt+T: task. Alt+N: research note. Alt+W: clean wallpaper.
The first launch includes five stated outcomes only: quant billionaire ambition, MIT, Yancopoulos, IOI, IAIO.
Plans, deadlines, tasks, milestones, notes, measured values and histories start empty.
Default focus duration (25 minutes), world clocks and resource launchers are editable suggestions.
No real-time financial feed is connected. Market launchers open external websites.

DATA
Chrome storage.local is shared by extension pages in this profile; no server or account is required.
Settings > Export JSON to save a backup. Export sessions CSV for analysis. Import JSON replaces records after confirmation and does not restore an active timer. Back up before updates or uninstalling.
Avoid concurrent edits in multiple new tabs: simultaneous writes can overwrite one another. Use one dashboard tab for editing when possible.
Focus time means elapsed time on the timer or manually entered time. It does not establish actual productive activity.
Clock shows local system milliseconds; display refresh is limited by screen/browser scheduling. No external atomic clock synchronization.

PERMISSIONS
storage: local records; tabs: open/switch/close tabs and save workspace URLs; alarms/notifications: focus timer completion.
Bookmarks and history are optional permissions requested only when explicitly granted. Browser history lookup is limited to 500 records over the last 30 days. Workspace restores create a new window; they do not restore application state, cookies, unsaved forms, or Chrome internal pages.
No live CPU, temperature, stock prices, account balance, estimated success probability, or website analytics are fabricated.
No website blocking or monitoring software is included. Use the browser controls and task/decision ledgers for intentional workflows.

NEW IN v1.2
Task blockers and definitions of done, a Blocked filter, task-linked focus sessions, searchable task/note contents in the command palette, and optional milestone criteria and evidence. Goals has a collapsed Plan audit checking missing plans, milestones, next actions, blocked tasks and completed milestones without evidence. Audit counts are record checks, not success probabilities. No new permissions.

TEST STATUS
JavaScript syntax checks passed. v1.2 Home/Overview separation, search shortcut, responsive width and core UI behavior tested with Chromium and a mock local storage adapter: tasks, milestone completion, scientific calculator, date tool, stopwatch, manual session log, early focus completion, command palette and notes. Additional tests passed for editable greeting, blocked filter, task search, task-linked timer prefill, milestone criteria/evidence, plan audit and note lookup.
The environment's browser policy prevented loading unpacked extensions and navigating to a local server. Actual Chrome new-tab override, chrome.storage integration, alarm delivery, notifications, optional bookmark/history access and workspace operations could not be end-to-end verified here. Test these on your own Chrome profile after installation.

FUTURE PLAN INTEGRATION
When the Yancopoulos, IOI and IAIO plans are finalized, enter them in Goals or export your current JSON and provide it with the plans for a structured update. Keep existing records and IDs intact. No strategy or milestone is prefilled without your input.

NEW IN v1.4
Home-only visual refinement: larger warm neon greeting, luminous clock, responsive compact layout and uncropped wallpaper on unusual aspect ratios. No storage, permissions, or application logic changes.

Version 1.5: lowered greeting and clock; moved date and world clocks below the astronaut. No data or permission changes.

Version 1.7: Home returns to viewport-centered alignment. The wallpaper is reframed with a 64-pixel reflected right-edge extension; the original JPEG remains unchanged. All other features and storage keys are unchanged.

Version 1.8: removes the reflected wallpaper extension. Home and clean wallpaper use the original HD JPEG with proportional overscan and subject-axis centering. Some outer-edge cropping is necessary to fill the viewport. Interface geometry, application logic, permissions and storage keys are unchanged.
