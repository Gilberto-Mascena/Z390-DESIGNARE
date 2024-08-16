# *EFI OC Gigabyte Z390 DESIGNARE*


[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Gilberto-Mascena/Z390-DESIGNARE)
![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Gilberto-Mascena/Z390-DESIGNARE/.github%2Fworkflows%2Fbuild.yml)
[![license](https://img.shields.io/github/license/Gilberto-Mascena/Z390-DESIGNARE)](https://github.com/Gilberto-Mascena/Z390-DESIGNARE/blob/main/LICENSE.md)
[![GitHub stars](https://img.shields.io/github/stars/Gilberto-Mascena/Z390-DESIGNARE)](https://github.com/Gilberto-Mascena/Z390-DESIGNARE/stargazers)
[![GitHub issues](https://img.shields.io/github/issues/Gilberto-Mascena/Z390-DESIGNARE)](https://github.com/Gilberto-Mascena/Z390-DESIGNARE/issues)
[![tag](https://img.shields.io/github/v/release/Gilberto-Mascena/Z390-DESIGNARE?include_prereleases)](https://github.com/Gilberto-Mascena/Z390-DESIGNARE/releases)
![release](https://img.shields.io/github/release-date/Gilberto-Mascena/Z390-DESIGNARE)
![size](https://img.shields.io/github/repo-size/Gilberto-Mascena/Z390-DESIGNARE)

---

## *Operating systems*

<img align="right" src="./img/banner.png" alt="photo Z390-DESIGNARE" width="330">

<div>
<img src="./img/macos-catalina-icon.png" alt="" width="55">
<img src="./img/macos-big-sur-icon.png" alt="" width="55">
<img src="./img/macos-monterey-icon.png" alt="" width="55">
<img src="./img/macos-ventura-icon.png" alt="" width="55">
<img src="./img/macos-sonoma-icon.png" alt="" width="55">

</div>

---

_**Setup**_

- _**Motherboard**_
  - [*Gigabyte Z390 DESIGNARE*](https://www.gigabyte.com/br/Motherboard/Z390-DESIGNARE-rev-10#kf)
- _**Power supply**_
  - *CORSAIR - 650W*
- _**CPU**_
  - *Core I7 9700K*
- _**Water Cooler**_
  - *CORSAIR 120*
- _**NVME M.2**_
  - *XPG GAMMIX S41 512GB* 
- _**GPU**_
  - *MSI RX 580 GAMING X 8G*
- _**Memory**_
  - *G.SKILL 2x16GB 32GB*
- _**Network**_
  - *Intel I219-V / I211* 
- _**WI-FI / Bluetooth**_
  - *AC9560*

---

<a name="ancora"></a>
## Topic navigation
- [*What works*](#ancora1)
- [*Screenshot*](#ancora2)
- [*Kexts used, (all Releases)*](#ancora3)
- [*Recommended tools*](#ancora4)
- [*Intel BIOS Settings*](#ancora5)
- [*Thanks*](#ancora6)
- [*License* ](#ancora7)

---

<a id="ancora1"></a>
## *What works*

- [x] *Sound*
- [x] *Network (both network ports)*
- [x] *WI-FI*
- [x] *Bluetooth*
- [x] *USB*
- [x] *Thunderbolt (No hot/swap support, testing will be done)*
- [x] *Sleep*

[Top](#ancora)

---

<a id="ancora2"></a>
## *Screenshot*

## *About this mac* 
![about this mac](./img/about.jpeg)
## *BIOS version*
![Bios](./img/Bios.jpeg)
## *USB port mapping*
![USB Mapping](./img/USBPorts.jpeg)

[Top](#ancora)

---

<a id="ancora3"></a>
## *Kexts used, (all Releases)*

- *[`WhateverGreen.kext`](https://github.com/acidanthera/WhateverGreen)*
- *[`Lilu.kext`](https://github.com/acidanthera/Lilu)*
- *[`VirtualSMC`](https://github.com/acidanthera/VirtualSMC), only: `VirtualSMC.kext`, `SMCProcessor.kext` and `SMCSuperIO.kext`*
- *[`CpuTscSync.kext`](https://github.com/acidanthera/CpuTscSync)*
- *[`AppleALC.kext`](https://github.com/acidanthera/AppleALC)*
- *`USBMap.kext`*
- *[`AirportItlwm.kext`](https://github.com/OpenIntelWireless/itlwm/releases)*
- *[`BlueToolFixup.kext`](https://github.com/acidanthera/BrcmPatchRAM/releases)*
- *[`IntelBlueToothFirmware.kext`](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases)*
- *[`IntelBTPatcher.kext`](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases)*
- *[`IntelMausi.kext`](https://github.com/acidanthera/IntelMausi)*
- *[`SmallTreeIntel82576.kext`](https://github.com/khronokernel/SmallTree-I211-AT-patch/releases)*

[Top](#ancora)

---

<a id="ancora4"></a>
## *Recommended tools*

*  Recommendation 1
  * *Use [`GenSMBIOS`](https://github.com/corpnewt/GenSMBIOS), to generate new serials for your SMBIOS in order to avoid conflicts with iServices.*
* Recommendation 2
  * *Use [`ProperTree`](https://github.com/corpnewt/ProperTree), to edit your config.plist.*     
* Recommendation 3
   * *Use [`USBMap`](https://github.com/corpnewt/USBMap), to map your USB ports, starting from OC 0.9.3, they can be mapped with XHCIPortLimit enabled in config.plist + [`USBInjectAll`](https://github.com/Sniki/OS-X-USB-Inject-All/releases).*
* Recommendation 4
  * *Extract your DSDT from windows.*
  * *Use [`SSDTTime`](https://github.com/corpnewt/SSDTTime), to generate your SSDT patches.*    
* Recommendation 5
  * *Use [`MaciASL`](https://github.com/acidanthera/MaciASL), to compile your SSDT patches on mac.*

[Top](#ancora)

---

<a id="ancora5"></a>
## *Intel BIOS Settings*

- [*OpenCore Install Guide*](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#intel-bios-settings)

[Top](#ancora)

---

<a id="ancora6"></a>
## *Thanks*

- [*Acidanthera Team*](https://github.com/acidanthera)
- [*CorpNewt*](https://github.com/corpnewt)
- [*CrisHotpatch*](https://t.me/crishotpatch)
- [*Dortania*](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#starting-point)
- [*Dicas do Mateus*](https://www.youtube.com/c/DicasdoMateus)
- [*Gabriel Luchina*](https://www.youtube.com/c/gabrielluchina)
- *And others*

[Top](#ancora)

---

<a id="ancora7"></a>
## *License* 

*The* [*MIT License*](LICENSE.md) (*MIT*)

*Copyright :copyright: 2023* 

[Top](#ancora)

---