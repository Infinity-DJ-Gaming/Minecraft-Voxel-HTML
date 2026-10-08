# Minecraft Browser Sandbox · 1.5.0

Upload **index.html** to GitHub Pages. Keep your extracted **SFX/** and **Music/** folders beside it, preserving their original filenames and subfolders. Icons, fonts and the game code are embedded in the HTML.

This update adds Firebase accounts, friends and direct messages; optional online voice; live server roles/settings; targeted commands with Tab completion; improved pixel visuals and held-item grips; crouching/PvP fixes; Elytra drag and air sounds; particles; and broader terrain/structure generation. Full patch notes are in the game.

**Accounts need a one-time Firebase setup:** follow **FIREBASE-SETUP.md** and publish the included **firestore.rules**. Your public Firebase configuration and automatic TURN relay are already included.

Host a saved world in **Multiplayer** and share its eight-character room code. Everyone needs version 1.5. Keep the host’s game open. Voice is available in Online rooms over HTTPS after enabling the microphone.

**Controls:** WASD move · Space jump · Shift crouch · R sprint · E inventory · T chat · Tab complete commands / open players · F5 cycle cameras · V push to talk · Esc menu. Change keys in Options. Browser/OS shortcuts such as Ctrl+W cannot be guaranteed to stay captured.

Examples: `/give @s diamond_sword 1`, `/gamemode Test_Friend creative`, `/tp @a @s`, `/role Test_Friend operator`. Replace spaces in player names with underscores. World cheats or room operator permission are required for modifying commands.

Existing browser saves and imported backups remain compatible. Export a backup before updating and keep the same website address to retain browser saves. Old worlds preserve their original terrain; create a new world for the revised caves, villages and regional structures. Friends/account data use Firebase; worlds stay on the device.

This is an independent, simplified voxel recreation. **Minecraft-source.zip** contains editable source and library licenses. It excludes your large sound/music folders; keep using the folders already in your repository.
