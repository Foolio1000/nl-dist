# Release notes

Older versions: [CHANGELOG-archive.md](CHANGELOG-archive.md)

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

## v0.5.137 · Nov 20, 2026

**🔧 Hotfix**
- Buildings table no longer jumps and redraws on load; the Table View checkbox stays put (BU-042)

**🎨 Look**
- Emphasis is colour and weight, never a bigger size: launch dialog Travel and Hydrogen, the Fleet Slots strip and the moon queue banner keep the text size around them, still bold; the PVE Fleet Slots line and Launch button too (FL-492, GL-364, GL-365, FL-493)
- Season colour presets: game default plus Navy, Crimson, Forest, Royal Purple and Amber; Custom still works (GL-366)

**🪐 Planets**
- Fleet on Planet Ship column drops "N dmg"; the count stays on the Repair / Maintain button (SH-067)
- Research table: branch square and Effects pills styled again, no background bleed under the last row (RE-039, RE-040, RE-041); ROI values keep the text size around them

**📊 Tables**
- Tables use 14px text and 12.8px headers, Fleet > Active details and the Shipyard and Buildings grids included (GL-367, SH-068)
- After a click the clicked row stays in place and the table doesn't jump for 2 seconds (GL-368); Buildings Building and Queued rows are highlighted again (BU-043)

## v0.5.136 · Nov 20, 2026

**🔗 Planet links**
- Your planet names open that planet's Overview, your moons open the moon's Overview, and another player's planet opens Galaxy at its system: in the Fleet tables, Transfer, Unsupplied, Stations, Mining and PVE lists, Reports, Espionage, Galaxy, the Combat Simulator note, Command Center, launch dialogs and attack targets (GL-358, FL-485, FL-486, FL-487, FL-488, FL-489, EM-040, GL-360)

**🎨 Look**
- Table sections get even spacing: 20px above, 10px below (GL-359)
- Richness pill is easier to read: lighter fills, dark bold text (FL-491)
- Hovers can show bold names (GL-362); shared table extras: an indigo pill, your own rows tinted, a little more room in action columns (GL-363)

**🪐 Planets**
- Fleet on Planet: Repair (N) / Maintain (N) and "N dmg" are back (SH-064); Good / Bad against show whole names that fit, then +N, full list on hover with bold names (SH-065); Built at moves to the end (SH-066)

## v0.5.135 · Nov 19, 2026

**🎨 Tables**
- Most tables now use our shared table look: Fleet Active, Stations, Transfer, Unsupplied, the PVP tabs, Pirates reports, Debris, Wormholes, Pirates/Surveys/Debris, Mining, Survey and Ruins, Galaxy, Research, Buildings, Command Center Resources, Moon Scans and Market Open Orders (FL-466, FL-467, FL-468, FL-469, FL-470, FL-471, FL-472, FL-473, FL-474, FL-475, FL-476, FL-477, FL-478, GA-009, RE-038, BU-040, EM-038, GL-354, GL-353)
- Style check for new tables (GL-351)

**🛰 Fleet dialogs**
- Fill cargo button on Fleet > Dispatch: fills by RSS weight, highest first, and Hydrogen keeps the trip's fuel (FL-482)
- One launch sound per launch, no double sound on moon deliveries (FL-483)
- Salvage Patrol Route target sits under Source and hides for Planet and System (FL-480, FL-484)

**🛡 Banner and Inbound**
- Leader HP bubble when the command vessel is damaged: yellow under 50%, red under 25% (GL-356)
- Inbound fleets shows a red Overflow row for anything that would go over storage (GL-357)

**🪐 Planets**
- Fleet on Planet Good / Bad against shows the top 3, the rest on hover (SH-062); Repair (n) and Maintain (n) (SH-060, SH-061); Crushes bold again (SH-063)
- Buildings Table View drops the "ROI " label (BU-041)
- One shipyard listener, no visible change (SH-052)

**🌙 Moons**
- Moon Buildings Table View: no clock in Time (MO-059); Effect energy shows the next level's change (MO-060)

**🔔 Badges**
- Badges clear the moment you act; the Patrol slot badge follows the game's capacity (GL-355, FL-479, FL-481)

## v0.5.134 · Nov 19, 2026

**🪐 Planets**
- Fleet on Planet is our own table: names white and bold, damaged ships "N dmg" in amber, Count blue, Built at bubbles, no column dividers; the new shared table renderer behind it (SH-057, GL-348, GL-349, SH-056); its extra cells only in Table View (SH-051)
- Research Table View column reads "Lab · Lv" (RE-037)
- Building ROI and energy cost read one shared RSS weight lookup, no visible change (BU-039)

**🛰 Fleet dialogs**
- Travel and Hydrogen cost stand out in bold blue in every launch summary (FL-459)
- The Galactic Highway box remembers your last launch for each dialog, Stations Make route included; Cancel saves nothing (FL-462)
- Active Table View: Send Defense is blue, only Recall stays red (FL-464)

**⛏ Mining and PVE**
- Salvage Patrol coverage matches the game: Planet ×1, System ×2, Route ×2 with a Route target (FL-463)
- Genesis bases are recorded (FL-465)

**🔔 Badges**
- An attacked Genesis base leaves the Fleet badge and Genesis tab badge (FL-460); the Expedition slot badge clears at launch (FL-461)

**📊 Market and Empire**
- Hub Inventory hides resources with 0 (GL-350)
- Empire Resources totals in neutral colours, Total set apart (EM-037)

## v0.5.133 · Nov 19, 2026

**🛰 Fleet dialogs**
- Galactic Highway checkbox (unchecked by default) on every launch that the game lets use it: deliveries, Evacuate, Move out / Supply, moon sends, Mining, station and debris collects, attacks (FL-457)
- Launch dialogs open at once with "Loading…", and closing while loading cancels (FL-456)
- PVP attack dialog runs on the shared launch dialog; the old one stays behind a switch for a week (FL-439)
- Every click shows something: Expeditions and Patrol Launch buttons keep working through refreshes, "Still loading planets…" instead of nothing (FL-456)

**🪐 Planets**
- Fleet on Planet columns, with ship-vs-ship matchups from Fleet Simulation and a flat Table View (SH-047, SH-048, SH-049, SH-050)

**⛏ Mining and PVE**
- Salvage Patrol capability readout (FL-455)
- Stations cleanup in Transfer, PVE and Stations, no visible change (FL-443, FL-444, FL-446, FL-447, FL-448)

**🌙 Moons**
- Moon Evacuate and Call Ships keep capitals out of Sentinel space, like the other launches (MO-055)

**🔔 Messages and under the hood**
- Unread badges on the Messages page Players and System sub-tabs (GL-343)
- S0: requests we cancel are no longer logged, slow reads log as "timeout" (GL-344)
- New style rule: buttons built inside HTML strings are flagged (FL-456)
