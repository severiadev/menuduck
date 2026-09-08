# MenuDuck alpha guide

[Back to MenuDuck](../README.md) · [Русский](ALPHA_GUIDE.ru.md)

No downloadable alpha is published yet. These instructions apply when a tested build appears in [Releases](https://github.com/severiadev/menuduck/releases).

## Before you install

- Use a Mac running macOS 26 or later. Check the release notes for supported hardware and known limitations.
- Keep a current backup. Avoid testing early display and wallpaper features during work you cannot interrupt.
- Get your invitation, tester license key, and expected SHA-256 through the private test organizer's channel.
- Early builds are ad-hoc signed, **not Developer ID signed or notarized by Apple**. Ad-hoc signing does not identify a trusted developer.

## Install a verified build

1. Open the specific alpha release and read its notes. Download the `.dmg` from its **Assets** section. GitHub's **Source code (zip/tar.gz)** archives are not the Mac application.
2. Verify the downloaded file's SHA-256 against the value sent privately by the organizer. In Terminal, type `shasum -a 256 `, drag the DMG into that window, then press Return. This command only reads the file. Compare all 64 hexadecimal characters. A checksum from the same release page alone is not independent proof of authenticity.
3. Open the DMG and drag `menuduck.app` into **Applications**. Eject the disk image.
4. Open the app from Applications once. If macOS blocks it because the developer cannot be verified, continue only if you trust and have verified the file.
5. Open **System Settings → Privacy & Security → Open Anyway**, then confirm **Open** if offered. This creates an exception for this app; keep Gatekeeper enabled.

If the checksum differs, macOS reports malware or damage, or the expected exception is unavailable, **stop and contact the organizer**. Do not disable Gatekeeper, remove quarantine attributes, run an installation bypass script, or override a managed Mac's policy.

Apple explains the supported exception flow in [Safely open apps on your Mac](https://support.apple.com/en-us/102445).

## First launch

1. Open MenuDuck's settings from its menu-bar icon.
2. Find **Enter License Key** in settings and enter the key sent privately. Approve the license request if you choose to activate. Never include the key in a public report.
3. Open the plugin catalog and choose **Update Catalog** when you want the current listing. Accept the relevant network permission if prompted.
4. In the published alpha, test installation of **Stay Awake** and **Network Speed**, the two Free plugins. Other entries should remain Planned. Do not treat a missing download as something to bypass.
5. Test one planned plugin's **I Need It** button. After the vote is recorded, it should show **Voted**. Check that **Remove Vote** works too.

## A ten-minute test

- Hide and reveal menu icons. Try auto-hide and a shortcut you assigned.
- Change one appearance option at a time. Check whether switching it off returns to the expected appearance.
- If relevant, test notch relocation, an external display, and switching Spaces. Note your setup when reporting problems.
- Treat **All (Experimental)** wallpaper mode as experimental; notch masking in that mode currently requires **Dark** wallpaper appearance.
- Start and stop Stay Awake. Check Network Speed during a small download; it is a traffic monitor, not a speed-test service.
- Quit and reopen MenuDuck. Check your saved preferences.
- If something is slow or wrong, record the action, expected result, actual result, and app version/build.

## If something goes wrong

Turn off the last setting you changed if the app still responds. If it does not, quit it or use macOS Force Quit, then contact the organizer with reproduction steps. Quitting is not a promise that every display or wallpaper state will restore automatically.

Do not delete MenuDuck's preferences, wallpaper assets, or recovery data as a troubleshooting shortcut. They may be needed to restore your previous state. Keep private reports out of public issues until you have reviewed and redacted them.

For a new build, read its release notes, quit the running app, and follow that release's update instructions. There is no automatic app updater in this alpha. Do not downgrade without guidance.

[Report a non-sensitive bug](https://github.com/severiadev/menuduck/issues/new/choose) · [Support and private concerns](../SUPPORT.md) · [Data handling](../PRIVACY.md)
