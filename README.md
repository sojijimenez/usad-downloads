# USAD downloads

USAD for the Android phone and the Windows PC.

**Download the latest version:** https://github.com/sojijimenez/usad-downloads/releases/latest

Under "Assets" on that page:
- `USAD-Mobile-<version>-release.apk` - Android phone
- `USAD-Desktop-Setup.exe` - Windows PC
- `READ ME FIRST - USAD Tester Pack.pdf` and `QUICK START - USAD Tester Pack.png` - start here

**Windows warning:** the installer is not code-signed, so Windows may say "Windows protected your PC".
Click "More info", then "Run anyway".

**Check your download (optional):** open PowerShell in the folder with the file and run
`Get-FileHash .\<file name>`, then compare with `SHA256SUMS.txt` on the release page.
