# Changelog

All notable changes to Cyberpunk 2077 Texture Fix are documented here.

## [1.0.0] — November 2026

### Added
- Texture cache rebuild: clears and rebuilds the streaming cache so textures stop popping in late or staying blurry.
- LOD tuning: raises the draw distance for level textures so distant streets stop looking like mush.
- Pop-in fix: reduces texture and geometry pop-in on fast travel and driving.
- VRAM memory tweak: adjusts streaming budgets for low and high memory GPUs.
- Config backup: timestamped copy of the current settings before any change.
- Portable, fully offline operation: one folder, no account, no telemetry.

### Notes
- Native C++ build, 6 MB, no runtime dependencies.
- No game files are modified; only local settings and texture cache are touched.
