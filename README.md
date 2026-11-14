# Agenzya Desktop

Downloads for **Agenzya Desktop**, the desktop app of [Agenzya](https://agenzya.com): your tasks, timer, timesheet, chat, agent and notifications, one click away from the menu bar or system tray.

This repository holds no code. Its [**Releases**](https://github.com/emiketic/agenzya-desktop-releases/releases) are where each version's installers are published, and where installed apps look for updates.

## Download

Open the [Releases](https://github.com/emiketic/agenzya-desktop-releases/releases) page and pick the newest version. Under **Assets**, download the file for your system:

| System | File | Notes |
| --- | --- | --- |
| macOS 12 or later (Apple silicon and Intel) | `Agenzya-<version>-universal.dmg` | Open it and drag Agenzya to Applications. Signed and notarized by Apple. |
| Windows 10 / 11 (64-bit) | `Agenzya-Setup-<version>.exe` | Run the installer. Until the app is code-signed, Windows SmartScreen may warn: choose **More info → Run anyway**. |
| Ubuntu / Debian (64-bit) | `agenzya_<version>_amd64.deb` | `sudo apt install ./agenzya_<version>_amd64.deb` |
| Other Linux (64-bit) | `Agenzya-<version>-x86_64.AppImage` | `chmod +x` the file, then run it. |

The `.zip`, `.blockmap` and `latest*.yml` files are used by the app's automatic updates; you don't need to download them.

## Updates

The app checks for new versions and installs them itself (Settings → Updates).

- **Stable** releases are the default.
- **Beta** versions are published as pre-releases. To receive them, choose the beta channel in Settings → Updates.

## Signing in

Sign in with your Agenzya account (email and password, or Google). You need an existing Agenzya workspace: ask your workspace admin for an invitation.

## Help

- Help centre: [help.agenzya.com](https://help.agenzya.com)
- Website: [agenzya.com](https://agenzya.com)
