# HALO by LYRA — downloads

HALO is a free, local-first AI workspace: **Halo Office** (your team of AI agents) and the **Halo notch app** for Mac.
Website: https://www.lyraengine.site

This repository only hosts the installers. Get the latest from **[Releases](https://github.com/Josekpapa/halo-releases/releases/latest)**.

| Download | For |
|---|---|
| [HALO-Office-mac-apple-silicon.dmg](https://github.com/Josekpapa/halo-releases/releases/latest/download/HALO-Office-mac-apple-silicon.dmg) | Macs with M1, M2, M3, M4 (macOS 12+) |
| [HALO-Office-mac-intel.dmg](https://github.com/Josekpapa/halo-releases/releases/latest/download/HALO-Office-mac-intel.dmg) | Intel Macs (macOS 12+) |
| [HALO-Notch-mac.dmg](https://github.com/Josekpapa/halo-releases/releases/latest/download/HALO-Notch-mac.dmg) | The notch app, any Mac on macOS 15+ |
| [HALO-Office-windows-setup.exe](https://github.com/Josekpapa/halo-releases/releases/latest/download/HALO-Office-windows-setup.exe) | Windows 10/11 (64-bit) |

## Installing on Mac

1. Open the `.dmg` and drag the app into **Applications**.
2. Open it from Applications. macOS will say it can't verify the developer. This early release isn't notarized by Apple yet.
3. Go to **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to the app's name. Confirm with **Open Anyway** again.
4. That's it. It opens normally from now on.

## Installing on Windows

1. Run `HALO-Office-windows-setup.exe`.
2. If you see **"Windows protected your PC"**, click **More info → Run anyway**. The installer isn't code-signed yet.
3. Follow the installer. It installs for your user only, so you don't need admin rights.

## Verify your download (optional)

Each release includes `SHA256SUMS.txt`. On Mac: `shasum -a 256 <file>`. On Windows: `certutil -hashfile <file> SHA256`.

---
© 2026 LYRA
