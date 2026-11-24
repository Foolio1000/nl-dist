# Release notes

Older versions: [CHANGELOG-archive.md](CHANGELOG-archive.md)

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

## v0.5.144 · Nov 20, 2026

**🛰 Fleet dialogs**
- The short-ship Launch box no longer has a double outline: its own border turns light orange and the number bold orange (FL-519)

## v0.5.143 · Nov 20, 2026

**🔧 Hotfix**
- The Shipyard build list, Buildings and moon Buildings grids and Fleet on Planet now have the solid table background too, not a see-through one (GL-389)

## v0.5.142 · Nov 20, 2026

**🕒 Times**
- One time format everywhere: "45s" under a minute, "4m 32s", "24h 09m", "13d 16h" from 25 hours, and days only past 10 days ("13d"); "time since" reads "3h 12m ago" (GL-385)
- The Fleet Slots countdown in the top bar has a fixed width, so the pills beside it no longer shift every second; its hover shows UTC (GL-387)

**🎨 Look**
- Every table gets the same solid background as Fleet on Planet (GL-388)
- The HP pill in the top bar opens the Leader screen for repairs (GL-386)

**🛰 Fleet dialogs**
- A ship whose template asks for more than the planet has gets its Launch box outlined in light orange (FL-518)

## v0.5.141 · Nov 20, 2026

**🎨 Button colours**
- One outlined look for every coloured button: green for positive, red for negative, blue for neutral, light orange for a limit or warning, and purple for rare uses. Unavailable buttons are grey, like Research's "Lab busy" (GL-383, GL-384)
- Build buttons on Shipyard, Research and moons match the Buildings build button (GL-382)
- Shipyard: Queue Full is grey, Max and All blue, Repair green and Maintain blue (SH-072, SH-073); Reports and Espionage Save is blue (FL-512); Routes: Delete red, Edit blue, Pause orange (FL-513); Market: Deliver green, Pickup blue, Rare deliver purple (GL-384)
- Zone pills in the tables use the new colours (GL-380)

**🛰 Fleet dialogs**
- Launch sound and Trip Time in every launch dialog (FL-510, FL-511)
- Ships with template 0 fold under "N more ships" (FL-515)
- A launch that needs a confirm turns the button into an orange "Launch anyway" instead of opening a box (FL-516)
- Every Collect dialog (Debris and Send more, battle freight, station Collect) has the Transport type row and Fit transports to cargo (FL-517)

**⛏ Mining and PVE**
- Send dig from Ruins (FL-434)
- The old PVE and Mining dialogs are gone (FL-442)

**🪐 Planets**
- Buildings Effect column: one pill per effect with an icon, red when it uses a resource, blue when it adds (BU-047)
- With Show Demolish on, Demolish takes the far-right button column on Buildings and moon Buildings (BU-046, MO-067)
- Fleet > Transfer hides an outpost's hydrogen Supply row while it's relocating (FL-514)

## v0.5.140 · Nov 20, 2026

**🎨 Look**
- Amber Bring buttons toned down: a dark translucent amber instead of a bright fill (GL-376)

**⛏ Mining and PVE**
- Expedition and raid loss notes show ship names instead of ids like "#4" (FL-505)
- The Salvage Patrol bands read pauses and backs off when the game says "too many requests" (FL-458)

**🔧 Under the hood**
- One shared attribute helper replaces 9 copies, no visible change (GL-347)

## v0.5.139 · Nov 20, 2026

**🔊 Sound**
- One click sound per click: buttons that hand your click on to the game's own button no longer click twice (GL-375)

**🛰 Fleet dialogs**
- Launch summaries show Travel "time (arrival UTC)" and, for return trips, Trip Time "time (home UTC)", bold blue; estimates in italic (FL-504)
- Mining launch notes: no trip breakdown; Worst loss and Last raid on their own lines (FL-503)

**⛏ Mining and PVE**
- The 1x/2x/4x/8x multiplier is remembered per resource (FL-502)
- PVE pill digits are centred (FL-499)

**🎨 Tables**
- System cells show a zone pill across PVP, Galaxy, PVE and Stations tables (GL-373, FL-496, FL-497, FL-498)
- Unread reports use the standard unread row (GL-372, FL-494, FL-495)

**⚔️ PVP**
- PVP Targets: Player first, and a new Closest column (FL-500)
- Quick Spy: Spy and Stealth en route pills in yellow (FL-501)

## v0.5.138 · Nov 20, 2026

**⚡ Energy**
- Buildings and moon Buildings Table View: energy is green or red by sign, and the cheapest energy building gets a green pill with an "N RSS per energy" hover (BU-045, MO-063)

**🎨 Look**
- Bring (missing resources) buttons are amber on Buildings, Research, Shipyard and moon Buildings (GL-369, GL-370, MO-062)
- The banner Hide ▾ button is the standard small button and stays inside the banner (GL-371)

**🪐 Planets**
- Shipyard build list Time without the clock, at 14px (SH-069); ship names 14px bold white (SH-070); locked rows fixed (SH-071)
- Research Fragments column and picker smaller (RE-042)
