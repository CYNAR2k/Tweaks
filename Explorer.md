# Explorer

```
Windows Registry Editor Version 5.00  

;Always show all icons and notifications on the taskbar

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer]
"EnableAutoTray"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Explorer]
"EnableAutoTray"=dword:00000000

;Always show more details in a file copy dialog

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\OperationStatusManager]
"EnthusiastMode"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Explorer\OperationStatusManager]
"EnthusiastMode"=dword:00000001

;Command Prompt in directory shit + right-click context menu
;Tutorial: https://www.tenforums.com/tutorials/72024-open-command-window-here-add-windows-10-a.html

[HKEY_CLASSES_ROOT\Directory\shell\cmd2]
@="@shell32.dll,-8506"
"Extended"=""
"Icon"="imageres.dll,-5323"
"NoWorkingDirectory"=""

[HKEY_CLASSES_ROOT\Directory\shell\cmd2\command]
@="cmd.exe /s /k pushd \"%V\""

[HKEY_CLASSES_ROOT\Directory\Background\shell\cmd2]
@="@shell32.dll,-8506"
"Extended"=""
"Icon"="imageres.dll,-5323"
"NoWorkingDirectory"=""

[HKEY_CLASSES_ROOT\Directory\Background\shell\cmd2\command]
@="cmd.exe /s /k pushd \"%V\""

[HKEY_CLASSES_ROOT\Drive\shell\cmd2]
@="@shell32.dll,-8506"
"Extended"=""
"Icon"="imageres.dll,-5323"
"NoWorkingDirectory"=""

[HKEY_CLASSES_ROOT\Drive\shell\cmd2\command]
@="cmd.exe /s /k pushd \"%V\""

[-HKEY_CLASSES_ROOT\LibraryFolder\Background\shell\cmd2]

;Display file size information in folder tips

[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"FolderContentsInfoTip"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"FolderContentsInfoTip"=dword:00000001

;Disable search suggestions

[HKEY_CURRENT_USER\SOFTWARE\Policies\Microsoft\Windows\Explorer]
"DisableSearchBoxSuggestions"=dword:00000001

[HKEY_CURRENT_USER\Software\Classes\Software\Policies\Microsoft\Windows\Explorer]
"DisableSearchBoxSuggestions"=dword:00000001

;Disable Show sync provider notifications
[HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"ShowSyncProviderNotifications"=dword:00000000

[HKEY_CURRENT_USER\Software\Classes\Software\Microsoft\Windows\CurrentVersion\Explorer\Advanced]
"ShowSyncProviderNotifications"=dword:00000000
