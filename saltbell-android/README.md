# Saltbell Android app

WebView wrapper for the Saltbell game (one offline HTML file in `app/src/main/assets/index.html`).
GitHub Actions (`.github/workflows/saltbell-apk.yml`) builds `Saltbell.apk` on every push to a `claude/**` branch.
Signed with the playtest key in `playtest.keystore` so new builds install over old ones and keep saves.
Master copy lives in the Claude project files under `newgame/android/`.
