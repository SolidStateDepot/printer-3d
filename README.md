Solid State Depot aka The Boulder Hackerspace has several reprap 3D printers available for members and for public workshops.  This repository contains resource files for 3D printers at SSD.  Members should start here for slicing configurations (aka "slicer INIs").

## Resources Files
The resource files in this repo. include:
- Slic3r configs
- Marlin firmware
- custom CAD files
- (optional) entire machine CAD files
- general and machine specific documentation

## Directory Structure
The top level of the repository contains general documents for all 3D printers.  Then there are subfolders for each _model_ of 3D printer at SSD.

	/ -- repo root
	|
	/tw-mm-16		:: Terawatt Industries MendelMax 1.6 resource files
	/tw-mm-16/slic3r	:: slic3r files (INIs)
	/tw-mm-16/marlin	:: TW Atlantic fork of Marlin
	|
	/prusa-i2		:: SSD Prusa i2
	/prusa-i2/slic3r	:: slicr files (INIs)
	/prusa-i2/marlin	:: Marlin for Prusa i-2 - w/original SSD mods
	|
	/lulz-ao-100		:: Lulz AO-100 (the AO-100 with the 00str00der)
	/lulz-ao-100/slic3r	:: slicr files (INIs)
	/lulz-ao-100/marlin	:: AO-100 marlin - from Lulzbot
	/lulz-ao-100/hardware	:: CAD files
	/lulz-ao-100/hardware/ssd	:: custom CADs by SSD members
	/lulz-ao-100/hardware/vendor	:: CADs from Lulzbot
	|
	/lulz-ao-100-d2		:: Lulz AO-100-D2 (printed Greg's/Wade's extruder)
	/lulz-ao-100-d2/slic3r	:: slicr files (INIs)
	/lulz-ao-100-d2/marlin	:: AO-100 marlin - from Lulzbot
