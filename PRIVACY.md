# MenuDuck alpha: data and online actions

[MenuDuck](README.md) · [Support](SUPPORT.md)

This page describes the alpha's data handling, including online requests and server records.

## On your Mac

MenuDuck stores preferences, plugin state, wallpaper assets, recovery information, and diagnostic events locally. Stored license secrets use macOS Keychain. Local diagnostics may contain paths and details about your display or configuration; review them before sharing.

## When you choose an online action

| Action | Data sent or requested | Purpose |
| --- | --- | --- |
| Update Catalog | A request for the published catalog; no app-generated account or installation identifier is attached to this download. | Update plugin listings and package metadata. |
| Install a plugin | A request for the selected package; the download does not attach your license key. | Retrieve the package you selected. |
| I Need It / Remove Vote | Plugin ID when voting, and a random vote token used to record or remove the vote. | Keep one record for that token and support removing it. |
| Enter / Refresh License | License key, requested product context, and a random installation ID. | Check entitlement, expiry, revocation, and the activation limit. |

The vote service stores the token's hash, plugin ID, and creation time. License records include the key's hash, a masked key, the organizer-assigned tester label, entitlement and validity details, and activation records with a hashed installation ID. A hash or random identifier is not the same as guaranteed anonymity. License keys are transmitted to the activation service over HTTPS; they are not stored there as plaintext keys.

The app exposes controls under **Privacy & Permissions** for its online features. Disabling a permission stops the corresponding permitted flow; it does not itself request erasure of records already stored on the server. Use **Remove Vote** for a vote, and contact your test organizer privately for license or data questions.

## Delivery providers and feedback

Requests to GitHub or MenuDuck's hosting infrastructure necessarily expose network information such as your IP address. Providers may process request time, requested URL, and client information for delivery, security, and operations. Do not interpret an offline catalog or locally stored settings as an absence of provider-side network processing.

GitHub issues and anything you attach to them are public. Your GitHub account and posts are also subject to GitHub's own policies. Do not attach license keys, installation or vote identifiers, private wallpaper files, unreviewed diagnostics, or screenshots containing personal data.

## Records and backups

Votes and activation records are held on the service for the alpha's operation. Server backups can contain earlier copies of those records; removing an active record does not erase all backup copies immediately. A fixed remote-backup retention period has not yet been established, so this page does not promise automatic erasure after a particular number of days.

For deletion requests or sensitive questions, use the private channel through which you received your invitation. Do not post the underlying data in a public issue. [How to ask for help](SUPPORT.md).
