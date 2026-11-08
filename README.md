# FreeIPTV — releases

Public release binaries for **FreeIPTV**. The source code lives in the private
repository `ju5eb/free-iptv`; this repo exists only so the app can check for and
download its own updates without exposing the code.

- `version.json` — the latest published version (read by the in-app updater).
- Releases — each tag (e.g. `v0.1.0`) carries the signed APK as an asset.

The app compares its installed `versionCode` against `version.json`; when the
published one is higher it offers a one-tap update. All APKs are signed with the
same release key, so updates install over the top of a previous version.

## Install on a TV (any network)

This link always points to the newest signed APK:

```
https://github.com/ju5eb/free-iptv-releases/releases/latest/download/free-iptv-latest.apk
```

On a Google TV / Android TV, install the **Downloader** app, paste that URL, and
it will download and install it (allow "install unknown apps" once when asked).
You only need to do this once — the app updates itself from then on.
