# Release notes

Older versions: [CHANGELOG-archive.md](CHANGELOG-archive.md)

## v0.5.171 · Nov 27, 2026

**🏗 Buildings**
- The Table View box sits in the Buildings tab bar, and the queue section's subtitle is gone, so the list starts higher on the page (BU-056)

**⚙ Behind the scenes**
- Evacuate, Recall and Transfer read your fleets back through the shared data helper after a send, so each send triggers only one refresh (GL-471, second part)

## v0.5.170 · Nov 27, 2026

**🏗 Buildings**
- The Max Level pill is grey, and a queued row's Time shows the game's build time for the next level. It reads "Waiting" only when that time isn't known (BU-054)
- The Shield Generator row's Effect shows how much shield HP and regen the upgrade adds (BU-055)

**⚙ Behind the scenes**
- A shared helper for reading game data, so features can share one read instead of each making their own (GL-459)
- The fleet dialog's attack check and the re-reads after a launch use that helper (GL-471, first part)

**🐞 Fixes**
- Command Center remembers your last tab again when you open it from the menu (EM-062)
- The hidden copy of the Patrol form no longer plays click sounds while you make selections (FL-611)
- The storage report no longer lists table settings as unknown keys (GL-472)

## v0.5.169 · Nov 27, 2026

**🏗 Buildings**
- Buildings rows have more room and separator lines. A queued row's Time reads "Waiting", resource numbers line up, and every status pill is full width (BU-053)

**🎨 Look**
- Warning buttons and highlights are gold instead of light orange everywhere: Bring missing resources, Pause, the attack bar, "Launch anyway" and the short ship box (GL-469)

**⚙ Behind the scenes**
- Browser storage now has one home and a list of every key the script saves (GL-441)
- The game-answer cache is no longer saved again in full on every change, which cuts storage writes (GL-460)

**🐞 Fixes**
- On NF2, building energy shows in the Energy column again instead of Effect, along with the RSS per energy hover and the cheapest-energy highlight (BU-052)

## v0.5.168 · Nov 27, 2026

**🏗 Buildings**
- The Buildings table has its own look: no stripes, no tint on rows that are building or queued, and the Building / Queued pill spans all five resource columns (BU-051)

**⚙ Behind the scenes**
- A new build check keeps every game read, timer and storage write going through one shared place, so new features can't add hidden background work (GL-467)
- The rules for what the script keeps in memory are written down in one place (GL-458), and the list of the script's timers is now generated from the code (GL-345)

**🐞 Fixes**
- The Buildings Energy column, its RSS per energy hover and the cheapest-energy highlight work again after the 26 Nov game update (BU-050)
- The memory clean-up's console message now says it removed our own sim results, not the game's (GL-466)

## v0.5.167 · Nov 27, 2026

**⚙ Speed and memory**
- The script keeps at most 300 saved game answers in memory, so a game tab left open all day no longer grows to gigabytes. Each planet's latest snapshot is always kept (GL-452)
- Once per version, the script clears the leftover results of our own combat-sim runs from browser storage, about 500 KB (GL-452)

**⛏ Mining and PVE**
- The hidden copy of the Patrol form behind the Salvage Patrol readout now closes within a second of the dialog closing. There's never more than one, and one left idle for 3 minutes closes itself (FL-610)

**🐞 Fixes**
- The Buildings table shows Building or Queued again instead of an empty pill, after the 26 Nov game update (BU-049)

## v0.5.166 · Nov 27, 2026

**⛏ Mining and PVE**
- The Salvage Patrol readout now uses the game's own ratings for Cargo and escort, worked out by a hidden copy of the game's Patrol form. If the game can't rate the fleet, the readout says "Rating unavailable" instead of guessing (FL-608)

## v0.5.165 · Nov 27, 2026

**🏠 Command Center**
- Command Center's own tabs (To Do, Resources, Buildings and Research) are back. They went missing when the 26 Nov game update added an icon to each tab (EM-061)

**🛒 Market**
- On a hub card that lists no resources, the game's Pickup button is hidden, since there is nothing to pick up (GL-449)

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
