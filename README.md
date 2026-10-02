# Minecraft Browser Sandbox — v1.3.0

Replace your GitHub Pages **index.html** with this update. Keep the extracted **SFX** folder and upload your supplied **Music** folder beside it:

```text
index.html
README.md
SFX/                 # original sound subfolders
Music/
  music/
    game/            # creative, end, nether, water, etc.
    menu/
  records/
```

Keep all original filenames and subfolders. No ZIP is required. Icons and game code are embedded in the HTML. Reload the site after uploading; audio begins after a click or keypress. **Options** has independent music/sound toggles, volumes, tests and local folder pickers.

**v1.3:** Elytra, End ships, rocket boosts, durable armor, Netherite upgrades, enchanting/anvil/smithing stations, 17 enchantments, spears, credits, automatic music, mineshafts, biome village styles, rarer Nether structures, varied piglin trades, supplied icons and matching 3D held items. Earlier features remain. Open **Patch notes** for the complete history.

**Controls:** WASD moves, Space jumps, E opens inventory, Esc pauses. Left-click mines/attacks; right-click places/uses. Change keys in Options. Creative double-jump toggles flight. Equip Elytra in the chest slot, press Jump airborne to glide, and use rockets to boost. Spears jab with left-click and charge while moving with right-click held. Shift-click transfers/equips items. The inventory’s book button toggles recipes/item search.

**Worlds:** creation settings include difficulty, cheats, Keep Inventory, Superflat, bonus chest and generation rules. **Edit** or pause → World settings changes names, mode and rules. Delete has a recovery copy and a restore button. Seed/terrain type stay fixed after creation.

**Saves:** browser worlds and imported v1 backups upgrade automatically, preserving builds, items, stations and progress. New backups retain enchantments, durability and rules. Older worlds retain their terrain/landmarks and gain exploration sites. Keep the same browser/site address for browser saves; use exported backups to move devices or URLs. Export before updating.

This remains a simplified recreation: flight physics, structures, enchanting offers, anvil costs and spear timings approximate Minecraft. Holding gold to pacify piglins is your custom rule. Official references: [Elytra](https://www.minecraft.net/en-us/article/taking-inventory--elytra), [spears](https://www.minecraft.net/en-us/article/minecraft-java-edition-1-21-11), [piglins](https://www.minecraft.net/en-us/article/meet-piglins).

**Minecraft-source.zip** contains editable modules; audio is separate. Prepend future releases in `releases.js`, preserve block IDs, and extend `saves.js` for migrations.
