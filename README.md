# Minecraft Browser Sandbox — Adventure Update

## GitHub Pages setup

1. Rename **Minecraft.html** to **index.html**, replacing your old game HTML.
2. Put **SFX.zip** beside index.html in your Pages repository. Keep the ZIP and all sound names unchanged; no extraction is needed.
3. Commit and push both files, then reload your site. **Options → Test sound** should show **2,728 original sound files**. Clicking the page enables audio.

SFX.zip is about **87 MiB**. Use GitHub Desktop or `git push`: GitHub's [browser uploader allows only 25 MiB per file](https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository).

## What's new

- **Options → Controls / change keys** remaps controls. Conflicts swap; Escape cancels.
- Creative: **press Jump twice quickly** to toggle flight. Jump rises, Ctrl descends; F also toggles flight by default.
- Visible **2×2 / 3×3 crafting grids**. Wooden tools accept **any wood, including mixed planks**. Shift-click a recipe for a batch, then select **Craft all**.
- New biomes, pillager outposts, Nether gold/quartz ores, fortresses, bastions, ghasts, blazes and piglins.
- Brew up to three water bottles with Nether wart, then a potion ingredient. Blaze powder fuels the stand.
- Craft **Eyes of Ender** from pearls and blaze powder. Follow them to a stronghold; fill its **12 portal frames**. Destroy End crystals, defeat the dragon and return through the exit portal.

Existing saves remain compatible. Export a backup from the pause menu before replacing your HTML. New biomes appear farther from spawn. Structures and mechanics are simplified in this browser recreation.

For local play, open the HTML and use **Options → Choose local sound ZIP**. **Minecraft-source.zip** contains editable code; sounds are supplied separately.
