# Install MenuDuck

[MenuDuck](../README.md) · English · [Русский](ALPHA_GUIDE.ru.md) · [Español](ALPHA_GUIDE.es.md) · [简体中文](ALPHA_GUIDE.zh-Hans.md)

Requires **macOS 26+**. This is an alpha without Developer ID signing or Apple notarization. Keep a backup and install only if you trust the source.

## Installation

1. Download the `.dmg` from **Assets** in [Releases](https://github.com/severiadev/menuduck/releases), not the **Source code** archive. Read that release's limitations.
2. Verify SHA-256: type `shasum -a 256 ` in Terminal, drag in the DMG, and press Return. Compare the full result with the checksum received through your private tester contact.
3. Open the DMG, drag MenuDuck to **Applications**, and eject the disk image.
4. Launch MenuDuck. If macOS cannot verify the developer, open **System Settings → Privacy & Security → Open Anyway**, then confirm **Open**.

**Stop if the checksum differs, macOS reports malware or damage, or Open Anyway is unavailable.** Contact the organizer; do not disable Gatekeeper or bypass your Mac's security policy. [Apple's instructions](https://support.apple.com/en-us/102445).

## First launch

- In settings, use **Enter License Key** with your tester key. Keep it private.
- Choose **Update Catalog**, approve the relevant network request, and install **Stay Awake** or **Network Speed**.
- For a **Planned** plugin, **I Need It** records interest; **Voted** confirms it. **Remove Vote** undoes it.

<details>
<summary>Testing, updates, and troubleshooting</summary>

Try hiding icons, shortcuts, display settings, and both plugins. Change one setting at a time; restart the app to check saved preferences. **All (Experimental)** wallpaper mode needs **Dark** wallpaper appearance for notch masking.

Updates are manual: quit MenuDuck and follow the new release's instructions. Do not downgrade without guidance.

If something breaks, undo the last change or quit the app. Quitting may not restore every display change. **Do not delete preferences, wallpaper assets, or recovery data.** Report your app/macOS versions and reproduction steps; remove personal data first.

</details>

[Report a bug](https://github.com/severiadev/menuduck/issues/new/choose) · [Private help](../SUPPORT.md) · [Privacy](../PRIVACY.md)
