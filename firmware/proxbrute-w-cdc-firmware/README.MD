This is the proxbrute mod by Brad Antoniewicz of Foundstone(https://github.com/brad-anton/proxbrute)<br>
ported to the latest Firmware with the CDC bootloader by Corey Harding of www.legacysecuritygroup.com<br>
<br>
Firmware Dated 9-23-2016<br>
proxmark3 source from Commit: https://github.com/Proxmark/proxmark3/tree/99911e5c7b8f4a2ca870046031e3f362324c0d88<br>
<br>
Proxbrute records a valid LF tag(maybe a guest badge) to Bank1(what I used to call Bank2) and then decrements the hex until you find another valid card(maybe with higher privileges for a different door).<br>
<br>
Flash the bootloader and fullimage elf files.<br>
<br>
A patch is also included in case you want to compile the source yourself.<br>
<br>
Instructions for using this port of the proxbrute mode on the elechouse RDV2 and standard version of the proxmark3 can be found at:<br>
https://legacysecuritygroup.com/index.php/categories/9-rfid/7-proxmark-3-emulating-hid-tags-in-standalone-mode