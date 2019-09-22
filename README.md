# Hackintosh Acer Swift 3 SF314-54G-51ZK Notebook
This is my complete EFI folder to be used for hackintosh on Acer Swift 3 SF314-54G-51ZK Notebook with multibooting:
- macOS Mojave 10.14.6
- Windows 10


<img src="/IMG/Catalina.png?raw=true" alt="macOS Catalina" align="center">

--------------------------------------------------------------------------------------------

### Notebook Specs
<img src="/IMG/SF314-54G.png?raw=true" alt="Acer Aspire E1-472G" align="right">
 
 Acer Swift 3 SF314-54G-51ZK Notebook
 - Model: Acer Swift 3 SF314-54G-51ZK Notebook 2018
 - CPU: Intel Core i5-8250U Quad-core (4 Core™) @ 1.60GHz (8th Gen) 
 - Chipset: Intel® Express Chipset
 - GPU: Intel UHD 620
 - eGPU : Nvidia GeForce® MX150
 - RAM: 8GB DDR4 @ 2133MHz SDRAM (upgradable to 12GB)
 - Storage SSD : SSD Evo 120 GB (GUID Partition Table)
 - Storage HDD: 1TB SATA @ 5400rpm (GUID Partition Table)
 - Audio: Realtek ALC256 HD Audio Controller
 - Wifi : Dual Band Wireless-AC 7265
 - Touchpad : Elan 12C Interface
 - Display Size : 14 Inch 16:9 FHD (1920 x 1080) LED
 - Card Reader : RTS5289
 - USB port : 1 x USB 2.0 + 2 x USB 3.0 + 1 x USB Type-C port: USB 3.1 Gen 1 (up to 5 Gbps)
 - Boot Mode : UEFI
 - Display Output: HDMI 
 - Camera : WebCam 1280 x 720
 - Battery : 4-Cell 3320 mAh 65Wh Lithium-ion Battery
 - BIOS: Ver. 1.14 (Acer).

--------------------------------------------------------------------------------------------

### EFI Contains
 - Clover Bootloader binary, config.plist, drivers for uefi, themes, etc..
 - Patched ACPI Tables (DSDT-SSDT) for Graphics, Audio, Wifi, Ethernet, Battery, etc..
 - 3rd party kexts for working devices under Mac OS X 10.11.6 upto macOS Mojave 10.15.x
 
 --------------------------------------------------------------------------------------------
 
### What Worked
- [x] QE/CI Graphics Of IGPU IHD 4400
- [x] Restart, Sleep and Shutdown
- [x] Wifi
- [x] Internal Speaker, Headphone audio and Internal Mic
- [x] Output Audio ALC282
- [x] Brightness 
- [x] FN + Brightness Button Up / Down
- [x] HDMI Output
- [x] HDMI Audio
- [x] Touchpad
- [x] Keyboard
- [x] All Port USB (USB 3.0 full speed)
- [x] Bluetooh (Need boot to Windows first and reboot to mac)

--------------------------------------------------------------------------------------------

### Not Worked / Bugs
- [ ] NVIDIA GT820M (NVIDIA Optimus is not supported by Hackintosh)
- [ ] Etc

--------------------------------------------------------------------------------------------

### Notes
1. macOS versions used are Retail from Mac App Store, using createinstallmedia for USB Installer
2. Platform Datas (SN, ROM, UUID) used here are ALL FAKE. So, you need to regenerate them.
3. Don't use Patched DSDT-SSDT if you have different BIOS version (need to configure config.plist - ACPI section)
4. To boot with Clover UEFI, you need to configure BIOS

### Credits
[Apple](https://www.apple.com) | [Microsoft](https://www.microsoft.com/en-us/windows) | [Clover](https://sourceforge.net/projects/cloverefiboot) | [Acidanthera](https://github.com/acidanthera) | [Rehabman](https://github.com/RehabMan/Laptop-DSDT-Patch) | [Andres ZeroCross](https://github.com/andreszerocross) | [Badruzeus](https://github.com/badruzeus) | [InsanelyMac](https://www.insanelymac.com/forum), | [Olarila](http://olarila.com/forum) and [OSXLatitude](https://osxlatitude.com/forums) Forum | <b>Other devs</b> who aren't mentioned.
