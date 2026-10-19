# Mercury releases

Signed builds of Mercury, Praetori's secure messaging app. Source is private; this repo only serves release artefacts.

- macOS installer: [Mercury.dmg](https://mikesoertsz.github.io/prt-mercury-releases/macos/Mercury.dmg) (latest production release)
- macOS update feed (Sparkle, EdDSA-signed): `https://mikesoertsz.github.io/prt-mercury-releases/macos/appcast.xml`
- iOS update feed: `https://mikesoertsz.github.io/prt-mercury-releases/ios/feed.json` with `feed.json.sig`

Every archive and feed is signed with the Mercury Ed25519 release key. Public key:
`zB+uzZSFPII9QV41kEYLMKpLYz9Foz0W0D0GV9KIeZc=`

Published by CI from `prt-mercury-macos` and `prt-mercury-kit`: version tags `v*` publish production releases and refresh the DMG; pushes to `main` publish development builds on the `development` channel.
