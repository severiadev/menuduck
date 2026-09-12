# Changelog

[MenuDuck](README.md) · [Releases](https://github.com/severiadev/menuduck/releases)

## 0.4.4 pre-alpha

- Added a universal Apple silicon and Intel build with a macOS 14.0 minimum.
- Moved Stay Awake and permission-sensitive plugin work into isolated helper processes.
- Added safer plugin package validation, interrupted-update recovery, and normal-quit handling.
- Withheld the new Stay Awake package until signed distribution validation is complete.

## 0.4.3 alpha

- Added offline Pro licenses bound to the current MenuDuck installation.
- Added one-time migration for earlier activations without background license checks.
- Blocked paid-plugin activation, restoration, and automatic runtime events without verified rights.
- Avoided license Keychain access during Free startup and made Keychain failures explicit.
- Preserved the existing Free/Pro split and current-session behavior.

## 0.4.1 alpha

- Added Free and Pro feature access with lossless expiry and renewal handling.
- Added live catalog refresh, two Free plugins, and plugin-interest voting.
- Improved wallpaper safety, recovery, cleanup, and diagnostics.

Changes, known issues, and download checksums are listed with each [release](https://github.com/severiadev/menuduck/releases).
