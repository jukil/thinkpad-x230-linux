# Installation
The following configuration files enables fan control on boot and on resume from suspend. 

## Boot
Add the section on fan control to your `/etc/rc.local`.

## Resume from suspend
Place `20_fan_control` as `/etc/pm/sleep.d/20_fan_control`.

# Warning
Improper settings of your fan can lead to severe damages of your machine! Use with caution.