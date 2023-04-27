This version of VCC v2.1.0.7	Oct/2022:


◦ Release of the long awaited "Debugger"
◦ Updated Manual - Bill Pierce

To use the Becker Port, you must insert the Becker Port cart into a slot on the MPI. Just open the Cartridge menu and select an empty MPI slot and select insert. Navigate to the VCC installation folder and select becker.dll.

Once the cart is loaded, you will find configuration options for this interface on the bottom selection of the Cartridge menu: DriveWire Server.  

If you are running DriveWire on the same computer that you run VCC, enter 127.0.0.1 as the server IP address and 65504 as the TCP port (already default).  This will match the settings used by the simple configuration wizard in DW4 if you choose emulator as your platform and leave the other settings at their defaults.  You can also connect to a server on another computer or even at another location by specifying it's IP address and port.

HDBDOS for DW ROMs are included in this installation and can be found in the same directory you installed VCC to.  These can be used in VCC by selecting FD-502 config from the Cartridge menu, and then choosing External ROM Image in the top lefthand Dos Image selection, and then use the Browse button in the lower right to choose the HDBDOS ROM image.  A hard reset is required when changing these options.

HDBDOS Roms:
* hdbdw3bc3 w-offset 5A000.rom - HDBDOS running full 2mhz with offset at $5A000 for multi-partitioned OS9/RSDOS VHDs (default).
* hdbdw3bc3.rom - HDBDOS running full 2mhz with no offsets for using with single partition OS9 or RSDOS VHDs
* hdbdw3bck w-offset 5A000.rom - HDBDOS running at normal speed for games and other time related apps, with offset at $5A000 for multi-partitioned OS9/RSDOS VHDs.
* hdbdw3bc3.rom - HDBDOS running at normal speed for games and other time related apps, with no offsets for using with single partition OS9 or RSDOS VHDs

To get the latest release of VCC,see:
https://github.com/VCCE/VCC/releases
To view the VCC documentation online, click Wiki in the right sidebar.

To use the Becker interface with NitrOS9, download any of the disks with names ending in becker from http://www.nitros9.org/latest/

For technical details for DriveWire4 see:
https://sites.google.com/site/drivewire4/

For technical details of the Becker interface, please see:
http://sourceforge.net/apps/mediawiki/drivewireserver/index.php?title=Becker_port_specification

Enjoy.
Bill P.
