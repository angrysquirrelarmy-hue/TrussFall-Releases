# TrussFall

Build houses. Badly. Together.

A goofy co-op construction game for up to four players: punch footing holes, stand the posts, nail up the walls, wire it, plumb it, paint it, and get it past the inspector.

## Install (Windows 10 / 11)

1. Open the [latest release](https://github.com/angrysquirrelarmy-hue/TrussFall-Releases/releases/latest).
2. Download **TrussFallLauncher.exe** and run it.
3. Press **INSTALL**. The game downloads into `%LOCALAPPDATA%\TrussFall` (about 400 MB), and TrussFall shortcuts appear on your desktop and in the Start menu.

Windows SmartScreen may warn about the launcher because it isn't code-signed: choose **More info > Run anyway**.

## Install (Steam Deck / Linux, through Proton)

TrussFall is a Windows game that runs under Proton (Steam's compatibility layer).

1. Download **TrussFallLauncher.exe** from the [latest release](https://github.com/angrysquirrelarmy-hue/TrussFall-Releases/releases/latest).
2. In Steam (desktop mode on a Deck): **Games > Add a Non-Steam Game to My Library**, browse to the launcher, add it.
3. Right-click it > **Properties > Compatibility**: tick **Force the use of a specific Steam Play compatibility tool** and pick **Proton Experimental** (or the newest Proton).
4. Start it from Steam and press **INSTALL**. The launcher sees it's under Proton: the **Graphics** option says *Auto (DirectX 11 for Proton)*, and it skips the desktop shortcuts (Steam's library is your shortcut).
5. **PLAY**. Updates work the same as on Windows.

If the game won't start or shows a black screen, pick another **Graphics** option in the launcher (DirectX 11 first, then Vulkan) and press PLAY again.

## Graphics options

The launcher's **Graphics** choice (kept between runs):

| Option | What the game starts with |
|---|---|
| Auto | Windows: the best for your PC. Proton: DirectX 11 |
| DirectX 11 | Most compatible: Windows, Proton and the Steam Deck |
| DirectX 12 | Newer Windows PCs |
| Vulkan | An alternative if the others misbehave |

## Updates

Open TrussFall from its shortcut. The launcher checks GitHub for a newer build every time it opens; **UPDATE** downloads only the files that changed. Then press **PLAY**.

Your saved houses and settings are kept in your AppData (on Proton: inside the game's Proton prefix), so updating or uninstalling never touches them.
