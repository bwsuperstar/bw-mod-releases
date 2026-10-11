# BW Mod Releases

Binary releases for BW Tank Stats, BW Hangar Stats, BW Reserves, BW AutoClaim and BW Network Monitor. No Python source code is published.

Each mod reads its own record from the shared release manifest. After a verified
update is loaded, the updater waits for World of Tanks to close, installs the
package under one stable filename and removes older versioned copies of that mod.

<details>
<summary>Full changelog</summary>

### BW Tank Stats
- **1.8.4:** Moved automatic updates to the shared manifest and added verified replacement of older installed packages after game exit.
- **1.8.3:** Cached verified releases by game version and restored resources for the next launch.
- **1.8.2:** Added the startup updater.
- **1.8.1:** Added a session switch for BW Network Monitor to pause future requests.
- **1.8.0:** Added bwstats.org data, per-class settings, TAB columns, ALT labels and translucent side-panel WN8.
- **1.0.0–1.7.4:** Earlier local packages exist; individual change notes were not recorded.

### BW Hangar Stats
- **1.10.4:** Moved automatic updates to the shared manifest and added verified replacement of older installed packages after game exit.
- **1.10.3:** Cached verified releases by game version and restored resources for the next launch.
- **1.10.2:** Added the startup updater.
- **1.10.1:** Improved card layout and readability; fixed statistics on filtered and two-row carousels.
- **1.0.0–1.10.0:** Earlier local packages exist; individual change notes were not recorded.

### BW Reserves
- **1.1.5:** Moved automatic updates to the shared manifest and added verified replacement of older installed packages after game exit.
- **1.1.4:** Cached verified releases by game version and restored resources for the next launch.
- **1.1.3:** Added the startup updater.
- **1.1.2:** Added reserve selection, automatic reactivation, session reset and mods-list entry.
- **1.0.0–1.1.1:** Earlier local packages exist; individual change notes were not recorded.

### BW AutoClaim
- **1.2.6:** Moved automatic updates to the shared manifest and added verified replacement of older installed packages after game exit.
- **1.2.5:** Cached verified releases by game version and restored resources for the next launch.
- **1.2.4:** Added the startup updater.
- **1.2.3:** Added pet and Clan Supply claims, a daily summary and a loaded-mods list.
- **1.1.0–1.2.2:** Earlier local packages exist; individual change notes were not recorded.

### BW Network Monitor
- **0.2.6:** Moved automatic updates to the shared manifest and added verified replacement of older installed packages after game exit.
- **0.2.5:** Tolerated WoT's wrapped import exception when optional SQLite is unavailable.
- **0.2.4:** Removed the `_ctypes` startup dependency that prevented mods-list registration.
- **0.2.3:** Cached verified releases by game version and restored resources for the next launch.
- **0.2.2:** Added the startup updater.
- **0.2.1:** Added connection, server, adapter, ICMP and privacy diagnostics with selected session controls.
- **0.1.0–0.2.0:** Earlier local packages exist; individual change notes were not recorded.

</details>
