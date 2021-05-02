# iUFCExport
Display and interact with DCS ([Digital Combat Simulator](https://www.digitalcombatsimulator.com)) plane panels from your iPad

Check [this video](https://www.youtube.com/watch?v=Kx_l9_WEQhs) of iUFCExport in action.

## How to install and configure

1) Install the iPad application from the [Apple AppStore](https://itunes.apple.com/WebObjects/MZStore.woa/wa/viewSoftware?id=1551491580) or use Xcode to build the application from [source](https://github.com/wluc9875/iUFCExport-iPad)

2) Install the Lua script on the PC where you installed DCS. Follow these [instructions](https://github.com/wluc9875/iUFCExport-LuaScript#readme).

3) (Optional) If after installing everything as explained in steps 1 and 2, you can't control DCS from your iPad, or you can't see anything in the UFC displays on your iPad, you may have to do some additional configuration. Follow these [instructions](https://github.com/wluc9875/iUFCExport-iPad#configuration) to configure the iPad application.


## Latest version
1.4 (released May 2, 2021)

## Supported planes and panels

Non-obvious clickable zones are highlighted in red.

### A-10C UFC
![A10C-UFC](./resources/a10c-ufc.png?)
All buttons work, including "Master caution" reset.
"Master caution" light illuminates.

### F-16C ICP
![F16-ICP](./resources/f16-icp.png?)
All buttons, switches and rotating wheels work.
The large wheeels (for example SYM or BRT) work but do not animate.

### F/A-18C UFC
![FA18-UFC](./resources/fa18-ufc.png?)
All buttons, switches and rotating buttons can be used.

All displays are sync'ed with DCS.

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

## Next version
Version 1.5 will add support for the Ka50 PVI-800.
Here's a preview:
![KA50-PVI800](./resources/KA50-PVI.png?)

## Source code
* [Lua script source code](https://github.com/wluc9875/iUFCExport-LuaScript)
* [iPad source code](https://github.com/wluc9875/iUFCExport-iPad)

## [Privacy policy](privacy.md)
