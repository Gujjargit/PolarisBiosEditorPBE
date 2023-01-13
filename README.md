# PolarisBiosEditorPRO 
👉 All in one AMD RX Polaris Bios one click editor Pro 🔝⛏🚀
----------------------------------------------------------------
![image](https://user-images.githubusercontent.com/98729987/212358120-3510ccc3-96c6-439b-9bfc-e8194b6f2fbd.png)

# Buy mining bios with performance timings! - https://mining-bios.eu/
----------------------------
+ Polaris Bios Editor 3 PRO https://mining-bios.eu/product/polaris-bios-editor-3-pro-pbe-3-pro-performance-timings/**
+ Bios mod guide: https://bitcointalk.org/index.php?topic=1954245.0

This is the one and only PBE tweaked by Mattthev!

Polaris Bios Editor 3 Pro updated to the latest version 2020! The original bios mod thread on Bitcointalk started by Mattthev. Free version Polaris Bios Editor 1.7.6 and older classic Polaris Bios Editor 1.6.7.

Pro Performance Timings
+ No memory timings shifting. Pro Performance memory timings
One Click Timing Patcher
+ It recognizes cards, memory types and memory size
All in 1
+ Timings optimized for ETH and XMR or Universal, you can choose which one you want (available only for some memory types)
+ Timings for 4GB or 8GB cards auto choosing the best timings for your card memory size (available only for some memory types)
+ Detect more types of memory and applies suitable timings (compared to PBE 1.6.7 and 1.7.0), new added support for H5GQ4H24AJ
+ Automatic undervolting, overclocking, underclocking (power saving option)
+ Gives the biggest hashrate boost compared to stock, for the 100% performance still need to manually tweak memory clocks and core voltages, editor cannot predict card quality so it’s impossible to automatically use the top values
+ Windows and Linux option, note Linux option only does no undervolting
+ Supports almost all RX cards Polaris and Baffin (RX 460/470/480/560/570/580), (RX550 only few of them, contact me before buy)
+ In next releases more intuitive timings patcher and undervolting






PolarisBiosEditor
==================

If you don't trust the EXE just build on Linux with ```sh build.sh```. Quick and easy.

### Important: You need to disable SecureBoot / Activate CSM in your
### Motherboard UEFI because the modification will make
### the cryptographic signature invalid.

+ Fork from lojkinKot
+ works on linux with mono, executable is build against .net 3.5
+ one click timing feature should be used with care, it maybe not stable for you
+ please build the executable yourself or decompile the existing one if you don't trust

Releases PolarisBiosEditor
---------------------------
### v1.7.6
- Fixed Samsung 2
- Fixed no supported memory found H5GC8H24AJ bug
- Few small changes in code
### v1.7.5
- Added UberMix 3.3
- Few small changes in code
### v1.7.4
- Fixed bug no supported memory found (K4G80325FC)
- Old version bump in properties
### v1.7.3
- Added support for memory Samsung K4G80325FC
- Added new device AMD Radeon RX 580 2048SP - 6FDF
### v1.7.2
- Fixed apply timings for Hynix memory
- Added support for RX590
- Added support for New Hynix memory H5GC8H24AJ
- Added timing for New Hynix H5GC8H24AJ

### v1.7.1
- Updated Elpida Timing

### v1.7.0
- Added New timing for Hynix.
- Added Clock Stretch Amount.
- Added option for choosing timings on hynix Between Universal Hynix timing and Good hynix timing.
- Universal Hynix timing work on: H5GC8H24MJ, H5GQ8H24MJ, H5GQ4H24AJ.

### v1.6.9
- Fixed UI (updated design)
- Fixed and Updated all Timing's
- Added New strap for Micron and Hynix
- Added option for choosing timings on samsung between uber-mix 3.1 and 3.2, and on Micron between Good Micron timing and S Micron timing.
- Added Icon
- Added option for max. Mem. freq. (after one click timing patch button click automatically change max. mem. to 2300 MHz)

### v1.6.8
- Fixed Samsung Uber-Mix strap
- Added support for Hynix H5GQ4H24AJ
- Fixed fan mod option

### v1.6.7
- created solution and project files for ide
- support for device id 0x67ef
- better timings for micron memory
- firmware signature test / firmware signature in ascii
- editing of bios message (experimental)
- online check for new versions
- online display of developer notice

### v1.6.6
- support for rx550 device id 0x699F

### v1.6.5
- support up to 48 entrys in the timings table (more than 2 memory vendors)

### v1.6.4
- elpida timings fixed
- K4G41325FS memory support

### v1.6.3
- timing modification starts now at 1500 instead of 1750
- device id 67FF now also supported

### v1.6.2
- experimental: ubermix timings are now also applied to 4g SAMSUNG vram (K4G41325FC, K4G41325FE)
- timing modification starts now at 1750 instead of 2000

### v1.6.1
- hynix memory H5GC8H24MJ now recognized (same timings as H5GQ8H24MJ)

### v1.6
- window resizes properly now
- memory vendor detection
- one click timing patch (samsung, hynix, elpida, micron)

### v1.5
- added FanControlMode setting
- implemented some timing editor related code (not usable yet)

### v1.4.1
- replaced WPF components with Windows Forms to archive mono compatibility

Contribution from Sebohe:

### Build Dependencies

Ubuntu 16.04.2:

```
sudo apt-get install mono-complete
```

Arch Linux:

```
yaourt -Sy mono48
```
### Building

```
sh build.sh
```

### Executing

Just change your working directory to the PolarisBiosEditor and execute:

```
./run.sh
```

