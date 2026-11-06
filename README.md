# Lune downloads

Lune is a macOS browser built on Chromium, ungoogled-chromium, and Helium, with
selected upstream contributions and Lune customization. Website: https://lune.computer.

This repository hosts signed installers, checksums, exact source inputs, and
validation evidence. Apple silicon and Intel use separate downloads and Sparkle
update feeds. Helium provides extension downloads, bangs, and other browser
services when enabled; Lune provides browser updates.

## Release status

The first release is undergoing acceptance testing. Prereleases are test builds;
no stable browser release or stable update feed has been promoted yet.

Use the DMG matching your Mac: `arm64` for Apple silicon or `x86_64` for Intel.
Open the DMG, drag Lune to Applications, then open Lune normally. The app and disk
image are signed and notarized; bypassing Gatekeeper should not be necessary.
Keep an existing Lune installation and profile backed up before testing updates.

Each release includes SHA-256 checksums, source locks, and a corresponding source
kit plus the pinned source/dependency archives. Build instructions and retained
component licenses are inside the source kit. Lune modifications are GPL-3.0;
imported components retain their respective licenses.
