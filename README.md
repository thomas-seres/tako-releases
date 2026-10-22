# Tako releases

Binaries and update feeds for the Tako apps. No source here.

- DMGs are attached to this repo's Releases, tagged `<app>-vX.Y.Z`.
- Each app's Sparkle feed is served from GitHub Pages:
  - `https://thomas-seres.github.io/tako-releases/calendar/appcast.xml`
  - `https://thomas-seres.github.io/tako-releases/claude/appcast.xml`
  - `https://thomas-seres.github.io/tako-releases/dock/appcast.xml`

Everything here is written by `Scripts/release.sh` in the private
`tako-apps` repo. Don't edit an appcast by hand unless you are pulling a
bad release.

First install: open the DMG, drag the app to Applications, then
right-click → Open once (the apps are self-signed, not notarised).
Later versions arrive through the app itself.
