# List of Windows Keyboard Shortcuts

This is currently a work in progress.

Welcome to submit PRs adding additional ones, my goal is to have this list eventually include many shortcuts that are not officially documented and understand the history behind them.

Unless noted individually, all the shortcuts support all Windows versions that follow the one they were introduced in.

## Introduced in Windows 1.01 (1985)
- `Alt + Tab` - Switch between open windows (since Windows 3.1 shows a visual switching indicator known as "CoolSwitch"), `Shift` can be added to change the direction
- `Alt + Space` - Open current window context menu, the arrow keys can be used to navigate the menu and enter to select an item
- `Any Letter` - Jump to the next file on the list beginning with the corresponding letter, Windows 95 improved the logic to detect consecutive letters typed rapidly and treat them in letter order
- `Enter` - Either enter focused folder, open focused file if a default program is defined or run focused file
- `Backspace` - Navigate to the parent folder
- `Shift` - Adds to a multiple selection when held while clicking files, this changed on Windows 3.0 (see relavent section)
- `Alt + Any Letter` - Open the menu item beginning with the corresponding letter, `Esc` can be used to close the menu
- `Esc` - Close the current dialog or an opened menu
- `Arrows` - Navigate through an open menu, since Windows 2.01 also navigates through the file list

## Introduced in Windows 2.01 (1987)
- `Alt + F4` - Close current window or shows the "end session" confirmation dialog if the "Desktop (Win95+)"/"Program Manager (Win3+)"/"MS-DOS Executive (Win2)" window is focused
- `Alt + Esc` - Similar to `Alt + Tab` except the windows "switched-to" on every press and not just on release, also no visual indicator is shown, `Shift` can be added to change the direction

## Introduced in Windows 3.0 (1990)
- `Ctrl` - Same as `Shift` on previous versions (and `Shift` now selects a range of files instead of individual ones)
- `Ctrl + Shift + Esc` - Open the "Task List (Win3+)"/"Windows NT Task Manager (NT4)"/"Windows Task Manager (Win2k+)", on the NT line this shortcut appeared Windows NT 4.0 onward, and on the 9x line it disappeared

## Introduced in Windows 3.1 (1992)
- `Alt + Enter` on a selected icon or `Alt + Double Click` on an icon - Open the file "Properties"

## Introduced in Windows NT 3.1 (1993)
- `Ctrl + Alt + Delete` - Open the "Windows NT Security (NT3+)"/"Close Program (Win95+)"/"Windows Security (Win2k,Vista+)"/"Windows Task Manager (WinXP)" dialog (from Vista+ it's fullscreen)

## Introduced in Windows 95 (1995)
- `WinKey` or `Ctrl + Esc` - Open the "Start" menu
- `WinKey + R` - Open the "Run" dialog
- `WinKey + M` - Minimize the current window, `Shift` can be added to undo the minimize
- `WinKey + E` - Open Windows Explorer
- `F8` - When pressed during early boot, opens a menu with advanced boot options (likely inspired by MS-DOS using the `F8` hotkey during boot)

## Introduced in Windows Vista (2007)
- `Ctrl + Alt + Tab` - Similar to `Alt + Tab` but keeps "CoolSwitch" open when the keys are let go and enables arrow navigation until `Enter` is pressed on the desired window

## Introduced in Windows 7 (2009)
- `WinKey + Arrows` - Move the current window according to the arrow direction, `Shift` can be added to move it to a different monitor

## Introduced in Windows 10 (2015)
- `Ctrl + Shift + Alt + WinKey + L` - Open LinkedIn - supported since Windows 10 1903

More coming soon!

### Useful Resources for Emulating Old Windows Versions
- https://copy.sh/v86
- https://www.pcjs.org/
- https://bellard.org/jslinux/
- 86Box
- QEMU
- Hyper-V Manager
