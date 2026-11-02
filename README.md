# SHELLS — releases

Built games only. Source lives in a private repo.

**Install:** download `SHELLS-Setup-<version>.exe` from the [latest release](https://github.com/ArthurJClack/shells-release/releases/latest) and run it (per-user, no admin).

**Updates are automatic.** Every time you start SHELLS the launcher checks
`https://github.com/ArthurJClack/shells-release/releases/latest/download/manifest.json`
(plus a local `Documents/shells/updates` folder) and installs any newer build before the game starts.
The launcher updates itself the same way.

Each release carries:

| file | what |
|---|---|
| `manifest.json` | build number, version, file names and SHA-256 checksums |
| `shells-<version>.zip` | the game build (game pack, server, bots, AI lab, map maker, matchmaker, shared data) |
| `shells-launcher-<build>.pck` | the launcher / updater |
| `SHELLS-Setup-<version>.exe` | full installer for new players |
