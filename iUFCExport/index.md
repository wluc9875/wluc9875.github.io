# iUFCExport
Display and interact with DCS ([Digital Combat Simulator](https://www.digitalcombatsimulator.com)) plane panels from your iPad

Check [this video review](https://www.youtube.com/watch?v=oVZdlUAiStw) by [The Air Warfare Group](https://www.youtube.com/channel/UCdz6fNb-V-h2iZ_daWNoaTQ) to watch iUFCExport in action.

## How to install and configure

1) Install the iPad application from the [Apple AppStore](https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=1551491580) or use Xcode to build the application from [source](https://github.com/wluc9875/iUFCExport-iPad)

2) Install the Lua script on the PC where you installed DCS. Follow these [instructions](https://github.com/wluc9875/iUFCExport-LuaScript#readme).

3) (Optional) If after installing everything as explained in steps 1 and 2, you can't control DCS from your iPad, or you can't see anything in the UFC displays on your iPad, you may have to do some additional configuration. Follow these [instructions](https://github.com/wluc9875/iUFCExport-iPad#configuration) to configure the iPad application.


## Latest version
1.8 (released on Apple AppStore on September 30, 2023)

Added support for F-15E UFC and for AH-64D Keyboard Unit.


## Supported planes and panels

Non-obvious clickable zones are highlighted in red.

### A-10C UFC
![A10C-UFC](./resources/a10c-ufc.png?)
All buttons work, including "Master caution" reset.
"Master caution" light illuminates.

### A-10C CMS
![A10C-CMS](./resources/A10-CMS.png?)
All buttons and displays work, except the brightness button.

To use the system switches, touch the bottom part to toggle between ON and OFF. Touch the upper part to activate the menu.

### AH-64D Keyboard Unit (only for Pilot)
![AH-64D-KU](./resources/AH-64D-KU.png?)
All buttons and displays work, except the brightness button.
### F-15E UFC (only for Pilot)
![A10C-CMS](./resources/A10-CMS.png?)
All buttons and displays work, except the brightness button.

To use the system switches, touch the bottom part to toggle between ON and OFF. Touch the upper part to activate the menu.

### F-15C ICP
![F-15E-UFC](./resources/F-15E-UFC.png?)
All buttons work, except for the volume rotaries.
The lower and higher half of the volume rotaries are used to decrement / increment the preset radio channels.

### F-16C CMS
![F16-CMS](./resources/F16-CMS.png?)
All buttons and displays work, except the GO/NOGO lights.

### F/A-18C UFC
![FA18-UFC](./resources/fa18-ufc.png?)
All buttons, switches and rotating buttons can be used.

All displays are sync'ed with DCS.

### F/A-18C CMS
![F18-CMS](./resources/F18-CMS.png?)
All buttons work.

Note that the RWR panel is NOT implemented yet!

### AV-8BNA UFC and ODUs
![AV8-UFC](./resources/av8-ufc.png?)
All buttons and rotating buttons can be used, except:
* the 2 volume buttons
* the brightness button

All displays are sync'ed with DCS.

### JF-17 UFCP
![JF17-UFCP](./resources/jf17-ufcp.png?)
All buttons can be used, except the 4 potentiometers at the bottom.

All displays are sync'ed with DCS.

### AJS 37 CK 37 and waypoints panels
![AJS37-CK37](./resources/ajs37-ck37.png?)
All buttons can be used, except for the RENSA button and its guard.

All displays are sync'ed with DCS.

### AJS 37 CMS
![AJS37-CMS](./resources/AJS37-CMS.png?)
All rotators  work.

### Ka 50 PVI 800
![KA50-PVI800](./resources/KA50-PVI.png?)
All buttons can be used, except the brightness.

All displays are sync'ed with DCS.

### Ka 50 CMS
![KA50-CMS](./resources/KA50-CMS.png?)
All buttons and displays work.

### Mirage 2000 C PCN
![M2000-PCN](./resources/M2000-PCN.png?)
All buttons can be used except the brightness button.

All displays are sync'ed with DCS, except the markpoints lights (M91-M93).

### Mirage 2000 C CMS
![M2000-CMS](./resources/M2000-CMS.png?)
All switches work.

## Source code
* [Lua script source code](https://github.com/wluc9875/iUFCExport-LuaScript)
* [iPad source code](https://github.com/wluc9875/iUFCExport-iPad)

## [Privacy policy](privacy.md)
