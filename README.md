# Hitori Client – Modified Build

<img src = "hitori.png">
A modified build of **Hitori Client** for Minecraft 1.12.2, with selected initialization and compatibility fixes.

## Information

- **Minecraft Version:** 1.12.2
- **Forge Version:** 14.23.5.2860
- **Client Version:** v1.0.0

## Changes

- Removed HWID verification.
- Fixed missing font fallback when `1.ttf` is unavailable.
- Fixed a font renderer initialization crash.
- Updated initialization code to avoid references to the removed HWID check.

## Installation

1. Install Minecraft 1.12.2.
2. Install Minecraft Forge 14.23.5.2860.
3. Download the modified Hitori JAR.
4. Place the JAR inside your `.minecraft/mods` folder.
5. Launch Minecraft using the Forge 1.12.2 profile.

## Font Information

The client attempts to load `1.ttf` from the Minecraft game directory.

If the font file is unavailable, the client falls back to Arial.

## Disclaimer

This is a modified build. It is not necessarily affiliated with or endorsed by the original Hitori developers.

Use at your own risk. Always keep backups of your Minecraft files.

## Credits

- Igrik 2.0.
- GameV.
