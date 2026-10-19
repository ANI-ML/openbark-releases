<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="brand/openbark-lockup-horizontal-outlined-on-dark.svg">
    <img src="brand/openbark-lockup-horizontal-outlined.svg" width="300" alt="OpenBark">
  </picture>
</p>

<p align="center"><strong>Installers for OpenBark, the free AI scribe for veterinary medicine. It runs on your clinic's own computer.</strong></p>

## Download

| Your computer | Download | How to install |
|---|---|---|
| **Windows** 10 or 11 (64-bit) | [**OpenBark-Setup.exe**](https://github.com/ANI-ML/openbark-releases/releases/latest/download/OpenBark-Setup.exe) | Open the file and follow the setup wizard. No administrator rights needed. |
| **macOS** 13 or later (Apple silicon) | [**OpenBark.dmg**](https://github.com/ANI-ML/openbark-releases/releases/latest/download/OpenBark.dmg) | Open the disk image and drag OpenBark to Applications. |
| **Linux**: Ubuntu, Debian | [openbark_amd64.deb](https://github.com/ANI-ML/openbark-releases/releases/latest/download/openbark_amd64.deb) | `sudo apt install ./openbark_amd64.deb` |
| **Linux**: Fedora | [openbark.x86_64.rpm](https://github.com/ANI-ML/openbark-releases/releases/latest/download/openbark.x86_64.rpm) | `sudo dnf install ./openbark.x86_64.rpm` |
| **Linux**: any distribution | [OpenBark.AppImage](https://github.com/ANI-ML/openbark-releases/releases/latest/download/OpenBark.AppImage) | Make it executable, then run it. |

These links always point to the newest version. Older versions and checksums (`SHA256SUMS.txt`) are on the [Releases page](https://github.com/ANI-ML/openbark-releases/releases).

**OpenBark is in beta.** It hasn't been validated in real clinics yet: review every draft before you sign it. The installers aren't code-signed yet, so the first time you open OpenBark:
- **Windows** may show "Windows protected your PC". Click **More info**, then **Run anyway**.
- **macOS** may say Apple can't check the app. Open **System Settings > Privacy & Security**, scroll down, and click **Open Anyway** next to OpenBark. (On macOS 13 and 14 you can also right-click OpenBark in Applications and choose **Open**.)

More at [openbark.io](https://www.openbark.io). Built by the [ANI.ML Health](https://www.animl.health) team. Apache-2.0. Questions: we.care@animl.health
