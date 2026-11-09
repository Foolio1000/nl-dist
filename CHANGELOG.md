# Release notes

## v0.5.110 · Nov 8, 2026

**🛰 Fleet**
- Active tab: mission types show as pills coloured by mission family (FL-270)
- Badges catch up on their own: Pirates re-reads camps in the background, and the Mining tab shows idle Miners and Gas Collectors (FL-266, FL-268)
<details><summary>Details</summary>

  - Pirates badge re-reads the camp list in the background, so new camps show (FL-266)
  - Mining tab badges for idle Miners and Gas Collectors (FL-268)
</details>
- Wormholes: the Attack button is green, and Hide, Attack and Unhide line up on the right; lost and damaged ships go on separate lines that wrap (FL-265, FL-267)
<details><summary>Details</summary>

  - Green Attack button, right-aligned row buttons on Detected (FL-265)
  - Lost and Damaged ships on their own wrapping lines (FL-267)
</details>
- The Salvage Patrol dialog stays open until every patrol is launched, with a toast after each launch (FL-269)
- In the fleet dialog, only the fleet slot count turns red or yellow, not the timer (GL-233)

**🛡 Station defense (Defense2)**
- The Vulnerability header drops the weekday, and Phalanx keeps the moon picker's order (GL-234, GL-235)
<details><summary>Details</summary>

  - Vulnerability window without the weekday (GL-234)
  - Phalanx popup keeps the moon picker's order (GL-235)
</details>

**🏗 Buildings**
- Table View: Build Next is gone and Hide sits left of the build button (BU-037)

**🧩 Other**
- Routine game messages (depleted fields, recovered artifacts and rewards, livery codes) are marked read quietly, with no sound or popup; anything legendary still shows (GL-232)

## v0.5.109 · Nov 8, 2026

**🛡 Station defense (Defense2)**
- Tidier page: one summary header, matching tabs, and green station names where you have planets nearby
<details><summary>Details</summary>

  - One header line: our stations, under attack, lost this window, and the vulnerability window with time left (GL-229)
  - Station Operations tabs all take our tab look while Defense2 is open (GL-230)
  - A station's name is green when its sector holds one of your planets; hover lists them (GL-231)
</details>

**🛰 Fleet**
- Wormholes: one red tab badge that refreshes when you open the Fleet page or the Wormholes tab, and Detected gets a Hidden bar (FL-257, FL-260, FL-264)
<details><summary>Details</summary>

  - Immediate check for new wormholes on the Fleet page and the Wormholes tab (FL-257)
  - Hidden bar on Wormholes Detected (FL-260)
  - One red Wormholes tab badge in the game's own style, covering wormholes to explore and runs waiting (FL-264)
</details>
- Surveys show the distance for systems more than 100 ly away (FL-256)
- Pirates shows an empty camps list instead of the placeholder box (FL-259)
- Supply hydrogen: you can edit the amount before sending (FL-261)
- Debris "Fleets on the way" gets Phase time and Trip time columns (FL-262)
- Transfer Routes: you can delete a route (FL-263)

**🚢 Shipyard**
- Planetary and orbital ships show as pills in different colours (SH-032)

**🧩 Other**
- Nothing else this time

## v0.5.108 · Nov 8, 2026

**🛡 Station defense (Defense2)**
- The station defense page gets a big round of improvements: clearer status, scout math and timing, and quieter alerts
<details><summary>Details</summary>

  - Phalanx popup opens at once from saved moon data (GL-211)
  - Scouts needed shows only what's still missing, with 2x and 4x views (GL-212, GL-216, GL-214)
  - Counts line shows stations under attack, landed and in-the-air fleets, and whether it's live (GL-213)
  - Delta column: battle time minus scout reinforce time, as a live countdown (GL-215)
  - Menu badge reads "Station attacks: N landed · M in the air" (GL-217)
  - "You" tag on stations where one of your fleets is or is heading (GL-218)
  - Hide a station until its attack ends; hidden rows fold into their own section (GL-219)
  - Recalled and Resolved rules tightened, and your own alliance's fleets never count as attackers (GL-220, GL-221)
  - Select Ships and Recall All on Recalled and Resolved rows (GL-222)
  - The game's capture banner stays collapsed once you collapse it (GL-223)
  - Status is the table's only colour, valued in Scouts against what's needed (GL-224)
  - A station's name turns red when its sector holds one of your planets (GL-225)
  - Background reads back off when the game asks, without ever blocking your clicks (GL-226)
  - Defend uses the Highway only when you have it researched (GL-228)
</details>

**🛰 Fleet**
- Quick Spy finds targets by planet name and shows Probe and Stealth travel times
<details><summary>Details</summary>

  - Type a planet name into Quick Spy to get spy targets (FL-249)
  - Probe time and Stealth time columns (FL-251)
</details>
- Stations: a Route button on each row, and the planet list picks up new colonies (FL-254, FL-250)
<details><summary>Details</summary>

  - Route button on the Stations table (FL-254)
  - The Station Filter's nearest-planet list includes newly colonized planets (FL-250)
</details>
- Mining: Total Trip retries a failed read, and the list shows 20 belts (FL-252, FL-255)
<details><summary>Details</summary>

  - Total Trip retries a failed read instead of staying blank (FL-252)
  - Mining lists 20 belts (FL-255)
</details>
- Supply hydrogen to a moon fills the right default amount (FL-253)

**🌙 Moons**
- Moon Scans: pick a sector beside each ready Scan and scan it in one click (MO-035)
- Phalanx search finds names that start with a number and a dash, like "7-azz" (MO-036)

**🏗 Buildings**
- An abandoned colony drops off the Energy badge (and the other badges) right away (BU-035)

**🧩 Other**
- Middle-click or Ctrl-click our left-menu items to open them in a new tab (GL-227)

## v0.5.107 · Nov 8, 2026

**🛰 Fleet**
- Spy missions show a landing countdown while en route (FL-246)
- Espionage and Moon Recon rows get a Recall button (FL-247)
- The Mining Total Trip column no longer gets stuck on "…" (FL-244)
- The Fleet badge keeps counting a wormhole run that is still waiting for your decision (FL-248)

**🌙 Moons**
- Fleet Phalanx results show as a nearest-first list under the search box; empty slots and your own planets and moons are hidden, out-of-range targets are greyed out, and a click on a row selects the target (MO-034)

**🏗 Buildings**
- In Table View, the Demolish panel opens as a full-width strip under its row (BU-036)

**🧩 Other**
- Nothing else this time

## v0.5.106 · Nov 7, 2026

**🛰 Fleet**
- You can edit rows in the Transfer Routes table (FL-245)

**🧩 Other**
- Nothing else this time

## v0.5.105 · Nov 7, 2026

**🛰 Fleet**
- The Next Tick countdown now shows the bio change next to it, e.g. "· −681.2 Bio" (FL-229)
- The Mining Richness number sits centred in its pill (FL-232)
- Surveys no longer shows a stale Investigate badge after an Investigate mission ends (FL-231)
- Paused logistics routes now count as one badge, "Routes paused: N". You can turn this badge off in Custom > Fleet Transfer (FL-233)
- Stations: the badge and table clear as soon as a collect launches, with no leftover rows (FL-237)
- Quick Spy and Stations Collect open in One click mode (FL-234, FL-235)
- The Survey table gains Wormhole and Pirate columns (FL-238)
- Mining's idle count updates as soon as you launch (FL-236)
- Wormholes open in One click mode. C4 wormholes are never launched automatically (FL-241)
- The Surveys tab badge also counts moon-scan rows (FL-242)
- The Pirates tab badge counts only camps you can attack now, and Dread camps get a clearer label (FL-239, FL-240)
- Fleet tab controls: Table View is always the last control, with One click mode just to its left (FL-243)

**🚢 Shipyard**
- The warning when you cancel an active build can no longer be turned off for good, for both ships and buildings (SH-031)

**🔬 Research**
- The fragment picker shows how many fragments you have: the hover ends with "N available" and the column reads "Fragments (N) · Action" (RE-030)

**🏷️ Badges**
- Custom > Badges has one on/off switch per badge type, grouped by menu, plus All on and All off. Turning a type off removes it from the menu count, the hover and its Fleet tab badge. Each server keeps its own switches (GL-208)

**🧹 Polish**
- Pop-up toasts are bigger and easier to read (GL-210)
- Custom is now its own button at the top right, next to Options (GL-207)
- The Crew table fits the page (GL-205)
- The leader pill shows the game's own status, so it no longer mixes up Refitting and Recovering (GL-209)
- Messages opens on the System tab (GL-206)

**🧩 Other**
- Steadier test for the rank pills (hgl48)

## v0.5.104 · Nov 6, 2026

**🛰 Fleet**
- Wormholes: a launched wormhole leaves Detected Wormholes at once and shows as "Launching" in Active Runs until the run arrives (FL-225)
- Ruins table cleaned up to match the other Fleet tables (FL-221)
- A badge when a logistics route is paused (FL-222)
- The Wormholes badge no longer counts a wormhole that already has a run (inside, returning or done) (FL-227)

**🔭 Surveys**
- An Investigate row leaves the table the moment you click (FL-226)

**🏴‍☠️ Pirates**
- New Pirate Camps column order, and Merchant Contracts claim colours
  <details><summary>Details</summary>

  - Pirate Camps columns in the new order (FL-224)
  - Merchant Contracts claim states in colour (FL-223)
  </details>
- Dread camps always open the fleet dialog in One click mode, and their tier shows as a coloured pill (FL-228)
- The Pirates badge stops counting a camp as soon as you launch at it (FL-230)

**🚢 Shipyard**
- Queue headers show the time left and the finish time (SH-030)

**🌙 Moons**
- Moon Scans rows stay in moon picker order and never move (MO-033)

**🧹 Polish**
- An 18px gap above the Hidden bar on Buildings, Moons and Fleet Pirates (GL-204)
- After NL Mute, Escape closes the game's Audio panel (GL-203)

**🧩 Other**
- Nothing else this time

## v0.5.103 · Nov 6, 2026

**🏴‍☠️ Pirates**
- Hide camps, a cleaner contracts line, and Battle Reports that fit the page
  <details><summary>Details</summary>

  - A Hide button on each camp and a Hidden section; the Pirates tab badge counts visible camps only, in the game's badge style, never on the Fleet menu (FL-212)
  - A camp you attacked stays out of the table until the fight (FL-213)
  - Battle Reports fit the page width, with the buttons on the right and rare resources in one column (FL-211)
  - Merchant Contracts line spaced out, no ✓, and "Claimed" in the same style as the other tags (FL-210)
  </details>

**♻️ Debris**
- Two sections: piles to collect, and piles with a fleet already on them
  <details><summary>Details</summary>

  - Split table, new column order, and a clicked Collect moves its row down right away (FL-214)
  - Send more is yellow (FL-219)
  - The Debris tab badge counts only piles still to collect (FL-220)
  </details>

**🔭 Surveys and Mining**
- Investigate rows leave the table as soon as you launch, and come back if the launch fails (FL-215)
- "Anomaly: Anomaly Detected" now reads "Anomaly Detected" (FL-216)
- Mining controls tidied: resource buttons top left, everything else top right, and the idle ships on one line (FL-217)

**🛰 Fleet**
- Fleet Active: no game icon before any mission name, Collect Debris included (FL-218)

**🔔 Badges and dialogs**
- Clicking the Messages badge opens the Messages window, like the menu item (GL-202)
- Bring missing resources: hub rows read like planet rows, "all" or "short <resource> <amount>" (GL-201)

**🔬 Research**
- A gap between the visible rows and the "Hidden (N)" bar (RE-029)

**🧩 Other**
- STYLE.md: rules for rare resources in one column and the Hidden-bar gap

## v0.5.102 · Nov 6, 2026

**🪐 Planet safety (the fix for data mixing between planets)**
- Every module now takes the planet from the game's planet switcher, never from the last planet it read
  <details><summary>Details</summary>

  - One shared "where am I" helper used by Shipyard, Fleet, Research, Buildings and Gather Fleets (GL-196)
  - Fire Sale, Scout First Strike "Copy to…" and Fleet Evacuate use the planet on screen (GL-195)
  - Sends and writes re-check the planet at the moment of the click and stop on a mismatch (GL-198)
  - Research "Lab busy" counts only research on this planet (RE-028)
  - The energy cost hover uses only the planet on screen (GL-196)
  - A build check fails on any "last planet read" pattern, and per-planet tests use two planets with different data (GL-197, GL-199)
  - Written rules for planet and server handling (GL-200)
  </details>

**🛰 Fleet tabs finished**
- PVE page retired: its tables and settings now live in Fleet
  <details><summary>Details</summary>

  - No PVE link or page; PVE settings move to Custom > Fleet > PVE with the same values (GL-186)
  </details>
- Debris tab rebuilt
  <details><summary>Details</summary>

  - New control row with Table View, One click mode and Refresh (FL-197)
  - A column per resource, Total, Expires, Nearest Planet, colour-coded Distance, Hide and Collect (FL-198)
  - Public pirate-camp piles marked * and listed first (FL-199)
  - Battle freight from survey reports shows here with Collect / Clear Pirates (FL-200)
  - Piles being collected move to the bottom with "Send more" (FL-201)
  </details>
- Mining and Surveys tables cleaned up
  <details><summary>Details</summary>

  - Mining: One click mode with a 1x / 2x / 4x / 8x multiplier (FL-192)
  - Mining: a Total Trip column (FL-193)
  - Mining: no inner scroll, fixed widths, sortable headers and an even control row (FL-194)
  - Surveys: nearest 20 plus Show more, an inline Range field, and Investigate above the Survey table (FL-195)
  - Table controls on one row, top right, on every Fleet tab (FL-196, GL-190)
  </details>
- Pirates tab tidied
  <details><summary>Details</summary>

  - Battle Reports as a Table View (FL-205)
  - Merchant Contracts condensed into one line (FL-206)
  - The game's Active Missions section hidden (Fleet > Active lists them) (FL-207)
  </details>
- Wormholes sorted by trip time
  <details><summary>Details</summary>

  - Active Runs: a Trip time column, shortest first, with runs waiting for your decision in their own table on top (FL-202)
  - Detected Wormholes: Hide + Attack only, already-sent wormholes left out, "n hidden · Show all" at the top right (FL-203)
  </details>
- Fleet Active shows outpost relocations, and the Active tab counts only fleets using a slot
  <details><summary>Details</summary>

  - Relocation rows show RELOCATION with the outpost name and no Recall (FL-189)
  - "Active (N)" matches "Uses fleet slots (N)" (FL-204)
  </details>

**🔕 Quieter badges**
- Silenced reports stay silent on the Fleet tabs and the unread chip too, and new targets badge only their own tab
  <details><summary>Details</summary>

  - Silenced reports are silent on tab badges and the "N unread" chip, Reports tab included (FL-187)
  - New Pirate Camps and unexplored Wormholes badge their own tab, cleared on attack or run (FL-188)
  - Open investigations badge the Surveys tab, cleared on Investigate / Collect (FL-190)
  - Expedition and Wormhole run reports never badge; runs waiting for Continue / Retreat still do (FL-191)
  </details>
- Messages badge hover groups unread messages by type, with click targets (GL-191)

**🌙 Moons**
- Moon Scans table modernized, ready scans first, with a "Sectors on cooldown" table (MO-032)
- An upgrading row's cancel reads "× Cancel" (MO-031)

**🏗 Buildings**
- Hide is protected: a bulk-write guard, a change log and Unhide all (BU-033)
- Times line up (no clock icon), and "No rare resource on this planet" shows only on the Rare Resource Extractor (BU-032, BU-034)

**🚢 Shipyard**
- Build on all planets: one dialog with a ship's build row for every planet (SH-028)

**💬 Hovers**
- Hovers appear at the cursor, only when the text is actually cut short, and no longer repeat button labels
  <details><summary>Details</summary>

  - A hover that only repeats the field's text is skipped unless the field is cut (GL-192)
  - The hover appears at the cursor and stays put; left-menu badge hovers stay on the badge (GL-193)
  - Button hovers that only reword the label are dropped (GL-194)
  </details>

**🐛 Fixes**
- Surveys no longer offers systems still on their 2-hour cooldown (FL-208)
- Transfer: paused routes no longer count as covering a pickup (FL-209)

**🧩 Other**
- Four flaky tests fixed (time of day, a badge redraw race, and two test inputs)

## v0.5.101 · Nov 6, 2026

**🧭 PVE moves into Fleet**
- Pirates, Surveys, Debris, Mining and Ruins are now Fleet tabs with Table View
  <details><summary>Details</summary>

  - New Fleet > Mining tab: the mining belt list as a table, with Mine opening the Mining dialog (FL-164)
  - New Fleet > Ruins tab: the Survey Ruins table (FL-165)
  - Pirates Table View with Nearest Planet, Distance and Attack (template dialog) (FL-166)
  - Detected Wormholes Table View with Nearest Planet, Distance, Hide and Attack (FL-167)
  - Surveys Table View with Investigate, Send Freighters / Clear Guards and an "Open only" filter (FL-168)
  - Debris Table View with Nearest Planet, Distance, Hide and Collect (FL-169)
  - PVE's background data keeps running without the PVE page (GL-185)
  </details>
- New **One click mode** launches with defaults (the dialog still opens if anything's off)
  <details><summary>Details</summary>

  - One click mode checkbox on the Surveys, Debris and Pirates tables (FL-185)
  </details>
- Ruins table now pages 10 at a time
  <details><summary>Details</summary>

  - < and > arrows page through the nearest Ancient moons, with a "11–20 of 465" count (FL-186)
  </details>

**🏗 Buildings**
- Clean status pills: Max Level, Building, Queued
  <details><summary>Details</summary>

  - One centred pill style for Max Level, Building, Queued and "No rare resource on this planet"; "Requires" rows without the lock icon (BU-028)
  </details>
- All tab grouped into sections; Defense split into Fleet and Ground
  <details><summary>Details</summary>

  - Section headings per building category on the All tab, with Fleet Defense and Ground Defense (BU-030)
  </details>
- Hover any energy gain to see **RSS per energy**, with the cheapest upgrade ringed green
  <details><summary>Details</summary>

  - RSS per point of energy on hover, using the energy after research bonuses (BU-031)
  </details>

**🔬 Research**
- Plan checkbox, every rare resource shown, and "Lab busy" while researching
  <details><summary>Details</summary>

  - A Plan checkbox column adds or removes a research from the game's Research Plan (RE-024)
  - The Cost "Other" column shows every rare resource, exact amounts on hover (RE-025)
  - While a research is underway, other rows show "Lab busy" instead of a Start that can't work (RE-026)
  </details>

**📊 Table cleanup**
- Consistent tables across Research, Shipyard, Fleet, Moons, Empire and Overview
  <details><summary>Details</summary>

  - Research: the Cost column is wide enough for the rare resource list (RE-027)
  - Buildings: more room for Effect (BU-029)
  - Shipyard and Command Center fleet matrix: long ship names show in full on hover (SH-027, EM-027)
  - Moons list: fixed column widths (MO-030)
  - Fire Sale dialog: even rows and one button width (OV-016)
  - Fleet Reports: the expand arrow is no longer clipped, Location fits wormhole names, and its hover never shows wormhole IDs (FL-170, FL-171)
  </details>
- Even row heights in Fleet Active, and the Wormholes run tables tidied up
  <details><summary>Details</summary>

  - Fleet Active: even 30px rows, "—" for empty times, and no icon in front of the mission name (FL-176, FL-160)
  - Wormholes run tables: one line per cell with the rest on hover, Finished as "Fri 17:58", equal Go Deeper and Retreat buttons, uppercase headers (FL-175)
  </details>

**🔕 Quieter badges**
- No badges for Mining Complete, Wormhole Battles, successful mining raids, or Survey and Pirate reports where no ships were lost
  <details><summary>Details</summary>

  - Mining Complete and Wormhole battle reports raise no Fleet badge (FL-182, FL-184)
  - Mining Raid reports raise a badge only when something went wrong (FL-183)
  - Survey and Pirate reports raise a badge only when ships were destroyed (FL-161, FL-162)
  - The quiet list is easy to extend with more report types (FL-163)
  </details>
- Hover a left-menu badge for a clickable menu of its lines
  <details><summary>Details</summary>

  - The hover lists each badge line and each line goes to its own place; the menu lines up with the top of the badge (GL-183, GL-184)
  </details>
- Leader badge now jumps to Fleet > Active (GL-188)

**🛰 Fleet**
- Fleet Active: a Detail column, a leader star, and two-click Recall
  <details><summary>Details</summary>

  - Detail column shows what each mission is doing (resource, wormhole class and stage, zone, camp, station) (FL-178)
  - A star marks the fleet carrying your leader (FL-181)
  - Every Recall needs a second click to confirm (FL-179)
  </details>
- Recalling a fleet that would end a station capture now gives a clear 24h warning (FL-180)
- Espionage and Transfer improvements
  <details><summary>Details</summary>

  - Spy tables use the full page width with the buttons on the right (FL-172)
  - Spy mission times in local time, and even rows (FL-173)
  - Quick Spy buttons are one width (FL-177)
  - Transfer: the full Covers text on hover, and data left-aligned (FL-174)
  </details>

**🚢 Shipyard**
- Fleet on Planet shows which facility builds each ship (SH-029)
- Cancelling the ship build in progress now asks first (no accidental cancel penalty) (SH-026)

**🐛 Fixes**
- Low Bio warning now fires on Shipyard builds (GL-189)
- Survey Ruins cooldown is 48 hours, and a refused send hides the moon for the time the game names (GL-181)
- Hover tooltips no longer flicker on tables that refresh every second (GL-182)
- The Research Plan cleanup no longer misses a research that is already underway (RE-019 fix)

**🧩 Other**
- More automated checks for table layout, and two flaky tests fixed (GL-187)

## v0.5.100 · Nov 6, 2026
- BU-027
- MO-029
- RE-023

## v0.5.99 · Nov 5, 2026
- BU-026
- FL-142
- FL-144
- FL-145
- FL-146
- FL-147
- FL-148
- FL-149
- FL-150
- FL-151
- FL-152
- FL-153
- FL-154
- FL-155
- FL-156
- FL-157
- FL-158
- FL-159
- GL-177
- GL-178
- GL-180
- MO-024
- MO-025
- MO-026
- MO-027
- MO-028
- RE-022
- SH-025

## v0.5.98 · Nov 5, 2026
- Fleet slots count right after Fleet
- Transfer improvements
- Transfer improvements
- Transfer improvements
- Readable labels over banner art
- Transfer Why column categories
- PVE tabs layout
- Defense2 uses shared phalanx and spy reports
- Season presets
- Command Center menu icon
- Station Ops in the main menu during an attack
- Options close on an outside click
- Storage full: any resource at 100%
- Moon storage rules
- Research hover text no longer names a player
- Fragments picker stays open
- Energy hover example text
- Buildings Table View
- Buildings Table View tidy-up
- Fire Sale greyed until Galactic Exchange

## v0.5.97 · Nov 5, 2026
- Buildings banner
- Buildings slots colour
- Cancel-upgrade warning
- Buildings table view
- Empire countdowns
- Reports: Gains cleanup
- Routes: Last run column
- Moon Collect amount in the Fleet badge hover
- Planet names in Fleet Active routes
- Moon supply target
- Bio upkeep in the Fleet banner
- Wormholes tab badge
- Wormholes tab badge
- Wormholes tab badge
- Wormholes tab badge
- Wormholes tab badge
- Collect badge opens Transfer
- Fleet badges on the badge registry
- PVE features in the Fleet menu
- PVE features in the Fleet menu
- PVE features in the Fleet menu
- PVE features in the Fleet menu
- PVE features in the Fleet menu
- Galaxy amber
- Galaxy names truncated
- Season colour picker
- Unmute guard
- Moon-scan finds on the Survey table at once
- UI review: hovers
- UI review: PVE fold
- UI review: shared countdowns
- UI review
- UI review
- Badge registry
- Fleet slots pill refresh
- Badge registry
- Badge registry
- Badge registry
- Badge registry
- Badge registry
- Badge registry
- Badge registry
- Moons list opens on badge click
- Moons table view
- Outposts badge on the registry
- Research Plan self-heal
- Ship maintenance badge
- Shipyard idle split

## v0.5.96 · Nov 5, 2026
- Internal cleanup: the Global module split into smaller files

## v0.5.95 · Nov 5, 2026
- Internal cleanup: page switching uses the shared route and page watchers

## v0.5.94 · Nov 5, 2026
- Shipyard: build boxes use projected stock
- Shipyard: costs update with quantity
- Research cards: no picture and Hide at top right
- Tasks tab removed
- Moons badge opens the right page
- Defense2 improvements
- Defense2 improvements
- Defense2 improvements
- Defense2 narrower columns
- Defense2 improvements
- Defense2 improvements
- Defense2 improvements
- Defense2 improvements
- Defense2 improvements
- Defense2 improvements
- Defense2 improvements
- Defense2 narrower columns
- Defense2 improvements
- Defense2 one Attackers column
- Crew: Table View
- Crew: Hide all-marked
- Crew: sort by grade
- Survey Ruins: dead-space list
- Fleet Transfer: fewer hover boxes

## v0.5.93 · Nov 4, 2026
- Internal cleanup: one shared copy of the game's transport code

## v0.5.92 · Nov 4, 2026
- Routes: resume tick right of PAUSED
- Fleet Reports: descriptive types and wormhole names
- Research table fits the page
- Recycling then Wandering Trader Modules
- Planet lists in the game's picker order
- Simpler crew cards with roles
- Survey Ruins: a stuck read gives up
- Fleet badges trimmed
- Espionage badge: mining activity only
- Wormholes badge: new runs
- Pirates badge: exceptions only
- Expeditions badge trimmed
- Open expedition slots on the badge
- Surveys badge: exceptions only
- Debris tab badge hidden
- Open patrol slots on the badge
- Badge data runs without the Tasks page
- Contracts badge
- Energy badge on Buildings
- Supply hydrogen rows for planets
- Supply hydrogen rows for outposts
- Outpost upgrade ready badge
- Send for upgrade on outposts
- Moons page with Moon Scans

## v0.5.91 · Nov 4, 2026
- Fleet Reports: Table View
- Fleet Reports: combat rounds
- Transfer tab after Espionage
- Routes: tick to resume a paused route
- Relocated outposts resume their routes
- Transfer: Covered by a route is now Routes
- Fleet Reports: Next and Back
- Transfer: Move out rows only flag the issue
- Fleet page: condensed banner
- Fleet badge: game's own count plus ours
- Ship maintenance badge on landing
- Shipyard: Gather Fleets
- Shipyard: Table View
- Survey Ruins fills in S0

## v0.5.90 · Nov 4, 2026
- Fire Sale: review dialog with a Post button per row
- Fire Sale: posted rows with Cancel; repeat sales
- Fire Sale button shows active order count
- Attack banner shows resources and ships at risk
- Defense2 tab for attacked stations
- Defense2: battle planet and Scout times
- Defense2: Scout counts and Defend button
- Defense2: Phalanx per row
- Defense2: Recalled attacks
- Survey Ruins: table under Stations
- Survey Ruins: source planet picker
- Survey Ruins: 10 nearest Ancient moons
- Survey Ruins: hide colonised moons
- Survey Ruins: 24h cooldown hide
- Survey Ruins: Spy Probes and Hackers only
- Survey Ruins: simpler columns
- Survey Ruins works in S0
- Daylight saving notice
- Mine: launched belt leaves the list at once
- Mine dialog: worst loss line
- Messages moves to the end of the menu
- Bring resources: planets that can fill it read all
- Transfer: To move column
- Transfer: Supply rows clear when delivered
- Fleet: game's own fleet slots chip back
- Transfer: Supply from the moon's planet with a warning
- Transfer tab after Espionage
- Hide buttons never disabled
- Relocate badge on Asteroid field depleted
- Research badge opens Artifacts

## v0.5.89 · Nov 4, 2026
- PVE: leader vessel never auto-selected
- Click a menu badge to open its planet
- Daylight saving time notice
- Leader pill shows the mission type
- PVE: station defense rows get Select Ships and Recall All
- Research badge for artifact study
- Shipyard: one Hide menu for four notices
- Fleet Active: Recall on station defense opens the game dialog
- Transfer: no full on Supply rows
- Transfer: Supply from the moon's own planet

## v0.5.88 · Nov 4, 2026
- Bring resources: hub pick opens the hub dialog
- Bring resources: which planets can fill the order
- Bring resources on a moon: its own planet first
- Deliver bar in violet
- Transfer: Why hover one resource per line
- Ship repairs badge skips full queues
- Command Core in the left menu
- Command Core badge
- Rare deliver button colours
- Badges clear instantly: Buildings
- Buildings badge for repairs
- Badges clear instantly: Shipyard
- Badges clear instantly: Fleet
- Badges clear instantly: Moons
- Badges clear instantly: Outposts
- Badges clear instantly: Dashboards
- Badge at 100% storage

## v0.5.87 · Nov 4, 2026
- Maintenance: error log on the Custom screen
- Maintenance: shared formatting helpers
- Maintenance: shared write helper

## v0.5.86 · Nov 4, 2026
- Transfer settings: clearer labels
- Moon Collect: a threshold per main resource
- Transfer: deliver to moons below their keeps
- Transfer: moon ships seen on load
- Research badge clears when research starts
- Research: ROI only where it applies
- Fire Sale: Cancel anyway
- Overview badge for open Fire Sale orders
- Fire Sale keeps travel hydrogen
- Fire Sale keeps 1 h of Bio
- Rare deliver: button polish
- Rare deliver: No cargo ships fix
- Wormholes: lost and damaged % on completed runs
- Fleet: bio tick countdown
- Recall hover: time home
- Spy reports: Previous and Next
- Evacuate always includes damaged ships

## v0.5.85 · Nov 3, 2026
- Make route: flat trigger and send amounts in settings

## v0.5.84 · Nov 3, 2026
- Command Center Research: lab upgrade end time
- Transfer: moon Collect opens on the Fleet page
- Call Ships: one extra cargo ship
- Transfer: moon Collect thresholds in settings
- Transfer: Make route on moon rows
- Market hubs: Rare deliver button
- To Do: Undo button
- Shipyard badge skips full repair queues
- Research: ROI on cards
- Research: hide researches
- Research badge: artifacts and trader summon

## v0.5.83 · Nov 3, 2026
- Fleet Active: own planet names in Route
- Transfer tab no longer jumps to Active
- Transfer: moon rows see ships on the moon
- Spy reports table: Alliance and Player columns
- Spy reports table: Intel level bullets
- Top bar pills: even spacing
- Deliver bar: no empty columns

## v0.5.82 · Nov 3, 2026
- Transfer: Hide checkbox column
- Command Center: edit the target ratio
- Command Center: short ship names in ratios
- Command Center: hide empty location columns
- Tasks: Modules & Crew table removed
- Espionage: Recall on each active mission
- Espionage: Table View for spy reports
- Espionage: collapsible sections

## v0.5.81 · Nov 3, 2026
- Transfer tab update
- Quick Spy distance column
- Fleet badge names each resource
- Moon Call Ships from Transfer
- Launched rows grey out at once
- Shipyard hover says ship repairs
- One format for badge hovers
- Release notes link in the update bar

## v0.5.80
- Tasks hydrogen settings
- Tasks moon supply settings
- Tasks outpost settings
- Tasks Bio uses Bio warning days
- Bio warning days setting
- Moon Collect keeps setting
- Collect outpost at % setting
- Bad run loss % setting
- Build Next list size setting
- PVE settings group
- PVE source not tied to one planet
- Fleet ratio targets start at 0
- Generic example names
- Published script has no comments
- Old dashboard planet links off for new players
- Relocate rows off Fleet Transfer

## v0.5.79
- Relocate back on the Outposts badge, off the Fleet badge

## v0.5.78
- XP pill greys categories at 0/5
- Bring missing resources names your planet or moon
- Supply from defaults to the moon's planet
- Shipyard badge counts planets needing repairs
- Ship repairs off the Tasks tab
- Shipyard Hide works while building
- Fleet badge hover trimmed
- Quick Spy alliance search sorted by rank
- Quick Spy clears list with the box

## v0.5.77
- Outpost collections on Fleet Transfer
- Outpost menu badges moved to Transfer
- Fleet Transfer update
- Fleet Transfer update
- Storage alerts off the Buildings badge

## v0.5.76
- Buildings Hide follows the planet on screen
- Transfer table has no Total row
- Banner Fleet Slots count launches at once
- Fragments slider sits under Level Up

## v0.5.75
- Transfer moon rows: over 10k (H 50k) collects above reserves
- Transfer moon routes with own defaults dialog
- Moon Supplies switched off

## v0.5.74
- Hide underway no longer amber
- Fleet Active table truncates instead of wrapping

## v0.5.73
- Quick Spy
- Fleet matrix planet order
- Hide underway research

## v0.5.72
- Hide Planetary and Orbital shipyards separately
- Shipyard Maintain fix
- Hide empty Wormholes placeholder
- Wider Trip time columns

## v0.5.71
- Loss note in wormhole and expedition dialogs
- Fleet Slots strip yellow at 1 slot left
- Rank gaps on hover
- Station times in local time
- Market value check
- What's new in the update bar
- Style checks in tests
- Rank pills use the NL tooltip
- Fleet Transfer tab
- Go Deeper fix

## v0.5.70
- GL-042
- GL-043
- GL-044
- GL-045
- FL-037
- FL-038
- FL-039
