U-Boot for MikroTik RB750Gr3
============================

# Features
* Firmware flash from HTTP, TFTP and serial
* U-Boot flash from TFTP

# Notes/Warnings
* Initial flash must be done with an SPI programmer as factory bootloader (RouterBOOT) is locked down
* Bad flash subsequently could brick router and require SPI programmer flashing again

# Credits
Forked from [pinney/MT7621-u-boot-mod@5688587](https://github.com/pinney/MT7621-u-boot-mod/commit/5688587b9031073d95c8af5e878cf6ce8f3c0962)
