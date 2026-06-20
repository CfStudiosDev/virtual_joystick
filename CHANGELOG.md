# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [2.0.0] - 2026-06-20


### Changed

- **Plugin Renaming:** Renamed the plugin to **Virtual Joystick CF**, and updated the `class_name` and scenes to `VirtualJoystickCF` to prevent conflicts with the new native Virtual Joystick node introduced in Godot 4.7.
- **Refactoring:** Full refactor of the folder structure and internal paths to reflect the new nomenclature.

## [1.0.0] - 2026-03-11

### Added

- **Core:** Initial implementation of the `VirtualJoystick` node with full 2D support for Godot 4.5 or later.
- **Direction Modes:** Support for 2-way (Horizontal/Vertical), 4-way, 8-way, and 360° (Analog) movement snapping.
- **Tactile Feedback:** Integrated vibration support for Android and iOS devices with adjustable force.
- **Input Simulation:** Automatic triggering of `InputMap` actions, allowing seamless integration with `Input.get_vector()`.
- **Dynamic & Following Modes:** Feature to spawn the joystick at touch position with configurable screen margins and following behavior.
- **Visual Customization:** Exposed properties for base/stick textures, global scale, and real-time visual updates in the editor.
- **Debug Tools:** Visual indicators in the editor and in-game for deadzones, touch boundaries, and dynamic areas.
- **Documentation:** Comprehensive manuals provided in both Portuguese and English within the `docs/` folder.
- **Utilities:** Included `DirectionUtils` static library for advanced vector manipulation and direction conversions.
