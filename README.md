# Safe Temp Cleaner: downloads

Safely free up disk space on Windows 10/11. Safe Temp Cleaner finds temporary files, caches, Windows update leftovers
and stale registry entries of removed programs, shows you every item, and removes only what you confirm.

## Install

Download **`SafeTempCleaner-Setup-x.y.z.exe`** from the [latest release](../../releases/latest) and run it.
No administrator rights or .NET installation are needed.

The app updates itself: it checks this page once a day (or ⋯ menu > *Check for updates*), verifies each installer's
SHA-256 checksum, and shows what's new after every update.

## Verify a download manually

```powershell
Get-FileHash .\SafeTempCleaner-Setup-x.y.z.exe -Algorithm SHA256
```
Compare it with the matching `.sha256` file in the release.
