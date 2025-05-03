DietPi-ExternalRoot-helper
===============================

A shell script for configuring an external USB drive as root filesystem
on a SBC running DietPi. 

Using dietpi-externalroot-helper
-------------------------------------

On a SBC running DietPi, with a USB-connected storage device you
wish to use for your root filesystem:

    wget https://raw.githubusercontent.com/sysdump/DietPi-ExternalRoot-Helper/refs/heads/master/adafruit-pi-externalroot-helper
    chmod +x adafruit-pi-externalroot-helper
    sudo ./adafruit-pi-externalroot-helper -d /dev/sda

...where `/dev/sda` is the external USB you wish to use for a root filesystem.

Sources and Further Reading
---------------------------

- Modified from [benjamin-nose/Adafruit-Pi-ExternalRoot-Helper](https://github.com/benjamin-nose/Adafruit-Pi-ExternalRoot-Helper)
- Based on [Adafruit-Pi-ExternalRoot-helper](https://github.com/adafruit/Adafruit-Pi-ExternalRoot-Helper)
