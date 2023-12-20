# Apex Legends Configurations Repository

Welcome to the Apex Legends Configurations Repository! This Git repository is dedicated to storing configuration files that can be used to customize and optimize your Apex Legends gaming experience. Whether you're looking to tweak graphics settings, key bindings, or other game parameters, you'll find useful configurations here.

## Table of Contents

- Getting Started
- How to Use
- TODO
- Credits

### Getting Started

To get started, clone this repository to your local machine:
`git clone https://github.com/drxxmy/apex-configs.git`

### How to Use

#### Windows

1. Open downloaded folder.
2. Choose your desired configs.
3. Place `autoexec.cfg` to your games cfg directory. For example: `C:\Program Files (x86)\Steam\steamapps\common\Apex Legends\cfg`
4. Place `settings.cfg` and `videoconfig.txt` to `%USERPROFILE%\Saved Games\Respawn\Apex\local`
5. Add launch options to your game by right-clicking on the game in Steam and going to "Properties".
6. Enjoy boosted fps and comfortable game settings!

#### Linux

1. Clone git repo to your desired directory.
2. Change directory with a `cd apex-configs`
3. Choose your desired configs.
4. Place `autoexec.cfg` to your games cfg directory. For example: `/home/$USER/.local/share/Steam/steamapps/common/Apex Legends/cfg/`
5. Place `settings.cfg` and `videoconfig.txt` to `/home/$USER/.steam/steam/steamapps/compatdata/1172470/pfx/drive_c/users/steamuser/Saved Games/Respawn/Apex/local/`
6. Add launch options to your game by right-clicking on the game in Steam and going to "Properties".
7. Enjoy boosted fps and comfortable game settings!

#### Launch options

Windows and Linux: `-dev -novid -high +exec autoexec.cfg`
Linux with gamemoderun and strangle FPS lock: `strangle 141 gamemoderun %command% -dev -novid -high +exec autoexec.cfg`
Dependencies:
- https://gitlab.com/torkel104/libstrangle
- https://github.com/FeralInteractive/gamemode

### TODO

- Automate config installation

### Credits

The initial autoexec was taken from this website `https://www.riotbits.com/apex-legend-how-to-get-120-fov-improve-fps-overall-14864/`, all credits go to their respective creators.
