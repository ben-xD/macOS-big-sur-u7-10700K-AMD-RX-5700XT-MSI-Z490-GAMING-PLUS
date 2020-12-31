# Introduction

Use OpenCore to install macOS Big Sur.
> They said we shouldn't use XFX graphics cards. They said we might not be able to use MSI's motherboards. **You can.**

## Warning
**Don't copy this EFI**, but compare it with yours. I suggest doing it the [long way](https://dortania.github.io/Getting-Started-With-ACPI/ssdt-methods/ssdt-long.html) in the Dortania guide: compile your own ACPI files. I first chose the easy way (prebult SSDTs), and it didn't work after days of effort. Doing it the "long way" took a few hours, and it worked great.

## Specs and prices:

**Total:** £1,337

- £342: Intel Core i7-10700K Unlocked Processor
- £383: XFX RX 5700 XT Triple Dissipation 8GB
- £155: MSI MPG Z490 GAMING PLUS ATX Motherboard for Intel LGA1200 CPUs
- £110: Corsair Vengeance Pro RGB 32GB DDR4 3200MHz CL16 2x16GB Dual Channel Memory Kit
- £85: Crucial P1 1 TB CT1000P1SSD8 Internal Solid State Drive
- £30: Master 212 Black Edition
- £69: NZXT H510 - Compact ATX Mid-Tower PC Gaming Case
- £60: Fenvi T919 (mac compatible) wifi & bluetooth card
- £80: CORSAIR TX650M Semi-Modular ATX PSU - 650 W

## Screenshot

![macOS "about this mac" page](screenshot.png)

## Warning about the BIOS menu
The MSI BIOS menu is a little hard to wrap your head around. To enable/ disable some of the bios options suggested by OpenCore (e.g. enable virtualization/ hyperthreading, disable VT-d or CFG Lock, you need to go into the **OC (overclocking) option**, and then look under 2 sub-sections, Advanced CPU configuration (near the top of the list) and another option near the bottom of the list. I suggest generally spending a significant amount of time playing with your BIOS menu.

## Special thanks to:

- Anmol92verma and his repo: https://github.com/Anmol92verma/z490_opencore_msi
- Laura Müller for writing [LucyRTL8125Ethernet](https://github.com/Mieze/LucyRTL8125Ethernet)
- OpenCore contributors
