# ft6336u-linux-overlay
enable "CONFIG_TOUCHSCREEN_GOODIX=m" in the kernel config to use  

## commands
* compile dtbo from dtso: dtc -I dts -O dtb -o ft6336_480x320.dtbo -@ ft6336_480x320.dtso

## you may also be interested in the following projects
* https://github.com/igorkll/syslbuild
* https://github.com/igorkll/orangepi-zero3-st7735-devicetree-overlay
* https://github.com/igorkll/panel-mipi-dbi-firmwares-and-overlays
