<p align="center">
  <img src="assets/icon.png" width="112" height="112" alt="MenuDuck app icon">
</p>

<h1 align="center">MenuDuck</h1>

<p align="center"><strong>Make room in your menu bar.</strong><br>
A native macOS utility for menu icons, the notch, and small everyday tools.</p>

<p align="center">macOS 26+ · Invited alpha in preparation</p>

<p align="center">
  <a href="https://github.com/severiadev/menuduck/releases">Releases</a> ·
  <a href="docs/ALPHA_GUIDE.md">Alpha guide</a> ·
  <a href="CHANGELOG.md">Changelog</a> ·
  <a href="SUPPORT.md">Feedback</a> ·
  <a href="README.ru.md">Русский</a>
</p>

---

## Less clutter. More control.

**Keep the icons you need close.** Organize menu-bar icons into visible and hidden sections. Reveal them when needed, use auto-hide, and assign global shortcuts.

**Choose how the top of your screen looks.** Mask the notch with a black menu-bar background, adjust screen-corner styling, or move the menu bar below the camera area on supported displays. Masking the notch changes its appearance; relocation is the separate option for making room for icons.

**Add small tools as you need them.** An in-app catalog brings optional plugins into the same menu-bar experience. Browse the bundled catalog offline and choose when to refresh it online.

## Try the alpha

**No downloadable build has been published yet.** The first build is being prepared for invited testers. This repository will host the DMG, SHA-256 checksum, installation instructions, and release notes when it is ready.

The alpha targets macOS 26 or later on Apple silicon and Intel Macs. Check each release's notes for the exact tested configurations and limitations.

**Before installing:** early builds will not have a Developer ID signature or Apple notarization. macOS may block first launch. Only proceed if you trust the source and can verify the file through your private tester contact. [Read the installation guide](docs/ALPHA_GUIDE.md).

[Browse releases](https://github.com/severiadev/menuduck/releases) — the release list is intentionally empty until a build passes its release checks.

## Two plugins in the first-alpha scope

| Plugin | What it does |
| --- | --- |
| **Stay Awake** | Keeps your Mac awake while you need it. Closed-lid operation is not a supported alpha promise. |
| **Network Speed** | Shows current upload and download rates, with session traffic totals. |

Both are designated **Free** in the alpha catalog. Their download and installation checks are part of the first release preparation; packages are not published yet.

Other catalog entries remain **Planned**, not installable. Use **I Need It** to express interest once the alpha is live. A recorded vote shows **Voted**, and you can remove it later. Votes help set priorities; they are not purchases or delivery-date promises.

## Know what you are testing

- **Early software.** This is an invited alpha, not a stable release. Keep a current backup of your Mac.
- **Display-dependent behavior.** Notch relocation, multiple displays, Spaces, and wallpaper effects need testing on different setups. Live and complex wallpaper support is experimental.
- **Manual app updates.** Use GitHub Releases for new builds. Updating the plugin catalog is a separate action, not an app updater.
- **Individual tester keys.** Use the key provided privately by the test organizer. Never post it in an issue or screenshot.

See the [alpha guide](docs/ALPHA_GUIDE.md) for a short testing checklist and safe recovery steps.

## Privacy, in plain language

Preferences, wallpaper assets, and local diagnostics stay on your Mac. Catalog refreshes, plugin downloads, votes, and license activation have different online purposes and permissions. A vote uses a random token; license activation uses your key and a random installation ID. These identifiers are not a claim of complete anonymity.

Read [what each action sends](PRIVACY.md). Before sharing diagnostics or screenshots, remove personal information.

## Help shape MenuDuck

[Report a bug or suggest an improvement](https://github.com/severiadev/menuduck/issues/new/choose). English and Russian reports are welcome. Include your app version, macOS version, and a short way to reproduce the problem.

For license problems, private data, or security concerns, use your private tester contact instead of public issues. [Feedback and support guide](SUPPORT.md).

---

This is MenuDuck's public product and distribution repository. It contains documentation and release materials, not the application's source code. The app is not being offered as open-source software through this repository.
