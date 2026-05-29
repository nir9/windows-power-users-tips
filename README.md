# List of Windows Keyboard Shortcuts (Work in Progress)

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
- `Tab` - Navigate focus through UI elements, `Shift` can be added to change direction
- `Ctrl + A/B` - List files from Floppy A/B, the meaning of `CTRL + A` has completely changed in Win95 (see relevant section)

## Introduced in Windows 2.01 (1987)
- `Alt` or `F10` - Focus the window menu
- `Alt + F4` - Close current window or shows the "end session" confirmation dialog if the "Desktop (Win95+)"/"Program Manager (Win3+)"/"MS-DOS Executive (Win2)" window is focused
- `Alt + Esc` - Similar to `Alt + Tab` except the windows "switched-to" on every press and not just on release, also no visual indicator is shown, `Shift` can be added to change the direction

## Introduced in Windows 3.0 (1990)
- `Ctrl` - Same as `Shift` on previous versions (and `Shift` now selects a range of files instead of individual ones)
- `Ctrl + Shift + Esc` - Open the "Task List (Win3,Win3.1)"/"Windows NT Task Manager (NT4)"/"Windows Task Manager (Win2k+)", on the NT line this shortcut appeared Windows NT 4.0 onward, and on the 9x line it disappeared
- `F5` - Refresh
- `F1` - Help

## Introduced in Windows 3.1 (1992)
- `Alt + Enter` on a selected icon or `Alt + Double Click` on an icon - Open the file "Properties"
- `F6` - Same as `Tab` (including `Shift` support), since WinME acts slightly different than `Tab`; when the menu of the address bar is opened `F6` will always close it and switch to the next UI element while `Tab` navigates through the menu.

## Introduced in Windows NT 3.1 (1993)
- `Ctrl + Alt + Delete` - Open the "Windows NT Security (NT3+)"/"Close Program (Win95+)"/"Windows Security (Win2k,Vista+)"/"Windows Task Manager (WinXP)" dialog (from Vista+ it's fullscreen)

## Introduced in Windows 95 (1995)
- `Win` or `Ctrl + Esc` - Open the "Start" menu
- `Win + R` - Open the "Run" dialog
- `Win + M` - Minimize the current window, `Shift` can be added to undo the minimize
- `Win + E` - Open Windows Explorer
- `Win + Tab` - Cycle focus through windows in the taskbar, meaning changed starting from Vista
- `F4` - Open the Explorer address bar menu, on Win95 and 98 requires pressing `F4` again to start editing the address, from WinME it's editable right away. On the NT line this was supported from NT4 but the address was only editable starting from Win2k. This shortcut is actually more general and applies to other list components for example when pressed within the "Run" dialog it will open a menu with the history of commands.
- `F2` - Rename
- `Context Menu Button` or `Shift + F10` - Open context menu of focused item
- `F8` - When pressed during early boot, opens a menu with advanced boot options (likely inspired by MS-DOS using the `F8` hotkey during boot), on the NT line supported from Win2k
- New meaning for `Ctrl + A` - Select all files in current focused explorer window, meaning was expanded in Win2k (see relevant section)
- `Ctrl` + Dragging a file - Copy the file to the dropped area
- `Ctrl` + `Shift` + Dragging a file - Choose between "Move", "Copy" or "Shortcut" once the file is dropped

## Introduced in Windows 2000 (2000)
- Expanded meaning for `Ctrl + A` - Select all files/text, though this wasn't yet supported on all text fields (for example it was supported on Notepad but not on the text field of the Run dialog). Only starting from Vista it was supported on all text fields

## Introduced in Windows XP (2001)
- `Win + L` - Lock the computer

## Introduced in Windows Vista (2007)
- `Ctrl + Alt + Tab` - Similar to `Alt + Tab` but keeps "CoolSwitch" open when the keys are let go and enables arrow navigation until `Enter` is pressed on the desired window
- `Shift` + Context Menu - Add an option to open a command prompt in the current path (meaning has changed in a subsequent version - TODO: add new meaning)

## Introduced in Windows 7 (2009)
- `Win + Arrows` - Move the current window according to the arrow direction, `Shift` can be added to move it to a different monitor
- `Win + Home` - Restore or minimize all other windows
- `Win + T` - Cycle through taskbar
- `Win + Space` - Peek at the desktop
- `Win + G` - Bring gadgets forward (this was discontinued on the subsequent version)
- `Win + 1-9` - Click the taskbar entry with the position corresponding to the number (e.g. `Win + 3` clicks the third entry)
- `Shift + Click (or Middle-click) on taskbar entry` - Open the program (even if there is already a window)
- `Shift + Right-click on taskbar entry` - Show window operations menu

## Introduced in Windows 10 (2015)
- `Ctrl + Shift + Alt + Win + L` - Open LinkedIn, `Ctrl + Shift + Alt + Win` is what is virtually pressed when using the "Office" key - supported since Windows 10 1903

### Useful Resources for Emulating Old Windows Versions
- https://copy.sh/v86
- https://www.pcjs.org/
- https://bellard.org/jslinux/
- 86Box
- QEMU
- Hyper-V Manager
