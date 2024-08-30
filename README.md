# Custom AutoHotKey script to add Multimedia functionality to keyboards with an extra Windows Key and no FN Key:"

## Overview

This AutoHotKey V2 script is designed for users with an extra Windows key on their keyboard and no FN Key. It provides quick access to applications, media controls, and custom volume buttons using the Right Windows Key (where the FN key usually lies) combined with function keys. This script is particularly useful for users whose keyboards lack dedicated media keys or who want to customize their keyboard shortcuts for enhanced productivity.

## Features

- **Quick Access to Applications:**
  - `Right Windows + F3` → Launch Calculator
  - `Right Windows + F4` → Launch VLC Media Player

- **Media Controls:**
  - `Right Windows + F5` → Move to the Previous Track
  - `Right Windows + F6` → Move to the Next Track
  - `Right Windows + F7` → Play/Pause Media
  - `Right Windows + F8` → Stop Media

- **Custom Volume Controls:**
  - `Right Windows + F9` → Mute/Unmute
  - `Right Windows + F10` → Decrease Volume
  - `Right Windows + F11` → Increase Volume

## Requirements

- **AutoHotKey V2**: This script is written for AutoHotKey version 2. Ensure you have it installed on your Windows system. You can download it from [AutoHotKey's official website](https://www.autohotkey.com/).

## Installation

1. **Install AutoHotKey V2:**
   - Download and install AutoHotKey V2 from the [official website](https://www.autohotkey.com/).

2. **Download the Script:**
   - Clone this repository or download the `Multimedia-Key-Script.ahk` file from the [GitHub repository](https://github.com/sreasgop/AutoHotKey-Multimedia-Support).

4. **Make the Script a Startup Program:**
  - Copy the `Multimedia-Key-Script.ahk` file to Windows’s startup folder. You can type Win, R, then `shell:startup` to open an Explorer in Windows’s startup menu and paste the script file.

3. **Run the Script:**
   - Double-click on the `Multimedia-Key-Script.ahk` file to activate the script. AutoHotKey will run the script in the background, and the custom key bindings will be active.

## Usage

- Press the **Right Windows** key in combination with the specified **Function Keys** to perform the desired action:
  - **F3**: Launch Calculator
  - **F4**: Launch VLC Media Player
  - **F5**: Previous Track
  - **F6**: Next Track
  - **F7**: Play/Pause Media
  - **F8**: Stop Media
  - **F9**: Mute/Unmute Volume
  - **F10**: Decrease Volume
  - **F11**: Increase Volume

## Customization

Feel free to modify the script to suit your needs. You can change the application paths or adjust the key bindings by editing the `Multimedia-Key-Script.ahk` file.

## Support

If you encounter any issues or have questions, please open an issue on the [GitHub repository](https://github.com/sreasgop/AutoHotKey-Multimedia-Support) page.

## License

This script is licensed under the [MIT License](https://opensource.org/licenses/MIT). See the [LICENSE](LICENSE) file for more details.
