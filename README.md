# TapGlow Releases

Signed and notarized TapGlow releases — binaries only, no source code.

Each release attaches two artifacts under a stable URL pattern:

    https://github.com/tapglow-app/tapglow-release/releases/download/v<version>/TapGlow-<version>.zip
    https://github.com/tapglow-app/tapglow-release/releases/download/v<version>/TapGlow-<version>.dmg

- `TapGlow-<version>.zip` — Sparkle auto-update archive (referenced by the update feed).
- `TapGlow-<version>.dmg` — first-install drag-to-Applications image.

The Sparkle update feed is served at https://tapglow-landing.pages.dev/appcast.xml.
Source repository: https://github.com/mysideproject/tapglow (private).

TapGlow is an MIT-licensed fork of ClickLight by Aurora Scharff; see the source
repo's LICENSE/NOTICE for attribution.

> This repo is private until the first public release. Private download links
> require a GitHub login (anonymous Sparkle clients cannot fetch them).
