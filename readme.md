# CS2 Autoexec Configuration Files

This repository contains a collection of configuration files for Counter-Strike 2 to enhance your gameplay experience with optimized settings and useful binds.

## Installation

1. Download the files from this repository
2. Place them in your CS2 config folder:
   ```
   [Steam Directory]/steamapps/common/Counter-Strike Global Offensive/game/csgo/cfg/
   ```

## Configuration Files Overview

### autoexec.cfg

This is the main configuration file that will be executed automatically when you start CS2. You need to customize this file to match your personal preferences:

- **Sensitivity Settings**: Adjust mouse sensitivity, zoom sensitivity, and acceleration settings
- **Crosshair Configuration**: Customize your crosshair style, size, color, gap, etc.
- **Audio Settings**: Configure volume levels, and other sound-related options
- **Network Settings**: Optimize rates, interpolation, and other network parameters
- **Keybinds**: Set up your preferred key bindings for weapons, grenades, and actions

To edit the file, open it with any text editor and modify the values according to your preferences. Make sure to save the file after making changes.

## Movement Binds

The `movement/` folder contains specialized jump binds that have been de-subticked for consistent jumps in CS2. These binds help with:
- Uses [Ruby Rain's](https://steamcommunity.com/sharedfiles/filedetails/?id=3313210014) movement config
- Consistent bunny hopping
- Crouch jumps
- Other movement techniques

```
bind key +jb // jumpbug

bind key +cj // crouchjump
bind key +lj // longjump with -forward
bind key +ljleft // longjump with instant +left
bind key +ljright // longjump with instant +right

bind mwheelup +mj // minijump

bind key +j // de-subticked jump
bind mwheeldown j // de-subticked jump
```

The binds are designed to work with CS2's tick system to provide more reliable execution of movement techniques compared to standard binds.

## Configs

The `demo.cfg` file contains useful binds for reviewing demos:

| Key | Function |
|-----|----------|
| ↓ (Down Arrow) | Toggle X-ray (spec_show_xray) on/off |
| → (Right Arrow) | Fast forward (10x speed while held) |
| ← (Left Arrow) | Jump back 960 ticks (approximately 15 seconds) |
| ↑ (Up Arrow) | Pause/unpause demo |

To use these demo binds, load into a demo and execute the config by typing `exec demo` in the console.

### prac.cfg

This configuration file contains specialized binds and settings for practice servers, specifically:

#### Refrag.gg  & MatchZy-based Practice Servers
- Commands for  [Refrag.gg](https://refrag.gg) and [MatchZy](https://github.com/shobhit-pathak/MatchZy) practice servers
- Binds for spawning and manipulating bots
- Binds for rethrowing grenades
- Noclip and other admin commands


The `prac.cfg` file contains useful binds for practice servers:

| Key | Function |
|-----|----------|
| NUMPAD ENTER | Rethrows last grenade  |
| NUMPAD0 | Rethrow HE  |
| NUMPAD1 | Rethrow Flash  |
| NUMPAD2 | Rethrow Smoke |
| NUMPAD3 | Rethrow Molotov/Incendiary |
| NUMPAD4 | Spawns a standing bot at your current location |
| NUMPAD5 | Spawns a crouching bot at your current location |
| NUMPAD6 | Spawns a bot beneath you for boosting |
| NUMPAD 7 | Teleport to the closest spawn point |
| NUMPAD 8 | Teleport to the farthest spawn point |
| NUMPAD PLUS | Create a crouching bot beneath you for boosting  |
| NUMPAD MULTIPLY | Remove all bots from the server |

To use these practice configs, load into a practice server and execute the config by typing `exec prac` in the console.

## Customization

Feel free to modify any of these files to better suit your needs. The configurations are well-commented to help you understand what each setting does.

## Contributing

If you have improvements or additional configurations you'd like to share, please feel free to submit a pull request or open an issue.