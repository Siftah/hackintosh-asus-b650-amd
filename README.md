## Hardware

| Component        | Model                         			|
| ---------------- | --------------------------------------	|
| Motherboard      | Asus TUF Gaming B650-PLUS        			|
| CPU              | AMD Ryzen 9 7800X3D             			|
| Memory           | G.Skill Trident Z5 DDR5-6400 			|
| GPU              | PowerColor Red Devil RX 6900 XT		|
| WLAN & Bluetooth | None 							|
| Chassis          | Corsair							|
| Storage NVMe     | Samsung 970Plus 2TB				|
## Software

| Component | Model  |
| --------- | ------ |
| OpenCore  | 0.9.1  |
| macOS     | 12.6.5 |
| BIOS      | 1224   |

## Notes
Generate your own serial using GenSMBIOS for MacPro7,1 and add it to config.plist before
macOS has a 15 port limit so I've disabled USB 2.0 ports on the rear IO. Inspect [USBMap.kext](https://github.com/ryanilano/hackintosh-asus-b650ef-amd/blob/master/EFI/OC/Kexts/USBMap.kext/Contents/Info.plist) for labels and notes  
Thank you to everyone at [AMD-OSX](https://amd-osx.com) for being so helpful!
