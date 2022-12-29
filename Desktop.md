# Desktop

```
Windows Registry Editor Version 5.00  

;Alt+Tab Classic

[HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Explorer]
"AltTabSettings"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Explorer]
"AltTabSettings"=dword:00000001

;Desktop icon size - Small
[HKEY_CURRENT_USER\Software\Microsoft\Windows\Shell\Bags\1\Desktop]
"IconSize"=dword:00000020

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\Shell\Bags\1\Desktop]
"IconSize"=dword:00000020

;Disable Foreground lock timeout

[HKEY_CURRENT_USER\Control Panel\Desktop]
"ForegroundLockTimeout"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Control Panel\Desktop]
"ForegroundLockTimeout"=dword:00000000

;Disable Mouse menu delay

[HKEY_CURRENT_USER\Control Panel\Desktop]
"MenuShowDelay"="0"

[HKEY_CURRENT_USER\Software\Classes\Control Panel\Desktop]
"MenuShowDelay"="0"

;Disable Meet Now - Taskbar widget

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\Explorer]
"HideSCAMeetNow"=dword:00000001

;Disable News And Interests - Taskbar widget

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Feeds]
"ShellFeedsTaskbarViewMode"=dword:00000002

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Feeds]
"ShellFeedsTaskbarViewMode"=dword:00000002
