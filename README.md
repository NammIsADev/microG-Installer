<p align="center">
  <img src="https://github.com/NammIsADev/microG-Installer/blob/main/logo-microG.png" width="120" alt="microG logo">
</p>

<h1 align="center">microG Installer</h1>
<p align="center">
  <a href="https://github.com/NammIsADev/microG-Installer/releases">
    <img src="https://img.shields.io/github/v/release/NammIsADev/microG-Installer?color=blue&label=version&style=flat-square" alt="release">
  </a>
  <a href="https://github.com/NammIsADev/microG-Installer/stargazers">
    <img src="https://img.shields.io/github/stars/NammIsADev/microG-Installer?style=flat-square" alt="stars">
  </a>
  <a href="https://github.com/NammIsADev/microG-Installer/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/NammIsADev/microG-Installer?style=flat-square" alt="license">
  </a>
</p>

microG Installer is a minimal flashable installer for microG, designed for emui-based huawei devices and other android systems.  

*this flashable installer helps you install microG, GsfProxy, DroidGuard, Aurora Store, FakeGApps (LSPosed), and Companion (Dummy Store) to `/system`*

> [!WARNING]  
> do not flash over existing gms-based roms without removing `gmscore` and `phonesky` first  
> backup all stuff in your device before installing this  
> signature spoofing required for proper microg functionality (requires LSPosed)

---

## features

- supports both sar and non-sar layouts  
- installs to `/system` or `/system_root/system`  
- compatible with twrp 3.1+  
- clean installer logic with permission setting  

---

## usage

1. choose the correct zip from [releases](https://github.com/NammIsADev/microG-Installer/releases):

   - `microG-InstallerX.X-emuiX-hw-signed.zip` → emui-based huawei devices (emui 8/9+)
   - `microG-InstallerX.X-NonSAR-Global-signed.zip` → legacy devices without a/b layout
   - `microG-InstallerX.X-SAR-Global-signed.zip` → newer devices with a/b layout
   - `microG-InstallerX.X-NonSAR-minimal-signed.zip` → legacy devices + minimal package
   - `microG-InstallerX.X-SAR-minimal-signed.zip` → newer devices + minimal package

2. reboot to twrp  
3. flash the zip  
4. wipe cache/dalvik *(optional but recommended)*  
5. reboot and enjoy

**note:** tested on emui 8.0 / 9.1 and android 8.1 / 9 gsi builds

---

## credits

based on the official [microg project](https://github.com/microg)  
