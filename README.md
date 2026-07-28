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

For a normal install, download **only** the `.dmg`.

| Asset | Who needs it |
|-------|----------------|
| `Moxus_*_aarch64.dmg` | **You** — fresh install on Apple silicon |
| `latest.json` | App updater (automatic; no manual download) |
| `Moxus_*.app.tar.gz` | App updater (automatic; no manual download) |

Ignore GitHub’s automatic **Source code** zip/tar.gz links — this repo is installers only, not the application source.

Current first-party target: **macOS arm64**. Additional platforms may be added in later releases.

### Install (macOS)

1. Download the `.dmg` from the latest release.
2. Open the disk image and drag **Moxus** into Applications.
3. Launch Moxus from Applications (or Spotlight).

If macOS Gatekeeper prompts on first launch, open **System Settings → Privacy & Security** and allow the app, or right-click the app and choose **Open**.

### Update

Installed builds can check for updates from **Settings → About**. Updates are signature-verified before install.

## What this repo is / is not

| Is | Is not |
|----|--------|
| Public download + updater CDN for Moxus Desktop | Source code mirror |
| Signed installers and `latest.json` | Issue tracker for product bugs (prefer your support channel) |
| Versioned GitHub Releases | Nightly / unsigned CI dumps |

## License

Release artifacts in this repository are proprietary software. See [`LICENSE`](./LICENSE).

Copyright © Moxus. All rights reserved.
