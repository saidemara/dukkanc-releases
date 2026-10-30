# Dukkanc Desktop — public distribution

This public repository contains **release artifacts only**. The Dukkanc application source remains private in `saidemara/DukkanAPP`.

## Pending release: Retail 0.1.242 (UNSIGNED)

- Tag: `desktop-v0.1.242`
- Installer: `FlashAI-Retail-Setup-x64.exe` — 64,699,468 bytes; SHA-256 `F77F8ABDB8903E4908265983C0717513DA1807D0E7B041E35A657507363B6106`
- Update ZIP: `Dukkan-Retail-0.1.242-9177DF36-win-x64.zip` — 102,499,503 bytes; SHA-256 `6913AE95277D433B2835048366FDCB8E8821FD4FA0FDB02FCA80D2D56FEFD9E3`
- Update metadata: version `0.1.242`, sourceVersion `0.1.187`, releaseId `9177DF367EA393D1D16B13CDF69DC391F93FA131A6F21E7CE32FD6BF6771F2F0`

The artifacts have only been uploaded to a private source repository release; they are **not yet available for anonymous download**. Upload matching verified binaries as public GitHub Release assets before deploying a public updater feed.

### Release acceptance and safety

- Code signing is deferred: mark downloads **UNSIGNED**.
- Fresh install, upgrade, rollback, and uninstall tests were **NOT EXECUTED** under an explicit owner waiver. Do not claim they passed.
- Check package SHA-256 after upload and test anonymous downloads.
- Once assets are publicly accessible, publish a matching `latest.json` via the approved Netlify workflow and verify `https://download.dukkanc.com/app-updates/latest.json`.
- Never copy private application source, credentials, secrets, or signing keys into this repository.
