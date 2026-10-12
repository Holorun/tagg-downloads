# tagg-downloads

Tagg installers for download, one release per version, with fixed file names:

- `Tagg-Windows-x64.exe` (Windows 10 and 11, 64-bit)
- `Tagg-Mac-AppleSilicon.dmg` (M1 and newer)
- `Tagg-Mac-Intel.dmg`

## latest.json

`latest.json` is the version Tagg tells people about ("Update available" in the T-menu).
This file is the record: every change to it is a commit here, and the live copy the
app reads is published from it. Change it only when **both** platforms' files for that
version are in the matching release, and never by hand on the server.
