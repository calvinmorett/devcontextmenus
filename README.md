# Dev Context Menus
Different Context Menu Shortcuts for Developers

`opencmdprompthere.reg`
- this regedit will add a context menu shortcut to open cmd prompt in the current folder.

`Windows Registry Editor Version 5.00

[HKEY_CLASSES_ROOT\Directory\Background\shell\Open Commad Prompt Here]
"Icon"="%systemroot%\\system32\\pifmgr.dll,-38"

[HKEY_CLASSES_ROOT\Directory\Background\shell\Open Commad Prompt Here\command]
@="cmd.exe /s /k \"pushd \"\"%V\"\" & title %V\""
`
