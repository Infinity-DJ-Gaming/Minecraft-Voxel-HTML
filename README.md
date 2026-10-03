# Minecraft Browser Sandbox — v1.4.0

Replace your GitHub Pages **index.html** with the update. Keep your extracted assets beside it, with original filenames and subfolders:

```text
index.html
README.md
SFX/
Music/
  music/game/
  music/menu/
  records/
```

Pixel icons and libraries are built into index.html. No sound ZIP is required. Audio starts after a click or key press. Options has music/sound toggles, volumes and local folder selection.

## Multiplayer

1. Create a singleplayer world or use an existing save.
2. Open **Multiplayer**, choose **Online / same Wi-Fi**, select a world, then **Host selected world**.
3. Copy the eight-character code or invite link. Friends open the same updated website, choose Multiplayer, enter the code and click **Join room**. Everyone needs v1.4.
4. Keep the host’s game open. **T** opens chat; **Tab** opens players and invites. `/msg Name message` whispers; `/players` opens the list; `/spawn` returns to spawn.

Online uses PeerJS signaling and WebRTC. Some networks need a TURN relay; Advanced connection settings supports your own relay or signaling server. **Local tabs** connects tabs of the same site in the same browser; use Online for other devices.

Rooms include passwords, 2/4/8-player limits, shared terrain, creatures, drops and containers, optional PvP, building permissions, friend bookmarks, mute and host kick controls. The host leads dimension travel. Shared containers lock while another player uses them. Keep the host’s tab active for the best performance; browsers can slow background tabs.

## Profiles and controls

Use the bottom-left **Profile** button or **Options → Account / profile settings** to rename your player, change colors, import a 64 × 64 PNG skin, or manage/export profiles. Profiles are local display identities, not Microsoft/Mojang accounts. Connected players can change appearance but cannot switch profiles mid-room.

**WASD** move · **Space** jump · **Shift** sprint · **C** descend in Creative · double Space or **F** fly · **E** inventory · **Q** drop · **M** map · **1–9** hotbar · **Escape** menu. **F5** cycles first person, behind and front views. Rebind controls in Options.

F5 refresh and delivered browser shortcuts are intercepted while playing. **Fullscreen & keyboard protection** requests Keyboard Lock where supported. A website cannot guarantee blocking reserved browser or OS shortcuts such as Ctrl+W in every browser.

## Saves and patch notes

Browser saves and imported 1.0–1.3 backups migrate while preserving terrain, builds, equipment and progress. The host saves the shared world and each guest’s separate inventory. Rejoin with the same device profile to restore your items. Guests can **Save a local world copy**, including after the host disconnects. Export world backups and profiles before moving devices.

In-game **Patch notes** includes v1.4 and earlier releases: Nether and End progression, crafting, Elytra, armor, enchantments, spears, music and world settings. `Minecraft-source.zip` contains editable source and library licenses; SFX and Music remain separate.
