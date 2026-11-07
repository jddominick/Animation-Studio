# Animation Studio

Animation Studio is Maple's animation coworker: the same retro-computer workstation as [Maple Studios](https://github.com/jddominick/Maple-Studios), built for animating pixel characters with Claude Code. Give it motion references and character art, and it builds an editable rig, animates it with you, and exports approved frames that Maple can import into your game.

This repo only hosts the installer and updates. The source is private.

## Install

1. Download **Animation-Studio-Setup-x.y.z.exe** from [Releases](../../releases/latest) and run it. No admin rights needed.
   Windows may show "Windows protected your PC" because the installer isn't code-signed. Click **More info → Run anyway**.
2. Start Animation Studio from the desktop shortcut. On first start it shows its **starter pack**: Godot, Claude Code and Git are installed if missing, plus extras you can untick (ffmpeg, GitHub CLI, ImageMagick, GIMP, TexturePacker). Already have one somewhere unusual? Click **Locate…** next to it.
3. Use **Add project** on an existing rig project's git folder, or **New project** to make a fresh rig workspace in `Documents\Animation Projects`.
4. The first time, Claude Code asks you to sign in with a Claude account (Pro or Max) or paste an Anthropic API key.

Requires Windows 10 or 11, 64-bit.

## Install on a Mac

1. Download **Animation-Studio-x.y.z-mac.dmg** from [Releases](../../releases/latest) (Apple silicon and Intel, macOS 12 or newer).
2. Open the .dmg and drag **Animation Studio** into **Applications**.
3. The first time, macOS blocks it because it isn't signed by an Apple developer. Press **Done**, then **System Settings → Privacy & Security → Open Anyway**. You only do this once.

## Updates

Every time it boots, Animation Studio checks for a new version and asks: **[Y] INSTALL UPDATE** or **[N] LATER**. Your projects, sessions and memory are kept (they live in `%APPDATA%\Animation Studio`). On a Mac, **Y** opens the download page: drag the new app into Applications and choose **Replace**.

## Uninstall

Settings → Apps → Animation Studio → Uninstall. Your data in `%APPDATA%\Animation Studio` stays until you delete it. On a Mac, drag the app to the Trash; data stays in `~/Library/Application Support/Animation Studio`.
