# FreeIPTV — releases

Public release binaries for **FreeIPTV**. The source code lives in the private
repository `ju5eb/free-iptv`; this repo exists only so the app can check for and
download its own updates without exposing the code.

- `version.json` — the latest published version (read by the in-app updater).
- Releases — each tag (e.g. `v0.1.0`) carries the signed APK as an asset.

The app compares its installed `versionCode` against `version.json`; when the
published one is higher it offers a one-tap update. All APKs are signed with the
same release key, so updates install over the top of a previous version.
