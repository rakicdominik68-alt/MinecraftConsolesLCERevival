<img width="1920" height="669" alt="image" src="https://github.com/user-attachments/assets/1a29316a-dc58-4e43-9404-74b12b924012" />

# MinecraftConsoles (Legacy Console Edition)
Discord https://discord.gg/DjeeGtvX

This project is based on source code of Minecraft Legacy Console Edition v1.6.0560.0 (TU19) with some fixes and improvements applied.

The current goal of MinecraftConsoles is to be a multi-platform base for further development, such as modding, backports, and anything else LCE. On top of that, we're working to make this a quality experience on Desktop with or without a controller while (long-term) retaining console support.

See our our Contributor's Guide for more information on the goals of this project.
Download
Client

Windows users can download our Nightly Build! Simply download the .zip file and extract it to a folder where you'd like to keep the game. You can set your username in username.txt (you'll have to make this file)
Server

If you're looking for Dedicated Server software, download its Nightly Build here. Similar instructions to the client more or less, though see further down in this README for more info on that.

# Platform Support
- Windows: Supported for building and running the project
- macOS / Linux: The Windows nightly build will run through Wine or CrossOver based on community reports, but this is unofficial and not currently tested by the maintainers when pushing updates
- Android: VIA x86 EMULATORS (like GameNative) ONLY! The Windows nightly build does run but has stability / frametime pacing issues frequently reported
- iOS: No current support
- All Consoles: Console support remains in the code, but maintainers are not currently verifying console functionality / porting UI Changes to the console builds at this time.

# Features
- Dedicated Server Software (Minecraft.Server.exe)
- Fixed compilation and execution in both Debug and Release mode on Windows using Visual Studio 2022
- Added support for keyboard and mouse input
- Added fullscreen mode support (toggle using F11)
- (WIP) Disabled V-Sync for better performance
- Added a high-resolution timer path on Windows for smoother high-FPS gameplay timing
- Device's screen resolution will be used as the game resolution instead of using a fixed resolution (1920x1080)
- LAN Multiplayer & Discovery
- Added persistent username system via username.txt
- Decoupled usernames and UIDs to allow username changes
- Fixed various security issues present in the original codebase
- Splitscreen Multiplayer support (connect to dedicated servers, etc)
- In-game server management (Add Server button, etc)
