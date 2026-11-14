# The Completionist

Track every film you've seen against the **complete work** of the directors, actors and composers you love, and see how close you are to finishing each one.

**[Open the web app](https://the-completionist.pages.dev)** · **[Download for Windows, macOS or Linux](https://the-completionist.pages.dev/download)** · **[Latest release](../../releases/latest)**

## What it does

- **Real completion.** Add a director, composer, actor or film universe and see exactly how much of their filmography you've watched. Films and TV series are counted separately.
- **Bring your history.** Import a Letterboxd or IMDb export. Nothing is added to your library automatically.
- **Progress that feels like progress.** Trophies, levels and a Hall of Mastery for everything you finish.
- **Everywhere.** The same app on Windows, macOS, Linux and in any browser, phone included. Optional free account: sign in with an emailed code (no password) and your library follows you between devices.
- **A public profile, only if you want one.** Share your level, trophies and finished filmographies at a link of your own. You choose what's shown and can make it private or delete your account at any time.

## Install

These installers are **not code-signed yet**, so your system may warn you the first time you open the app. That is expected for a free project. Only download from this repository or the download page.

**Windows.** Run the `-setup.exe`. If a blue "Windows protected your PC" screen appears, click **More info**, then **Run anyway**.

**macOS.** Open the `.dmg` and drag the app into Applications. Open it once, then go to **System Settings, Privacy & Security** and click **Open Anyway**. Or, in Terminal:

```
xattr -dr com.apple.quarantine /Applications/the-completionist.app
```

**Linux.** AppImage (any distribution): `chmod +x the-completionist_*.AppImage && ./the-completionist_*.AppImage`. Debian and Ubuntu: `sudo apt install ./the-completionist_*.deb`.

**Updating.** Download the newer installer and run it. Your library and settings are kept.

## Your data

- Your library stays on your computer. An account is optional.
- You add your own free [TMDb](https://www.themoviedb.org/settings/api) key in Settings; it never leaves your device.
- A public profile is a summary you choose to publish. Your watch history, watch dates and keys are never uploaded.

## Feedback

Found a bug or have an idea? [Open an issue](../../issues). Please say which system you're on and which version (it's in the release name).

## Credits

This product uses the TMDb API but is not endorsed or certified by TMDb. Film data and images are provided by [The Movie Database](https://www.themoviedb.org/).

The source code is private; this repository only holds the finished installers.
