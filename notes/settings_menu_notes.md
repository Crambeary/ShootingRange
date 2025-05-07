# Settings Menu & User Customization (FPS Game)

This file is WIKILinked from the Kanban and contains details, references, and implementation notes for user-customizable settings in the 3D FPS Shooting Range game.

## Key Customizable Settings
- Resolution (dropdown)
- Fullscreen/windowed toggle
- V-Sync toggle
- FOV (slider, e.g., 75–110)
- Mouse sensitivity (slider)
- Master, SFX, and Music volume (sliders)
- Graphics quality (presets or toggles)
- Key rebinding (optional/advanced)

## Implementation Notes
- Use a `SettingsManager` singleton (autoload) to manage loading/saving settings.
- Store settings in `user://settings.cfg` using Godot's `ConfigFile`.
- On game start, load settings and apply them to ProjectSettings and AudioServer.
- Use Godot's InputMap for key rebinding.
- UI should provide real-time feedback (e.g., FOV slider updates camera immediately).
- Add a "Restore Defaults" button.
- Settings menu should be accessible from both main menu and pause menu.

## References
- [Godot Docs: Project Settings](https://docs.godotengine.org/en/stable/tutorials/editor/project_settings.html)
- [Godot FPS Template](https://github.com/godotengine/godot-demo-projects/tree/master/3d/fps)
- [Godot ConfigFile Usage](https://docs.godotengine.org/en/stable/classes/class_configfile.html)

## Task Breakdown (see Kanban for tracked tasks)
- See [[ShootingRange Kanban.md]] for actionable tasks and progress tracking.
