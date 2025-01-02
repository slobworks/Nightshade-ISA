NIGHTSHADE v0.8c2 - Public Domain Cirrus Logic CL-GD542x Based ISA VGA Card

As it says on the package. This card supports a maximum memory size of 1MB or 2MB, depending on the chip you use, using traditional multiple-CAS FPM 256Kx16 SOJ memory. 70ns or faster is recommended.
Created using KiCAD 8.0.
![front](https://github.com/user-attachments/assets/613e05ff-f9b9-49f3-b59c-2397743db88d)
![back](https://github.com/user-attachments/assets/518112d4-c9e9-4acd-aab4-bc4d20442333)
Features:
- Four layer PCB with generous stitching vias for maximum possible signal integrity
- Optional dedicated regulator for analog DAC power for further improved picture quality
- Supports 1MB of memory with CL-GD5424, or 2MB with CL-GD5426/5428/5429
- Compatible with the N-well variants of the CL-GD542x, including the CL-GD5424, GD5426, GD5428 and GD5429
- Uses 29C010-compatible flash memory for reduced cost; has options to select one of four 32K banks within the large 128K flash memory if you wish to try multiple video BIOSes
- Features my own hand-drawn artwork on back of board

Release History:
- 0.8a: Fixed VESA Feature Connector pinout, now conforms to Cirrus datasheet
- 0.8b: Resolved a number of issues related to VGA output quality (no more wavy interference onscreen!), and reduced the parts count a bit. Fewer parts means less $$ spent, and less breathing of solder fumes.
- 0.8b2: Changed LM334SM to the _much_ cheaper LM334M.
- 0.8c: Pretty heavy tweak-up of both layout, ground pours, and placement of 75 ohm termination resistors following feedback from TmEE, Jorge and others. Thanks everyone who spoke up to help.
Also re-added DPAK LF50 regulator for the RAMDAC, and yes, it is optional if you want to pinch pennies on the dollar - just remember to only populate R22 if you're **not** using a regulator. If you're installing the regulator, leave R22 **OPEN**.
- 0.8c1: Changed ROM footprint to an SMD PLCC-32 socket, and had to re-space stuff around it to make it fit. This looks like it ought to work: https://www.digikey.com/en/products/detail/amphenol-cs-fci/69802-132LF/2023294
- 0.8c2: Moved the LDO and related junk to the front of the board to help minimize the potential for damage. Hopefully things don't get too hot, where it is.

Other people's stuff I've used:
- PLCC-32 footprint from KiCAD (SchrodingersGat ?): https://github.com/KiCad/Housings_LCC.pretty/blob/master/PLCC-32_SMD-Socket.kicad_mod

Released into the Public Domain. Use whatever license floats your boat on your own edits.

As you can see I'm a bit of a neophyte when it comes to this GitHub stuff.
Expect this to change as I become more familiar with the platform.
