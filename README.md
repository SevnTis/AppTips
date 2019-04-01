# AppTips
Tips for Application

## Remote Desktop Organizer (RDO)

RDO is still living. Author upgraded version to 1.4.7, now it can support RDP8.

This tip can enable ClearType FontSmoothing automatically.

Choice 1: Add 4 keys to Registry.

    [HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\Control Panel\Desktop]
    
    "FontSmoothing"="2"
    
    "FontSmoothingType"=dword:00000002
    
    "FontSmoothingGamma"=dword:000004b0
    
    "FontSmoothingOrientation"=dword:00000001

Choice 2: Download && Run

[RDO.EnableClearType.reg](https://github.com/SevnTis/AppTips/blob/master/RDO.EnableClearType.reg)

