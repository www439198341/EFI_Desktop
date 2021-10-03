# EFI_Desktop

## Computer Infomation
|Name|Model|
|----|----|
|CPU|Intel Xeon E3-1230 v3, 3.30GHz|
|MotherBoard|MSI B85-G41 PC Mate(MS-7850), Haswell|
|Memory|Kingston 8 GB 1600 MHz DDR3|
|Graphics|NVIDIA GetForce GTX 760(2GB/NVIDIA)|
|HardDisk|ShineDisk M667 120GB SATA-III(for Windows)<br>WDC WD1503FYYS-02W0B0 1.5TB SATA 2.6(for data)<br>ShineDisk M746 128G SATA-III(for Mac)|
|Audio|Realtek ALC887|
|Network|Realtek RTL8168/8111/8112 Gigabit Ethernet Controller|

## EFI Structure

+ OpenCore 0.7.3
+ ACPI
  + SSDT-EC-DESKTOP.aml
  + SSDT-PLUG-DRTNIA.aml
+ Kexts
  + AppleALC.kext
  + Lilu.kext
  + RealttekRTL8111.kext
  + USBInjectAll.kext
  + VirtualSMC.kext
  + WhateverGreen.kext
+ Drivers
  + OpenCanopy.efi
  + OpenHfsPlus.efi
  + OpenLinuxBoot.efi
  + OpenPartitionDxe.efi
  + OpenRuntime.efi
+ Tools
  + OpenShell.efi

## Known issues

  + Sleep wake failure
  + Sounds on boot doesn't work(It worked, but now I forgot how to config it)
