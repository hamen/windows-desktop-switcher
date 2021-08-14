### Quick note
This is script is based on [searene/windows-desktop-switcher](https://github.com/searene/windows-desktop-switcher), but I changed the `Win` key with `Alt` because it fits my muscle memory better.

# windows-desktop-switcher
An AutoHotKey script for Windows that lets a user change virtual desktops by pressing Alt + [1,2,3,4].

## Installation

1. Install [AutoHotKey](https://www.autohotkey.com/) 
2. Run the `desktop_switcher.ahk` script (open with AutoHotKey if prompted)
3. Find your [App startup](https://support.microsoft.com/en-us/windows/add-an-app-to-run-automatically-at-startup-in-windows-10-150da165-dcd9-7230-517b-cf3c295d89dd) folder and put the file there so it will run at system startup.

## Hotkeys
        <Alt> + <Num>      - Switches to virtual desktop 1, 2, 3 or 4
        <Win> + A or P     - Switch to virtual desktop on left
        <Win> + S or N     - Switch to virtual desktop on right

To change the key mappings, modify the bottom of the script and reload. Be sure to read about the [symbols AutoHotKey uses](https://autohotkey.com/docs/Hotkeys.htm) for key mapping.

## Other
To see debug messages, download [SysInternals DebugView](https://technet.microsoft.com/en-us/sysinternals/debugview).

Disclaimer: I've only tried this on my machine, and on Windows 10. Use at your own risk.
