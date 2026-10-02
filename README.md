# Minecraft Browser Sandbox — v1.2.0

## GitHub Pages

Replace your repository's **index.html** with the updated **index.html** (or rename Minecraft.html to index.html). Keep your extracted **SFX** folder beside it:

```text
index.html
README.md
SFX/
  ambient/
  block/
  dig/
  mob/
  random/
  step/
  …other original sound subfolders
```

Keep every original sound filename and subfolder unchanged. The default sound path is **SFX/**; no ZIP is needed. Commit the update, reload your site, then click **Options → Test sound**. Sounds start after you interact with the page.

## Updates & controls

Open **Patch notes** from the title screen or pause menu for v1.2.0 and the earlier Adventure Update: all 2,728 sounds indexed, custom keybinds, Creative double-jump flight, better crafting, Nether ores/fortresses/bastions/mobs, outposts, more biomes, brewing, strongholds and the End boss fight.

Move with **WASD**, jump with **Space**, open inventory with **E**, and pause with **Esc**. Change keys and sound volume in **Options**. Wooden tools accept any mixed planks; crafting tables use a visible 3×3 grid.

Existing saves stay compatible. Export a world backup from the pause menu before updating. New biomes appear farther from spawn; mechanics are simplified in this browser recreation.

For local play, keep SFX beside the HTML or use **Options → Choose local sound folder**. The optional ZIP picker still works. **Minecraft-source.zip** contains editable code; sounds are supplied separately. Add each future update to the start of `releases.js` to update the version and preserve earlier notes.
