# Release notes

Older versions: [CHANGELOG-archive.md](CHANGELOG-archive.md)

## v0.5.164 · Nov 26, 2026

**🏠 Command Center**
- In the Fleet Matrix, clicking a planet's Planetary or Orbital queue cell opens that planet's Shipyard (EM-060)

**🐞 Fixes**
- Fleet on Planet shows Maintain for Mining Vessels again. The game now labels that button "Repair", so we tell them apart by type instead (SH-083)

## v0.5.163 · Nov 26, 2026

**🎨 Left menu and images**
- The left menu shows its old line icons again on all 20 entries, in place of the new pictures from the 26 Nov game update. Badges are unchanged (GL-446)
- The game's new artifact pictures are hidden everywhere, and the cards close up to their text (GL-447)

**🛰 Fleet**
- The Spy dialog has a Gateway box, unticked each time it opens (FL-607)
- The old attack dialog is gone; Attack always opens the shared dialog (FL-440)

**🐞 Fixes after the 26 Nov game update**
- Shipyard: hiding ships and the in-queue chips, the fleet stat columns and the Buildings slots chip work again (SH-080)
- Shipyard Table View finds HP, Attack and Speed again, so Speed sorts. The Shield column is now HP, since the game no longer has a separate shield stat (SH-081)
- Fleet on Planet shows the Repair button again (SH-082)

## v0.5.162 · Nov 26, 2026

**🐞 Fixes**
- A moon's Overflow tooltip uses the moon's real storage for Ore, Silicates, Hydrogen and Alloys. Only rare resources use the rare cap (GL-440)
- Fleet > Mining on S0 no longer sticks on "Loading your planets and the map…". The map read gets 60 seconds and one retry, a failure shows an error, and Refresh tries again (FL-589)

**🧩 Other**
- Capitals are always left out of Defend and Reinforce, now that the game refuses capitals at stations (GL-341)

## v0.5.161 · Nov 25, 2026

**🐞 Fixes**
- S0 no longer shows "Browser storage full" when the Espionage colony index is too big to save. The index stays in memory instead, and other saved data is left alone (GL-437)
- Wandering Trader compares every module with what you have equipped, including modules whose card wording differs from the game's own label (RE-051)

## v0.5.160 · Nov 25, 2026

**✨ New**
- Wandering Trader > Modules has a roomier layout (RE-050)
- Mining resource pills use stronger colours (FL-588)

**🐞 Fixes**
- Browser storage no longer fills up on S0. When storage is nearly full at load, the script clears caches it can rebuild from the game, largest first (GL-436)
- Wandering Trader shows Equipped once instead of three times (RE-050)

## v0.5.159 · Nov 24, 2026

**✨ New**
- Market now sits right under Messages in the left menu (GL-417)
- Command Center > Fleet: a "Highlight under N h" box sets the warning threshold, the Command Vessel box is hidden, and a ★ marks the leader's planet (EM-048, EM-049, EM-050)
- Gather Fleets lists moons in their own collapsible Moons section (SH-079)
- Wandering Trader > Modules: a sticky Equipped column and a slot label on each card, with no hover popup (RE-047, RE-048)
- Mining resource pills each get their own colour, plus a 16x chip (FL-573, FL-575)
- Genesis Bases: Tunnels column widened, and sectors show short names such as G17, with the full name on hover (FL-568, GL-411)

**🐞 Fixes**
- Bring missing resources, then picking a hub, fills only the missing resources in Market's Pickup, never every resource (GL-435)

## v0.5.158 · Nov 24, 2026

**✨ New**
- Genesis Scout is one click: it sends 1 Probe, or 1 Spy Probe if you have no Probes (FL-566)
- Genesis tab drops Scouted rows and adds a Garrison counter pill and an "RSS lost / dmg" column (FL-567, FL-585, FL-587)
- The Mining table hides belts that an outpost is on or relocating to (FL-576)
- Moon Effect shows the next level's production gain, with the total on hover (MO-069)
- Command Center's Fleet matrix turns orange when a Planetary or Orbital queue has under 8 hours left (EM-047)
- Gather Fleets leaves damaged ships at home and adds a Gate checkbox (SH-078, SH-077)
- "Use Galactic Highway" now reads "Gateway" in the fleet dialogs, Salvage, Make route and Gather Fleets (GL-434)

**🐞 Fixes**
- Genesis system messages are quiet: no ding, no badge (GL-413)
- Genesis attacks show as PVE in Fleet > Active (FL-569)
- Research stays condensed on the Artifacts and Recycling tabs (RE-049)
- Bring Resources leaves enough hydrogen for fuel (FL-586)
- The Bulk Carriers need fills in on Resources while Evacuate refreshes (FL-571)

**🔧 Under the hood**
- One shared planet zone read for Moons, Fleet, Attack, Salvage and Targets (GL-381)

## v0.5.157 · Nov 24, 2026

**✨ Moons and Outposts**
- Phalanx results, Moon Thresholds and the Relocate belt list now use the standard sortable tables (MO-056, MO-057, OU-016)
- Moon Bring uses the same amber as the rest of the script (MO-064)

**🐞 Fixes**
- The moon pill now refreshes right after you Hide a moon (MO-065)

**🔧 Under the hood**
- Retired 14 old feature switches for badges and quiet messages; behaviour is unchanged (GL-378, GL-424)
- One shared list of finished mission statuses for badges (FL-509)
- One shared planet zone read, now used by Moons; other areas move over next (GL-381, in progress)
- Removed the old Research click watcher; the Research badge already clears on the action itself (RE-045)

## v0.5.156 · Nov 23, 2026

**🚀 Performance**
- Galaxy no longer stutters: very big tables draw only the rows on screen, and Galaxy remembers rows that haven't changed (GL-416, GA-010)

## v0.5.155 · Nov 22, 2026

**🚀 Performance**
- Big tables no longer freeze while they redraw: a 2,000-row table now redraws in a blink instead of about 27 seconds, and the Galaxy table finishes loading (GL-410)

**🪐 Planets**
- Recycling compare shows the cost difference with the right sign and colour (RE-046)

## v0.5.154 · Nov 22, 2026

**🪐 Planets**
- Buildings: hovering a short cost shows exactly what is missing (BU-048)

## v0.5.153 · Nov 22, 2026

**🛰 Fleet**
- The send dialog reads the source planet's fleet fresh, so it no longer says "0 of N needed" when ships are there (GL-408)

**⚙️ Other**
- The attack line counts only working ships; damaged ships in Repair or Maintain don't count (GL-409)

## v0.5.152 · Nov 22, 2026

**🛰 Fleet**
- Surveys: the "Oldest available anomaly" pill is hidden, and Delete is a red trash icon (FL-564, FL-565)
- Bulk need no longer misses a fleet read that finishes just as it checks (FL-563)

**🪐 Planets**
- Gather Fleets: a box frames the ship count cells (SH-076)

**⚙️ Other**
- The attack line ignores a leader vessel that is refitting or repairing (GL-405)
- The "Trader: summon ready" badge clears right after you summon, and artifact or research changes update their badges at once (GL-406, GL-407)

## v0.5.151 · Nov 22, 2026

**🛰 Fleet**
- Genesis tab tidied: the header sits on one row, with Active and Reports section heads (FL-551, FL-552)
- Genesis: Simulate works again, finished Core runs show in Reports, and a base's Scouted reports hide once it has a Victory (FL-554, FL-560, FL-555)
- Launch dialogs show an orange countdown bar when one of your attacks is heading to the same target (FL-561)
- Spy reports group ships by class and show a Resources total (FL-562)
- The PVP Spy button works again (FL-558)
- On S0, the Table View box shows even without a supply panel (FL-559)

**🪐 Planets**
- Weapon and armor types are plain text again, with no colours (GL-403)
- Fleet on Planet's weapon and armor fixed, and table chevrons stay quiet (SH-075)

**🌙 Moons**
- A phalanx scan that finds nothing now says so (MO-068)

## v0.5.150 · Nov 22, 2026

**🚑 Hotfix**
- Shipyard and other table pages no longer stutter: the weapon and armor pills stopped rewriting a shared stylesheet many times a second (GL-402)

**🛰 Fleet**
- PVP Attack: a Raid needs only Assault Shuttles, and opening Attack from a PVP row no longer fills cargo ships (FL-549, FL-550)
- PVP target table uses the standard fonts (FL-556)
- Genesis tab badge counts new reports, the same as the menu (FL-557)

**🪐 Planets**
- Bulk need retries a failed fuel estimate and explains on hover when it can't (FL-548)

## v0.5.149 · Nov 21, 2026

**🛰 Fleet**
- Stations: Make route checks the game first, so no more duplicate routes; default amounts are 24,000 with Options to change them; distance colours from green (near) to red (far) (FL-536, FL-541, FL-537)
- Genesis: Battle report on a deleted report shows a message instead of a dead page, and those buttons turn grey; new Damaged column; Mass line in the attack dialog (FL-539, FL-540, FL-543, FL-544)
- The game's hidden error box no longer shows a red bar on Fleet tabs (FL-538)
- Dispatch speed colours work again (FL-542)
- Launch dialogs show one focus highlight instead of two (FL-545)
- PVP targets: Player, Alliance, Military, Planet first; the Spy report link works while spies are in flight (FL-546, FL-547)

**⚙️ Other**
- Smaller caches, so browser storage stays well under the limit (GL-401)

## v0.5.148 · Nov 21, 2026

**🛰 Fleet**
- New Genesis tab: base tables, unread report count in the menu, an attack dialog, and Scout and Simulate buttons (FL-529, FL-530, FL-531, FL-532)
- "Genesis base taken" and "Genesis base found" messages are quiet (FL-533, FL-534)
- Debris To collect shows estimated Phase and Trip times (FL-535)

**🪐 Planets**
- Resources tab: numbers shown in full and right-aligned, with a Bulk need figure (EM-045, EM-046)
- Recycling compare popover (RE-044)
- Weapon and armor types show as coloured pills (GL-398)

**⚙️ Other**
- When browser storage is full, Nexus Legacy clears its own rebuildable caches and keeps saving, and shows a notice if it still can't (GL-399)
- Sorting a table keeps your earlier sorts as tiebreakers (GL-400)
- XP tip reads "Resets at 00:00 UTC" (GL-397)

## v0.5.147 · Nov 21, 2026

**🛡 Station Operations**
- Defense tables use the shared table: sections sort and remember their state, one text button per row plus Scan, Salvage and Remove as icons in fixed slots, and planet names link to the planet (GL-352, GL-392, GL-393, GL-396, FL-490)

**🪐 Planets**
- Overview: after an Evacuate, the button becomes a red "Recall" showing time flown; two clicks recall the fleet (OV-024)
- Fleet on Planet: the two row buttons are stacked (FL-526)
- Research cost cells are no longer cut off (RE-043)
- Resources tab: Total column and Bulk subtotals removed, overflow fixed (EM-044)

**🛰 Fleet**
- Fleets Available slot count updates the moment a fleet launches or lands (GL-394, GL-395)
- Debris Phase and Trip time fill straight away instead of showing "—" for 20 to 30 seconds (FL-524)
- Bio picklist rows are tinted (FL-525)
- Reports Time and Transfer Routes columns fit the page (FL-527, FL-528)

## v0.5.146 · Nov 21, 2026

**📊 Resources**
- Resources tab: Subtotal rows on a grey fill (EM-041), a Total column that adds each row's resources, rare included (EM-042), and a Bulk Carriers column with have / need per planet (EM-043)

**🛰 Fleet dialogs**
- No layout shift: while fuel and travel recalculate, the last values stay on screen dimmed, and lines keep their space so the Launch button doesn't move (FL-523)
- Carrier hangars hold 15 + Carrier Operations level fighters, not 16 + level (FL-522)

**🔧 Fixes**
- Fleet on Planet sections collapse again (SH-074)
- The Fleet Slots pill text is centred in its fixed width (GL-390)

## v0.5.145 · Nov 20, 2026

**🪐 Planets**
- Overview Evacuate lines show what you have against what you need ("Cargo 1.3M / 1.21M"), with exact values on hover (FL-521)
- Outpost detail header buttons have solid backgrounds, so the image behind them no longer shows through (OU-017)

**🛰 Fleet**
- Routes buttons on Transfer and Stations: Edit green, Pause blue, Resume orange, Delete red (FL-520)
