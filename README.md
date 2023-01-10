# TZXDuino-Pico REVISION 1.2 CASSETTE RECORDER EMULATOR IN MINIATURE FORMAT

A small board that can be built into a home computer, that can send .TZX cassette data read from an SD-Card to its cassette input
With one button you can page through the available files (games) and by pressing another button start playback, after first entering CLOAD "" on the Spectrum (or the ZX-81 if you use ZX-81 .TZX Files)

This device can use the (arduino) software of a regular TZXDuino (or compatible device like a CASDuino), but has been simplified and normally doesn't have a display or a full set of buttons (although both can be added if you want). you can also modifiy the software so that it sends its display output to the serial port of the Arduino, so you can see it on the built in terminal software of the Arduino IDE, you can use it to debug the system.

You can read more about it on my Revspace wiki project page here: https://revspace.nl/TZXDuino_pico

This project is open source, so I also uploaded the CAD files (for KiCad 6) so you can create your own version.

This device can also be used (perhaps with modified software) for other projects where you want an Arduino that has an SD-Card interface to read or safe data to.
when ordering PCB's you can enter that it is 37.1mm wide, and 47.2mm high, and is a 2 layer board.
as for component ordering the only specific part is the DM3D-SF push/pull micro SD-card connector, Farnell part # 1764377. The buttons are standard 6x6mm buttons type MCDTS6-2N farnell code "9471707", or mouser code "179-TS026650BK160SCR" or reichelt code "taster 9302"
The same buttons as used in the ZX81+38 keyboard, although it is perhaps preferable to buy a type with a shorter stem lenght. 

This is revision 1,2 It has a 180 degrees rotated card holder, as the card needed to be sticked in from the side with the solderpads, and with the first revision that side was on the side of the resistors, so you could not insert the sd-card!
Also I changed all the (1206 size) resistors to the more common 0805 size
so from jan 10, 2023 the files here are for revision 1,2

I added a .png picture showing a 3D preview of a partially built up TZXDuino-pico, but the only parts missing are the Arduino-nano, and the two buttons. See TZXDuino-pico preview.
