# Installation
* Place `50-touchpad.conf` as `/etc/X11/xorg.conf.d/50-touchpad.conf` to improve the sensitivity of the touchpad. 
* Place `01-touchpad.rules` as `/etc/udev/rules.d/01-touchpad.rules` to disable the touchpad when using an external USB mouse. 
* Place `0000trackpad` as `/etc/pm/sleep.d/0000trackpad` if your touchpad is disabled on resume from suspend.