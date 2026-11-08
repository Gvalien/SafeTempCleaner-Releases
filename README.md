# Safe Temp Cleaner: downloads

Safely free up disk space on Windows 10/11. Safe Temp Cleaner finds temporary files, caches, Windows update leftovers
and stale registry entries of removed programs, shows you every item, and removes only what you confirm.

## Install

Download **`SafeTempCleaner-Setup-x.y.z.exe`** from the [latest release](../../releases/latest) and run it.
No administrator rights or .NET installation are needed.

### "Windows protected your PC"

The installer is not code-signed yet, so Microsoft Defender SmartScreen may show this message the first time you
run it. Click **More info**, check that the file name is `SafeTempCleaner-Setup-x.y.z.exe`, then click
**Run anyway**. If you want to be sure the file is genuine, verify its checksum (see below). Updates installed from
inside the app do not show this message.

## Updates

The app updates itself: it checks this page once a day (or ⋯ menu > *Check for updates*), verifies each installer's
SHA-256 checksum, and shows what's new after every update.

## Verify a download manually

```powershell
Get-FileHash .\SafeTempCleaner-Setup-x.y.z.exe -Algorithm SHA256
```
Compare it with the matching `.sha256` file in the release.
