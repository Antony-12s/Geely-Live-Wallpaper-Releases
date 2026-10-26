# Geely Live Wallpaper: releases

Signed APK releases of **Geely Live Wallpaper**, a live video wallpaper for Geely EX5 and EX2 head units. The source code is private. This repository only hosts the release files.

The app's **Settings → Check for updates** reads the latest release here. It downloads the APK, checks its SHA-256 against the `SHA256SUMS` file, and then opens Android's installer for you to confirm. Android only accepts an update signed with the same key as the installed app.

## Manual install

1. Download the newest `.apk` from [Releases](../../releases/latest).
2. Verify it:
   ```
   sha256sum -c Geely-Live-Wallpaper-*-SHA256SUMS.txt
   ```
3. Open the APK with the car's file manager, or install it with `adb install -r`.

Credits: Built.Dev By IT EX2 · Co.Dev By Catfish Farm
