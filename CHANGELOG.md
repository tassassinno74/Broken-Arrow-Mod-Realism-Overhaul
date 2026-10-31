# Changelog

All notable changes to Broken Arrow Realism Overhaul. Texts and translations are made with AI tools.

## 6.2 (October 2026)

**Built for Broken Arrow 1.2.2.** Needs MelonLoader 0.7.3. Every player in a lobby needs 6.2: an older version shows **Wrong version**.

**Update from 6.1:** close the game, replace `Mods\BrokenArrowRealismOverhaul.dll` and copy the new `RealismOverhaul_Vehicules` folder into the game folder (let Windows replace the files). Keep MelonLoader 0.7.3 and the other folders. Your decks are kept.

### Fixes
- **Campaign**: the **Launch the campaign** button opens the campaign again (it lit up but did nothing). Your campaign save is never erased.
- **Arsenal**: every card is back in its country's division (some lists could be empty).
- **Nuclear aircraft cards** are put aside for now. A deck that had one still works: only that card leaves it.

### Enemy commander
- It uses its transports and its trucks, guards what it holds and attacks better.

### New
- **ZALA 421-16E2**: Russian reconnaissance drone (Russia, Recon tab).

## 6.1 (October 2026)

**Built for Broken Arrow 1.2.2.** Needs MelonLoader 0.7.3. Every player in a lobby needs 6.1: an older version shows **Wrong version**.

**Update from 6.0.3:** close the game, replace `Mods\BrokenArrowRealismOverhaul.dll` and copy the new `RealismOverhaul_Vehicules` folder into the game folder (let Windows replace the files). Keep MelonLoader 0.7.3 and the other folders. Your decks are kept. The first launch after the game update takes a few more minutes while MelonLoader rebuilds its files.

### Game 1.2.2
- The crash or freeze while a map loads, with 6.0.3 on game 1.2.2, is fixed.
- The whole mod has been checked again on the new game version.

### Battle log (diagnostics)
- New setting in **Esc > Options > Mod > Diagnostics**: **Off**, **On** or **Full**.
- It writes a log of each battle to `UserData\RealismOverhaul_Sonde` (the last 10 are kept). **On**: errors, slowdowns, memory and the battle summary (about 200 KB). **Full**: also the details of the mod's scripts and of the AI (about 3 MB).
- It records the Steam ID (or VK Play account) and nickname of every player in the battle, and the chat. Never an IP address; your Windows folder (with your user name) is hidden.
- **Nothing is sent over the Internet.** **Prepare the file to send** puts the last 5 battles into one `.zip` under 10 MB; you decide whether to send it, and you send it yourself.

### Memory and low-end PCs
- Lighter memory use: a 3D model is only read when a unit of that type appears on the map. Before, the memory could fill up at the start of a battle.
- **Low-end PC mode** (Esc > Options > Mod): **Auto** (the mod decides from your PC's memory), **Yes** or **No**.

### A new HUD
- **Mod's new HUD** (Esc > Options > Mod > Interface (HUD)): one style for all of the mod's battle display (the same colours, one background, the game's font), one badge per unit.
- **Layout mode**: drag each block of the mod with the mouse, then **Done**. Positions are kept on your PC, one set per screen shape.
- **Mod interface size**: 75 % to 150 %.
- **Mod's new HUD: No** brings back the old display, unchanged. These settings are for your PC only: nothing is sent to other players.

### Lobbies and Create a game
- **Find a lobby** rebuilt: your version and the game's, the host's rules before you join, filters (same version, friends...), and a clear **Wrong version** button for a lobby of another version.
- A new lobby screen: your side in blue, the other side in red.
- **Create a game** laid out in 7 sections. What is chosen when the lobby is created (game mode, side) stays locked while the lobby is open.

### Guide and Training centre
- Two new cards in the **Play** tab, next to Campaign, Create a game and Find a lobby:
  - **Guide**: the whole mod explained (getting started, game modes, realism modes, range settings, wounded and evacuation, engineers and repair, supply, artillery, air war and air defence, electronic warfare, the battle log, the scenario AI commander).
  - **Training centre**: learn the mod step by step.
- Both are also on the mod's home page.

### Scenarios: the AI commander follows the difficulty
- **Easy**: the scenario's script alone, no mod bots. **Normal**: the mod's enemy commander plays like a normal player. **Hard**: it plays much harder.
- **Create a game > Mod AI commander (scenario) > Off** turns it off at every difficulty. Scenario makers can also write `script_only = yes` in `baro_rules.txt`.

### Real weapons and loadouts
- **Chinese missiles** on the Chinese aircraft and helicopters, which used to fire Russian or American missiles: PL-15, PL-10, TY-90, AKD-10, HJ-10, YJ-91, YJ-83K, KD-88, YJ-12 and KD-20.
- **New bombs**: GBU-38 and GBU-32 JDAM, GBU-16 Paveway II, FAB-5000M-54, OFAB-100-120.
- **Tu-95**: one card again. Tu-95M with its FAB-5000 or FAB-9000 bombs, Tu-95MS with its Kh-55.
- **F-15EX**: up to 12 air-to-air missiles.
- **B-1B**: 24 GBU-31 in its bay.
- **Eurofighter**: IRIS-T and Meteor loadouts.

### Chat and effects
- Chat: one key press no longer types two letters, and messages arrive in the right order for every player.
- Smoke from wrecks rises straight.

### Fixes
- WZ551: its 25 mm gun is back.
- Su-30MKK: it fires its Kh-29 instead of circling the target.
- Automatic laser: it lights the target of the attack order.
- A tank sent to a lake shore no longer drives into deep water.

### New vehicles
- They arrive step by step, each one after its check in game.

## 6.0.3 (October 2026)
China with its own vehicle models and real weapons on them; towing with every vehicle; a clean icon for every button; number of players chosen by the host (co-op up to 5, PvP up to 5 v 5); unit cap per player or Dynamic; one enemy commander for every two players; official missions in co-op; host settings for air defence, missile and artillery ranges, aircraft spawn and abandonment; C-RAM against shells, rockets and mortar bombs; real lines of sight over forests; capture by balance of forces; UMPK, SDB, StormBreaker, HARM and JSOW loadouts; a more active AI ally; fixes from player reports.

## 6.0.2 (October 2026)
China playable with new infantry; force fire on buildings with HE; Breakthrough at a real 3 to 1; an AI commander with a player's economy; real ranges of glide bombs and air-to-air missiles; recovery vehicles back; royalty-free music only.

## 6.0.1 (October 2026)
Final game 1.2.1; cards replaced in saved decks instead of removed; abandoned vehicles can be destroyed; Automatic / Manual laser.

## 6.0 (October 2026)
Built for game 1.2.1 (Unity 6); a Vanilla realism mode and a Dynamic unit cap; ranges and speeds checked against real figures; sub-mods through the BARO Workshop.

Older versions: see the Release history in [README.md](README.md).
