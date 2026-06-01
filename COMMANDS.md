# Useful Windows Commands

## Introduced in Windows NT 3.51 (1995)
- The `/d` flag in `cd` - Enables switching the current drive and the current directory at the same time, for example you are now on `C:\Windows` and after running `cd /d D:\setup` your command prompt will switch to `D:\setup`

## Introduced in Windows XP (2001)
> Note: The `shutdown` command was first built-in with XP but appeared in a resource kit that was commonly installed on earlier NT versions
- The `/FO` (format) flag in `tasklist` - If the list of currently running processes is long it may be more comfortable to see them in a "list" rather than the default "table". You can use `tasklist /fo list` to view as a list
- `shutdown` - Shutdown the system immediately by passing `/s /t 0`, log off by passing `/l`
