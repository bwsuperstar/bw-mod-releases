# BW Mod Releases

Binary releases for BW Stats, BW Hangar Stats, BW Reserves and BW AutoClaim. No Python source code is published.

Each mod reads its own record from the shared release manifest. After a verified
update is loaded, the updater waits for World of Tanks to close, installs the
package under one stable filename and removes older versioned copies of that mod.

<details>
<summary>Full changelog</summary>

### BW Stats
- **1.8.32:** Promotes the tested performance renderer, removes persistent battle text filters and document-wide TAB overlap hit testing, and keeps only two bounded startup synchronization passes.
- **1.8.31:** Restores static stats after WoT replaces loading-screen rows and supports replay/special battle lifecycle paths with bounded startup checks.
- **1.8.30:** Removes document-wide battle mouse handlers; TAB tooltips now listen only on the mod's own elements.
- **1.8.29:** Activates a downloaded update during the same game start and reports it as active without requesting a restart.
- **1.8.28:** Loads one statistics snapshot at battle start, prevents duplicate requests and removes recurring battle UI work that could reduce FPS.
- **1.8.27:** Confirmed compatible with Micropatch 2.4.1_1, which retains the 2.4.1.0 mod folder.
- **1.8.16:** Restored settings and TAB layouts on World of Tanks 2.4.1 and updated battle panel registration.
- **1.8.15:** Updated and packaged for World of Tanks 2.4.1.0.
- **1.8.14:** Made the GLOBAL and TANKS setup sections mutually exclusive.
- **1.8.13:** Redesigned the in-game setup window and added the GLOBAL section.
- **1.8.10:** TAB screen: the stat columns now sit between the player name and the tank name, long names shorten instead of pushing the row, and nothing covers the numbers.
- **1.8.9:** TAB screen: the small game icon (×) no longer covers the stat numbers.
- **1.8.8:** Settings window: bigger stat and vehicle class headers, smaller buttons.
- **1.8.7:** Smaller checkboxes in the settings window.
- **1.8.6:** Moved the garage update notice into the mod so it appears during the first automatic update from an older release.
- **1.8.5:** Added an English garage notification for the automatic update result and fully hidden background updater processes.
- **1.8.4:** Moved automatic updates to the shared manifest and added verified replacement of older installed packages after game exit.
- **1.8.3:** Cached verified releases by game version and restored resources for the next launch.
- **1.8.2:** Added the startup updater.
- **1.8.1:** Internal changes.
- **1.8.0:** Added bwstats.org data, per-class settings, TAB columns, ALT labels and translucent side-panel WN8.
- **1.0.0–1.7.4:** Earlier local packages exist; individual change notes were not recorded.

### BW Hangar Stats
- **1.10.17:** Promotes the tested bounded carousel renderer, caches tank statistics and splits dossier work into small main-thread batches.
- **1.10.16:** Disconnects the garage DOM observer before battle so carousel scans cannot follow battle UI changes.
- **1.10.15:** Activates a downloaded update during the same game start and reports it as active without requesting a restart.
- **1.10.14:** Debounced garage carousel updates, ignored the mod's own UI changes and removed indefinite missing-data scans.
- **1.10.13:** Confirmed compatible with Micropatch 2.4.1_1, which retains the 2.4.1.0 mod folder.
- **1.10.10:** Restored the garage widget through native World of Tanks 2.4.1 resource registration.
- **1.10.9:** Updated and packaged for World of Tanks 2.4.1.0.
- **1.10.8:** Added a compatibility payload for systems that block native mod components.
- **1.10.6:** Moved the garage update notice into the mod so it appears during the first automatic update from an older release.
- **1.10.5:** Added an English garage notification for the automatic update result and fully hidden background updater processes.
- **1.10.4:** Moved automatic updates to the shared manifest and added verified replacement of older installed packages after game exit.
- **1.10.3:** Cached verified releases by game version and restored resources for the next launch.
- **1.10.2:** Added the startup updater.
- **1.10.1:** Improved card layout and readability; fixed statistics on filtered and two-row carousels.
- **1.0.0–1.10.0:** Earlier local packages exist; individual change notes were not recorded.

### BW Reserves
- **1.1.16:** Promotes the tested performance build while retaining its dedicated updater and battle-paused scheduling.
- **1.1.15:** Activates a downloaded update during the same game start and reports it as active without requesting a restart.
- **1.1.14:** Replaced the recurring reserve scan with one garage check scheduled for the active reserve's expiry time.
- **1.1.13:** Confirmed compatible with Micropatch 2.4.1_1, which retains the 2.4.1.0 mod folder.
- **1.1.12:** Redesigned the Personal Reserves window with the BW Stats blue visual style and checkbox controls.
- **1.1.11:** Restored the settings window and removed the recurring restart prompt.
- **1.1.10:** Updated and packaged for World of Tanks 2.4.1.0.
- **1.1.9:** Added a compatibility payload for systems that block native mod components.
- **1.1.7:** Moved the garage update notice into the mod so it appears during the first automatic update from an older release.
- **1.1.6:** Added an English garage notification for the automatic update result and fully hidden background updater processes.
- **1.1.5:** Moved automatic updates to the shared manifest and added verified replacement of older installed packages after game exit.
- **1.1.4:** Cached verified releases by game version and restored resources for the next launch.
- **1.1.3:** Added the startup updater.
- **1.1.2:** Added reserve selection, automatic reactivation, session reset and mods-list entry.
- **1.0.0–1.1.1:** Earlier local packages exist; individual change notes were not recorded.

### BW AutoClaim
- **1.2.15:** Promotes the tested performance build while retaining its dedicated updater and garage-only claim processing.
- **1.2.14:** Activates a downloaded update during the same game start and reports it as active without requesting a restart.
- **1.2.13:** Limits claim checks to the garage and cancels pending checks when a battle starts.
- **1.2.12:** Confirmed compatible with Micropatch 2.4.1_1, which retains the 2.4.1.0 mod folder.
- **1.2.11:** Updated and packaged for World of Tanks 2.4.1.0.
- **1.2.10:** Added a compatibility payload for systems that block native mod components.
- **1.2.8:** Moved the garage update notice into the mod so it appears during the first automatic update from an older release.
- **1.2.7:** Added an English garage notification for the automatic update result and fully hidden background updater processes.
- **1.2.6:** Moved automatic updates to the shared manifest and added verified replacement of older installed packages after game exit.
- **1.2.5:** Cached verified releases by game version and restored resources for the next launch.
- **1.2.4:** Added the startup updater.
- **1.2.3:** Added pet and Clan Supply claims, a daily summary and a loaded-mods list.
- **1.1.0–1.2.2:** Earlier local packages exist; individual change notes were not recorded.

</details>
