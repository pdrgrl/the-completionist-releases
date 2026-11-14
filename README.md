# The Completionist: downloads

Installers for **The Completionist**, a filmography-completion tracker. Track every film you've seen against the complete work of the
directors, actors and composers you love.

**[Get the latest installers](../../releases/latest)** for Windows, macOS and Linux. It also runs in any browser, on your phone too.

The source code is private. This repository only holds the finished installers.

## Installing

These builds are **not code-signed yet**, so your system may warn you the first time. That is expected for a free project.

**Windows:** run the `-setup.exe`. If a blue "Windows protected your PC" screen appears, click **More info**, then **Run anyway**.

**macOS:** open the `.dmg` and drag the app into Applications. Open it once, then go to **System Settings, Privacy & Security** and
click **Open Anyway**. Or, in Terminal:

```
xattr -dr com.apple.quarantine /Applications/the-completionist.app
```

**Linux:** for the AppImage, `chmod +x the-completionist_*.AppImage && ./the-completionist_*.AppImage`. For Debian and Ubuntu,
`sudo apt install ./the-completionist_*.deb`.

## Privacy

Your library stays on your computer. An account is optional and only used to publish a profile you choose to share.
