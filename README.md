# Tiltbit — downloads

**All releases: <https://github.com/Adam-LX/coppertilt-releases/releases>**

The easiest way to play is the launcher. It checks GitHub for the latest
build, verifies the SHA-256 checksum, installs it, and starts the game.
On NixOS it uses `steam-run` when that command is available.

**Stable “latest” links** (asset names do not include a version number):

- Windows launcher (one `.exe`):
  <https://github.com/Adam-LX/coppertilt-releases/releases/latest/download/Tiltbit-Launcher.exe>
- Windows game zip:
  <https://github.com/Adam-LX/coppertilt-releases/releases/latest/download/Tiltbit-windows-x86_64.zip>

| File | System | How to run |
|---|---|---|
| `Tiltbit-Launcher.exe` | Windows 10/11, 64-bit | run the file (SmartScreen: “More info” → “Run anyway”) |
| `Tiltbit-Launcher-windows-x86_64.zip` | Windows 10/11, 64-bit | unzip and run `Tiltbit-Launcher.exe` |
| `Tiltbit-Launcher-linux-x86_64.zip` | Linux, 64-bit | unzip and run `./Tiltbit-Launcher.x86_64` |
| `Tiltbit-windows-x86_64.zip` | Windows 10/11, 64-bit | unzip and run `Tiltbit.exe` |
| `Tiltbit-linux-x86_64.zip` | Linux, 64-bit | unzip and run `./Tiltbit.x86_64` |
| `Tiltbit-terminal-linux-x86_64` | Linux, terminal | `chmod +x Tiltbit-terminal-linux-x86_64 && ./Tiltbit-terminal-linux-x86_64` |
| `Tiltbit-terminal-windows-x86_64.zip` | Windows, terminal | unzip and run `Tiltbit-terminal.bat` (Python is bundled) |
| `coppertilt_tty.pyz` | any system with Python 3 | `python3 coppertilt_tty.pyz` |
| `SHA256SUMS` | — | `sha256sum -c SHA256SUMS` |

The game source is not in a public repository right now — this page is only
the ready-to-run packages.
