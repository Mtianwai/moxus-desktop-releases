<p align="center">
  <img src="./moxus-logo.png" alt="Moxus" width="96" />
</p>

# Moxus Desktop Releases

**Language / 语言:** English | [中文](./README.zh-CN.md)

Public distribution channel for **Moxus Desktop** installers and in-app updater metadata.

This repository contains **release artifacts only**. Application source code is not published here.

## Download

Use the latest GitHub Release:

**[Download Moxus Desktop](https://github.com/Mtianwai/moxus-desktop-releases/releases/latest)**

Pick the installer for your OS — ignore updater packages and GitHub’s automatic **Source code** archives.

| Asset | Who needs it |
|-------|----------------|
| `Moxus_*_aarch64.dmg` | **macOS** (Apple silicon) — fresh install |
| `Moxus_*_x64-setup.exe` | **Windows** (x64) — fresh install (NSIS) |
| `latest.json` | App updater (automatic; no manual download) |
| `Moxus_*.app.tar.gz` / `*.nsis.zip` | App updater (automatic; no manual download) |

Supported first-party targets: **macOS arm64** and **Windows x64**.

### Install (macOS)

1. Download the `.dmg` from the latest release.
2. Open the disk image and drag **Moxus** into Applications.
3. Launch Moxus from Applications (or Spotlight).

If macOS Gatekeeper prompts on first launch, open **System Settings → Privacy & Security** and allow the app, or right-click the app and choose **Open**. (Apple notarization is not enabled yet.)

### Install (Windows)

1. Download the `*-setup.exe` from the latest release.
2. Run the installer and follow the prompts.
3. Launch **Moxus** from the Start menu.

Builds are not Authenticode-signed yet; Windows SmartScreen may warn on first launch. Choose **More info → Run anyway** if you trust this release channel.

### Update

Installed builds can check for updates from **Settings → About**. Updates are signature-verified before install.

## What this repo is / is not

| Is | Is not |
|----|--------|
| Public download + updater CDN for Moxus Desktop | Source code mirror |
| Release installers and `latest.json` | Issue tracker for product bugs (prefer your support channel) |
| Versioned GitHub Releases | Nightly CI dumps |

## License

Release artifacts in this repository are proprietary software. See [`LICENSE`](./LICENSE).

Copyright © Moxus. All rights reserved.
