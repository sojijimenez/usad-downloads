# USAD downloads

USAD for the Android phone and the Windows computer.

## Download

**Go to the latest version:** https://github.com/sojijimenez/usad-downloads/releases/latest

USAD has two apps: one for the phone and one for the computer. Download the app for **each device you will use**.
If you use both a phone and a computer, download **both**. On that page, scroll down to **Assets**:

| Device | App | File to download |
|---|---|---|
| Android phone | USAD Mobile | `USAD-Mobile-<version>-release.apk` |
| Windows computer | USAD Desktop | `USAD-Desktop-Setup.exe` |

New to USAD? Start with the `READ ME FIRST` PDF (full guide) or the `QUICK START` picture on the same page.
Ignore "Source code (zip)" and "Source code (tar.gz)": GitHub adds them automatically and you do not need them.

The page itself also has step-by-step install instructions for phone and computer.

## Warnings you may see
- **Windows:** "Windows protected your PC". The installer is not code-signed. Click **More info**, then **Run anyway**.
- **Android:** "Can't install apps from this source". Tap **Settings**, switch on **Allow from this source**, then go back and tap **Install**.

## Check your download (optional)
Open PowerShell in the folder with the file and run `Get-FileHash .\<file name>`, then compare with `SHA256SUMS.txt` on the release page.
