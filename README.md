# GlowStick Downloads

## Current Beta: 1.2.48

Built September 17, 2026. Choose the download for your computer. No GitHub account is required.

| Computer | Download |
| --- | --- |
| Mac with Apple Silicon (M-series) | [Download Apple Silicon beta](https://github.com/lewislux-spec/glowstick-downloads/releases/download/v1.2.48/GlowStick-1.2.48-macOS-Apple-Silicon-2026-09-17.zip) |
| Mac with Intel processor | [Download Intel Mac beta](https://github.com/lewislux-spec/glowstick-downloads/releases/download/v1.2.48/GlowStick-1.2.48-macOS-Intel-2026-09-17.zip) |
| Windows PC (64-bit) | [Download Windows beta](https://github.com/lewislux-spec/glowstick-downloads/releases/download/v1.2.48/GlowStick-1.2.48-Windows-x64-2026-09-17.zip) |

[Beta release notes](https://github.com/lewislux-spec/glowstick-downloads/releases/tag/v1.2.48) | [Update instructions](https://github.com/lewislux-spec/glowstick-downloads/releases/download/v1.2.48/START-HERE.txt) | [SHA256 checksums](https://github.com/lewislux-spec/glowstick-downloads/releases/download/v1.2.48/SHA256SUMS.txt)

This beta includes the BGMC Trading Card Tournament with registration, referee phone connections, match assignments and scoring, compact tournament controls, and two-column audience leaderboards. The External Control widget is removed; Presenter Remote and referee phones remain. Earlier section, editor, mixer, and Mac File/Edit menu fixes are retained.

The current activation flow is unchanged. The unfinished email/code activation system is not included. The separate TypeScript audit cleanup is not complete.

## Updating GlowStick

Quit GlowStick and back up your shows/media before updating. These are packaged applications, not automatic updates or installer wizards.

Mac: extract the ZIP and replace the existing GlowStick.app in Applications. Keep a backup of the old app until the beta is verified.

Windows: extract the complete ZIP and replace the application folder, keeping GlowStick.exe with all its supporting files. Do not replace only the EXE.

Regular GlowStick settings and data stay in their usual location. Local development-preview apps use a separate profile; preview tournament records are not automatically transferred. No real player data, photos, or referee tokens are bundled.

## Beta Testing Limits

All three platform payloads and uploaded file checksums were verified. Both Mac packages passed server startup checks on Apple Silicon, with Intel running under Rosetta. Native Windows playback, physical Intel Macs, DMX equipment, and physical multi-monitor operation still require tester validation. Test before live events.

Mac apps are ad-hoc signed, not Apple-notarized. Windows is not Authenticode-signed. Operating-system trust warnings may appear. Do not disable system-wide security protections.

## Previous Downloads

[Previous non-beta release: 1.2.43](https://github.com/lewislux-spec/glowstick-downloads/releases/tag/v1.2.43)

[All previous releases](https://github.com/lewislux-spec/glowstick-downloads/releases) remain available for rollback.

This is a downloads-only repository. GitHub's automatic Source code archives are not the GlowStick application or installers; use the named platform ZIPs above.
