## Requirements

**Section "Screen"**

```Option         "metamodes" "[name] +0+0 {viewportin=<hdpi>x<vdpi>}"```

**Note: You should only use viewportin if you are using fractional scaling**

*PS: the use of force composition pipeline might break fullscreen applications, potentially causing lagging/kernel panic.*

**This option must be present and is essential for operation**



```Option         "ModeValidation" "NoEdidModes"``` 

must be present so that the rules are not overridden.

---
**Section "Monitor"**

```Modeline "name" clock hdisp hsync-start hsync-end htotal vdisp vsync-start vsync-end vtotal [options]``` 
must be present according to what configation you wish for

```Option         "PreferredMode" "[name]"```
must be present
