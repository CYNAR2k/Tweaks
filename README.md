# Tweaks

Collection of Windows Tweaks for Performance, Latency, Privacy & Gaming.

I don't take credits for such registrys.

Enjoy.

[Privacy](https://github.com/CYNAR2k/Tweaks/blob/main/Privacy.md)

<details>
<summary><b>Explorer.reg</b></summary>
<br>

Windows Registry Editor Version 5.00  

### ;Alt+Tab Classic
```
[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer]
"AltTabSettings"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Explorer]
"AltTabSettings"=dword:00000001
```
### ;Always show all icons and notifications on the taskbar
```
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer]
"EnableAutoTray"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Explorer]
"EnableAutoTray"=dword:00000000
```
### Always show more details in a file copy dialog
```
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\OperationStatusManager]
"EnthusiastMode"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Explorer\OperationStatusManager]
"EnthusiastMode"=dword:00000001
```
### Command Prompt in directory shit + right-click context menu

###
