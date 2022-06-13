
Note: VMware Fusion 12 supports legacy Sound Blaster 16 (ISA bus based) emulation.
We could use official [SoundBlaster 16 PnP](http://www.nextcomputers.org/forums/index.php?msg=26145) driver.

# README

This package contain the driver for the SoundBlaster16PCI and other cards with an es1371 chip for NeXTSTep/Openstep. It is based on the sources for the linux driver which is also included for reference (es1371.c).

The driver currently only supports playback and I think recording will never be supported since I have no need for that. 

Since this is my first driver I cannot guarantee that it has no effect on other parts of the system but on my system it runs stable.

The driver is programmed to support shared IRQ's but that feature is completely untested although it is enabled in the Default.table.

I try do document the source as good as I can and espacially my changes to the parts of the linux driver I used.


Jens Heise


Legal:
This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License as
published by the Free Software Foundation; either version 2 of
the License, or (at your option) any later version.
