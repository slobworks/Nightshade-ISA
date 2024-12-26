Starting with v0.8a, the VFC should conform to the official schematics provided by Cirrus Logic.
Version 0.8 had a broken VFC altogether with a missing signal and wacked out assignments, these issues have been fixed starting with 0.8a.

NIGHTSHADE v0.8b - Public Domain Cirrus Logic CL-GD542x Based ISA VGA Card

As it says on the package. This card supports a maximum memory size of 1MB or 2MB, depending on the chip you use, using traditional multiple-CAS FPM 256Kx16 SOJ memory. 70ns or faster is recommended.
Created using KiCAD 8.0.
![front](https://github.com/user-attachments/assets/7c06135f-8955-4014-8534-52e9cfb77c33)
![image](https://github.com/user-attachments/assets/8d1cead2-0d4a-467a-b041-778c5fac8fb5)


Features:
- Four layer PCB with generous stitching vias for maximum possible signal integrity
- Supports 1MB of memory with CL-GD5424, or 2MB with CL-GD5426/5428/5429
- Compatible with the N-well variants of the CL-GD542x, including the CL-GD5424, GD5426, GD5428 and GD5429
- Uses 29C010-compatible flash memory for reduced cost; has options to select one of four 32K banks within the large 128K flash memory if you wish to try multiple video BIOSes
- Features my own hand-drawn artwork on back of board

Released into the Public Domain. Use whatever license floats your boat on your own edits.

As you can see I'm a bit of a neophyte when it comes to this GitHub stuff.
Expect this to change as I become more familiar with the platform.
