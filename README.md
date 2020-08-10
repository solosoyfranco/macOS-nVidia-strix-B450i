<p align="center">
	<img src="https://raw.githubusercontent.com/solosoyfranco/macOS-nVidia-strix-B450i/master/Images/1.png"/>
</p>

<p align="center">
	<img src="https://raw.githubusercontent.com/solosoyfranco/macOS-nVidia-strix-B450i/master/Images/7.png"/>
</p>

I would like to mention that this is the compilation of Willza3's work (https://github.com/willza3) , and reading forums on Reddit, (thanks Jethri_NA)

** After understanding the process of how opencore works, it is important to mention that the version installed by the opencore script is version 17G66, in which they do not have any kind of support for NVIDIA webdrivers. so you need to update.

If you would like to use iCloud services, you will need to [flush a new SMBIOS](https://dortania.github.io/OpenCore-Desktop-Guide/AMD/zen.html#platforminfo). Using the included one is unsafe and can result in a permenantly blacklisted Apple ID - *you have been warned!*

If you can, please consider [donating to AMD OSX.](https://forum.amd-osx.com/index.php?dbtech-donate/drives/amd-os-x.1/donate) Without the team, none of this would be possible.

## System Specs

* **Motherboard:** Asus ROG Strix B450-i Gaming
	* LAN: Intel I211-AT
	* Audio: SupremeFX S1220A
	* Wireless: Realtek 8822BE

* **Processor:** AMD Ryzen 5 3600X
* **Graphics:** # EVGA GeForce GTX 1080 FTW GAMING ACX 3.0, 8GB 

## Reccomended BIOS Settings

**Boot**

* Fast Boot → Disabled
* CSM → Launch CSM → Disabled
* Secure Boot → OS Type → Windows UEFI

> Set OS Type to "Other" if you're having issues booting the macOS installer.

**Advanced**

* USB Configuration → XHCI Hand-off → Enabled

**Using a Ryzen G CPU?**

* Core Performance Boost → Disabled

These settings were tested with BIOS v3004 - use the latest available BIOS to mitigate any issues.

## Issues

**Internal WiFi & Bluetooth is not supported by macOS.**

**Line-in microphones may not work.**


**Fix Photoshop with Ryzen:** [Link](https://www.youtube.com/watch?v=AAmyddHts1s&t=32s)

