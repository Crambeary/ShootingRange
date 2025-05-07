---

kanban-plugin: board

---

## Stretch Ideas

- [ ] Movement


## Epic: Settings & Customization

- [ ] [ST] Implement [[settings_menu_notes.md|SettingsManager singleton & persistent user preferences]]
- [ ] [ST] Create graphics settings UI (resolution, fullscreen, V-Sync, FOV)
- [ ] [ST] Create audio settings UI (master/SFX/music volume)
- [ ] [ST] Create controls settings UI (mouse sensitivity, FOV, key rebinding)
- [ ] [ST] Implement save/load of preferences using ConfigFile
- [ ] [ST] Add "Restore Defaults" option to settings menu
- [ ] [ST] Integrate settings menu into main and pause menus
- [ ] [ST] Test settings persistence and error handling


## Menus & QoL

- [ ] [MQ] Main Menu
	  - [ ] Design menu layout
	  - [ ] Add start/quit buttons
	  - [ ] Implement navigation logic
- [ ] [MQ] Pause
	  - [ ] Add pause/resume functionality
	  - [ ] Implement pause menu UI
	  - [ ] Test for bugs
- [ ] [MQ] Mouse Sensitivity Setting
	  - [ ] Add slider to menu
	  - [ ] Connect to input logic
	  - [ ] Save/load setting
- [ ] [MQ] Audio Volume Setting
	  - [ ] Add volume slider
	  - [ ] Connect to audio system
	  - [ ] Save/load setting
- [ ] [MQ] UI Prompts and Feedback
	  - [ ] Identify key prompts needed
	  - [ ] Implement UI messages
	  - [ ] Playtest for clarity
- [ ] [MQ] Easy Exit/Restart
	  - [ ] Add exit/restart buttons to menus
	  - [ ] Implement logic for exit/restart
	  - [ ] Test for reliability
- [ ] [MQ] UI Sounds for Menus
	  - [ ] Source/craft UI sounds
	  - [ ] Integrate with menu navigation
	  - [ ] Playtest for feedback


## Gun Feel

- [ ] [GF] Gun Model
	  - [ ] Find reference images
	  - [ ] Block out basic shape in engine
	  - [ ] Add textures/materials
- [ ] [GF] Muzzle VFX
	  - [ ] Prototype muzzle flash effect
	  - [ ] Add lighting burst synced with firing
	  - [ ] Polish VFX timing
- [ ] [GF] SFX
	  - [ ] Source or create gunshot sound
	  - [ ] Implement sound trigger
	  - [ ] Adjust volume/mix
- [ ] [GF] Bullet
	  - [ ] Implement bullet logic (raycast or projectile)
	  - [ ] Test hit registration
	  - [ ] Add impact effect
- [ ] [GF] Crosshair / Iron Sights
	  - [ ] Design crosshair/iron sights
	  - [ ] Implement aiming logic
	  - [ ] Playtest for clarity
- [ ] [GF] Weapon Sway
	  - [ ] Implement basic sway math
	  - [ ] Tune for feel
	  - [ ] Playtest and tweak
- [ ] [GF] Recoil and Recovery
	  - [ ] Add recoil kick
	  - [ ] Implement smooth recovery
	  - [ ] Playtest for fun
- [ ] [GF] Polished Animations (shooting, idle, aiming)
	  - [ ] Create/collect animation assets
	  - [ ] Integrate into engine
	  - [ ] Polish transitions
- [ ] [GF] Hit Detection
	  - [ ] Implement hit detection logic
	  - [ ] Add debug visualization
	  - [ ] Playtest for accuracy
- [ ] [GF] Visual Hit Indicators (hit marker, target flash)
	  - [ ] Design hit marker/target flash
	  - [ ] Implement feedback on hit
	  - [ ] Playtest for clarity


## Foundation

- [ ] [FD] Level Blockout
	  - [ ] Add basic geometry for play area
	  - [ ] Set up navigation space
	  - [ ] Place placeholder obstacles/targets
- [ ] [FD] PlayerCharacter Scene
	  - [ ] Create PlayerCharacter.tscn
	  - [ ] Add child nodes (Camera3D, CollisionShape3D, MeshInstance3D, etc.)
- [ ] [FD] Camera Setup
	  - [ ] Attach Camera3D to PlayerCharacter
	  - [ ] Implement aiming with mouse only (no movement)
- [ ] [FD] Input Map
	  - [ ] Define input actions (aim, shoot, pause)
- [ ] [FD] Core Gameplay Loop
	  - [ ] Implement aiming and shooting logic
	  - [ ] Add hit detection on static target
	  - [ ] Provide immediate feedback (muzzle flash, sound, UI)
- [ ] [FD] Placeholder Assets
	  - [ ] Import or create temporary meshes and textures
- [ ] [FD] TileMapLayer Setup
	  - [ ] Add TileMapLayer nodes if using tiles
	  - [ ] Configure layers for collision, navigation, visuals
- [ ] [FD] Lighting Setup
	  - [ ] Add basic DirectionalLight3D or other lights
	  - [ ] Test visibility and mood


## Next Up

- [ ] [FD] Main Scene
	  - [ ] Create Main.tscn
	  - [ ] Add root node (Node or Node3D)


## In Progress

- [ ] [FD] Godot Project Setup
	  - [x] Create new Godot 4.4 project
	  - [ ] Configure project settings (window size, name, etc.)


## Done

**Complete**
- [x] Outline Project Scope
- [x] Start GDD




%% kanban:settings
```
{"kanban-plugin":"board","list-collapse":[true,true,true,false,false,false,false]}
```
%%