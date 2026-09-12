# Changelog

[MenuDuck](README.md) · [Releases](https://github.com/severiadev/menuduck/releases)

## 0.4.4 pre-alpha

This release consolidates the current public pre-alpha feature set:

- Hide and reveal menu-bar icons, including Quick Reveal and keyboard shortcuts.
- Mask the notch, use static-wallpaper tools, and adjust menu-bar positioning and appearance.
- Use Free and Pro modes with profiles, shortcuts, and automation controls.
- Activate Pro offline without background license checks; Free startup avoids Keychain access.
- Refresh the plugin catalog, run the Network Speed plugin, validate plugin packages, and recover interrupted updates.
- Run natively on Apple silicon and Intel with a macOS 14.0 minimum.
- Isolate Stay Awake and permission-sensitive plugin runtimes from the main app.
- Quit normally without leaving managed helper processes behind.

Current limitations:

- The new Stay Awake package is withheld until signed distribution validation is complete.
- Real-system validation on macOS 14 and Intel remains pending.
- The downloadable build is ad-hoc signed and not notarized.

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
