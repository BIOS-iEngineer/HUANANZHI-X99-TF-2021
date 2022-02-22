# Custom BIOS for Huananzhi X99-TF Gaming (2021 Edition)
### (For Motherboard 2021 Edition, with nuvoTon NCT5567D-B)

### CX99DE30 BIOS for HUANANZHI X99-TF GAMING Motherboard 11/24/2021

![CX99DE29 BIOS for HUANANZHI X99-F8 GAMING Motherboard 11/24/2021](https://raw.githubusercontent.com/BIOS-iEngineer/PNG/main/X99TF2021.jpg)

### Sponsored by: iEngineer

## RELEASES
* ##### Release CX99DE30 November 24, 2021

<div align="left">
    <a href="https://github.com/BIOS-iEngineer/HUANANZHI-X99-TF-2021/releases">
        <img src="https://img.shields.io/github/downloads/BIOS-iEngineer/HUANANZHI-X99-TF-2021/total.svg?color=silver&style=for-the-badge&logo=appveyor" alt="downloads"/>
    </a>
    <a href="https://github.com/BIOS-iEngineer/HUANANZHI-X99-TF-2021/releases/latest">
        <img src="https://img.shields.io/github/release/BIOS-iEngineer/HUANANZHI-X99-TF-2021.svg?color=silver&style=for-the-badge&logo=appveyor" alt="latest version"/>
    </a>
    <a href="https://github.com/BIOS-iEngineer/HUANANZHI-X99-TF-2021/blob/master/License">
        <img src="https://img.shields.io/github/license/BIOS-iEngineer/HUANANZHI-X99-TF-2021.svg?style=for-the-badge&logo=appveyor" alt="license"/>
    </a>
</div>

## CREDITS
**Builder: iEngineer**

## BEFORE YOU PROCEED
* ##### ⚠️ MAIN NOTICE! The manufacturer changed the brand of the BIOS chip to MXIC 25L128 (Macronix) but didn't change the software for this chip, so the update is only possible with the programmer device.
* ##### ⚠️ Check your motherboard revision! This firmware only for motherboards witn nuvoTon NCT5567D-B, 2021 release!
* ##### ⚠️ If you ignored the warning above and flashed your BIOS using firmware update software, please don't create issues, read the instructions carefully and get a programmer device as stated!
* ##### ⚠️ In some cases, it is required to clear CMOS data, for that, you must unplug all power cables to the motherboard and remove the CMOS battery. This is due to the lack of standardization of chinese motherboard manufacturers.

## FIRMWARE FEATURES

* UEFI / CSM
* RAID
* Set FSB to 100 MHz
* ME firmware to v9.1.45.3000 (5MiB)
* EFI/OROM for RSTe SATA(Port 0-3)/sSATA(Port 4-7) to v5.5.5.1005 (_Full I/O speed_)
* 4 channels RDIMM, LRDIMM, UDIMM DDR4 Memory up to 2400MHz & DDR3* up to 2133MHz (Only if CPU supports DDR3)
* CPU microcode
* AMI NVMe firmware
* LAN BOOT ROM
* EFI Realtek UNDI PCIe GbE Family Controller Driver v2.054 (06/30/2020)
* DMI Data

## HOW TO UPDATE THE FIRMWARE
##### ⚠️ If you have factory stock firmware - _YOU MUST USE A PROGRAMMER DEVICE!_ (e.g. EZP-2019 or CH341A)

1. Burn the firmware with a programmer device. (e.g. EZP-2019 or CH341A) [Instruction for CH341A](https://www.miyconst.com/Blog/View/2086/ch341a-minimal-usage-guide-how-to-read-and-write-a-motherboard-bios)
2. Clear CMOS by plugging motherboar power cables and removing the CMOS battery for a few seconds then plug again.
3. After restart load setup defauls by entering the BIOS setting and then **Restore Defaults -> F10 -> Enter**
4. Configure RAM timings and other settings and enjoy!

## DRIVERS DOWNLOAD

[Intel Chipset Driver for Windows 10 x64 Download](https://github.com/BIOS-iEngineer/SZMZ-X99-Dual-Z8/raw/main/Drivers/Windows%2010%20x64/Intel%20Chipset/IntelChipset.zip)

[IRSTe SATA RAID Driver for Windows 10 x64 Download](https://github.com/BIOS-iEngineer/SZMZ-X99-Dual-Z8/raw/main/Drivers/Windows%2010%20x64/IRSTe%20SATA%20C612/IRSTe%20SATA.zip)

[PCIe Realtek GbE Driver for Windows 10 x64 Download](https://github.com/BIOS-iEngineer/SZMZ-X99-Dual-Z8/raw/main/Drivers/Windows%2010%20x64/PCIe%20Realtek%20GbE/PCIe%20Realtek%20GbE.zip)

[Realtek High Definition Audio Drivers 2.81 for Windows 10 x64 Download (Google Search)](https://www.google.com/search?client=firefox-b-d&q=Realtek+High+Definition+Audio+Drivers+2.81+for+Windows+10+x64+Download)

## SCREENSHOTS

![CX99DE30 BIOS for HUANANZHI X99-TF GAMING Motherboard 11/24/2021](https://raw.githubusercontent.com/BIOS-iEngineer/PNG/main/CX99DE29-002.png)
![CX99DE30 BIOS for HUANANZHI X99-TF GAMING Motherboard 11/24/2021](https://raw.githubusercontent.com/BIOS-iEngineer/PNG/main/CX99DE29-003.png)
![CX99DE30 BIOS for HUANANZHI X99-TF GAMING Motherboard 11/24/2021](https://raw.githubusercontent.com/BIOS-iEngineer/PNG/main/CX99DE29-004.png)
![CX99DE30 BIOS for HUANANZHI X99-TF GAMING Motherboard 11/24/2021](https://raw.githubusercontent.com/BIOS-iEngineer/PNG/main/CX99DE29-005.png)
