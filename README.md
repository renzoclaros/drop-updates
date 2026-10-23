# Drop for Mac

This repository hosts Drop installers, signed app-update feeds, and release notes. The app source code is maintained separately.

## Download

Download the DMG from [the latest release](https://github.com/renzoclaros/drop-updates/releases/latest).

Requires an Apple silicon Mac (M1 or newer) with macOS 13.5 or later.

1. Open the DMG and drag Drop to Applications.
2. Eject the disk image, then open Drop from Applications.

## Updates

Starting with Drop 1.5.0, use **Drop → Check for Updates…** or **Settings → Updates → Check for Updates…** to update the app. Checks are manual. The download engine has a separate update control.

Drop verifies signed update feeds and signed installers before installation. Released app bundles and disk images are Developer ID signed and Apple-notarized. Installation waits for current work to finish.

Users on 1.4.5 or earlier need to install the first updater-enabled version manually once.

The stable signed feed is [appcast.xml](https://github.com/renzoclaros/drop-updates/releases/latest/download/appcast.xml).

SHA-256 checksum files are included with releases. Only installers, update feeds, checksums, and release notes are published here.
