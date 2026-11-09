# Lune downloads

Lune is a macOS browser built on Chromium, ungoogled-chromium, and Helium, with
selected upstream contributions and Lune customization. Visit [lune.computer](https://lune.computer).

## Download

- [Apple silicon](https://github.com/leebyron/lune-downloads/releases/latest/download/Lune-macos-arm64.dmg)
- [Intel](https://github.com/leebyron/lune-downloads/releases/latest/download/Lune-macos-x86_64.dmg)
- [Release notes and versioned downloads](https://github.com/leebyron/lune-downloads/releases/latest)

These links follow the latest production release. Previous versions remain in
[Releases](https://github.com/leebyron/lune-downloads/releases). macOS 13 or newer
is required. Open the matching DMG, drag Lune to Applications, and open it normally.
The app and disk image are Developer ID signed and notarized by Apple. Do not
bypass a Gatekeeper warning; report it instead.

Lune 26.1109.1 uses Chromium 158.0.8127.18. Signed installation, browsing,
persistence and installed updates pass on Apple silicon and Intel under Rosetta.
Physical Intel and older-macOS testing remain pending; the owner chose to publish
and address any discovered issues in subsequent versions. See the release notes
for known limitations and the Chromium Stable comparison.

## Updates and source

Browser updates use architecture-specific Sparkle feeds hosted here:
[Apple silicon](https://raw.githubusercontent.com/leebyron/lune-downloads/main/updates/stable/mac/appcast-arm64.xml)
and [Intel](https://raw.githubusercontent.com/leebyron/lune-downloads/main/updates/stable/mac/appcast-x86_64.xml).
Enable browser updates during setup or in Settings; About checks for updates.
Helium provides optional extension downloads, bangs, and other browser services.
Lune provides browser updates.

Each release includes SHA-256 checksums, source locks, and a matching source kit
plus pinned source/dependency archives. Build instructions and retained component
licenses are inside the source kit. Lune modifications are GPL-3.0; imported
components retain their respective licenses. Signing credentials are excluded.

The repository's release tags identify distribution history. The source kit and
release metadata identify the exact browser source commit. Previously published
build-1/build-2 test artifacts remain unchanged; current releases use production
only, with no public staging or prerelease channel.
