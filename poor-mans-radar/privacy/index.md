---
title: Poor Man's Radar — Privacy Policy
---

# Poor Man's Radar — Privacy Policy

_Last updated: 2026-11-07_

Poor Man's Radar helps you find **your own** Bluetooth devices (earbuds, tags, watches) by their
signal. It is open source: https://github.com/uzvld/Poor-Mans-Radar. Developer: uzvld.

## The short version

- Everything the app computes, it computes on your phone. We run no servers and collect nothing.
- No accounts, no analytics, no crash reports, no tracking.
- What the app keeps on your phone is encrypted with a key that stays on your phone.
- If you turn on backup, an encrypted copy goes to **your own** iCloud or Google Drive. It is
  end-to-end encrypted: neither we, nor Apple, nor Google can read it.

## What the app keeps on your phone

Your own devices and their calibration, your home map (walls, rooms, signal heatmaps), the last
place where each of your own devices was heard, anonymous landmark statistics (a salted hash of a
nearby static device's address, never its name or address), and your settings. Session logs are
recorded only when you turn recording on and stay on the phone until you share them yourself.

The app never shows, follows or keeps other people's devices.

## Permissions and why

- **Bluetooth / Nearby devices** — to hear your devices. On Android 12+ the system also requires
  **location** for Bluetooth scan results; the app does not use or store your location for search.
- **Location (while using, and optionally in the background)** — only for "Remember where I left it":
  the last place each of your own devices was heard, one place per device, encrypted on the phone.
- **Motion & fitness / Physical activity** — steps and turns to point the arrow while you walk.
- **Camera** — only while you scan your home; frames are never stored or shown.
- **Wi-Fi state (Android)** — signal strength of your own network as a landmark at home.

## Backup (optional, on by default)

An encrypted archive is stored in your iCloud (private database of the app) or your Google Drive
(hidden app folder, `drive.appdata` access only). Between iPhone and Android it is unlocked with a
passkey from your password manager (or a passphrase / PIN you choose). Turn backup off in Settings to
delete the cloud copy. You can revoke the app's Google access at https://myaccount.google.com/permissions.

## Sharing

Nothing is shared with us or third parties. Links to other apps (Find My, Samsung Find, Find Hub,
Tile) open those apps only when you tap them, and pass nothing from Poor Man's Radar.

## Children

The app is not directed at children.

## Contact and deletion

Delete the app to delete everything on the phone; turn off backup to delete the cloud copy.
Questions: https://github.com/uzvld/Poor-Mans-Radar/issues.
