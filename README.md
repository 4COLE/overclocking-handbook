# Overclocking (CML, although some knowledge can be applied to other architectures)

## Why OC?

- Consistent performance compared to algorthim based "auto oc" & "turbo boost"
- Games (especially open world) you can see a huge boost in lows https://kingfaris.co.uk/blog/intel-ram-oc-impact/
- Responsive input (Input Delay/Lag)

## Steps

## Pre-OC Setup

- High quaility PSU and power conditioner (optional)
- Use either a high quality thermal paste (Noctua NH-2) or liquid metal (Thermal Grizzly Conductonaut) with either a direct die frame or copper ihs
- Use a 360mm **prefered** or 280mm AIO or custom loop (make sure the block is copper)
- Use Arctic P12/P14s for your ram sticks with the heatsinks removed or swapped for copper, this is required as faster ram has tighter temperature requirements (<40c)
- One 4GB or larger usb for live linux/windows pe & bios flashing (**NEVER overclock on your os if you care about the data on it**)
- A disgusting amount of time (make sure ur doing nothing on a weekend)

###### Required Software 

- https://medicatusb.com/ (Windows PE + extra + ventoy)
- https://www.hirensbootcd.org/ (Windows PE)
- SWAP LINK FOR UEFI ONE (AutoGSAT | IMC+RAM)
- https://www.mersenne.org/download/ (Prime95 | CPU+IMC+RAM stress)
- https://www.techpowerup.com/download/linpack-xtreme/ (Linpack Xtreme | CPU+IMC+RAM stress)
- https://github.com/BoringBoredom/Linpack-Extended (Linpack Extended | CPU+IMC+RAM stress)
- Linpack Xtreme & Extended are slightly different as they use different versions of the binary (Xtreme is older) either is a good option for testing its mostly preference
- https://www.overclock.net/threads/memory-testing-with-testmem5-tm5-with-custom-configs.1751608/ (TM5 | IMC+RAM stress)
- https://www.ocbase.com/ (OCCT | AIO stress testing app)
- https://www.hwinfo.com/ (HWiNFO64 Temp/Voltage monitor **ONLY USE HWiNFO64 FOR MONITORING AND NOTHING ELSE**)

###### Optional Software 

**I WILL NOT PROVIDE LINKS TO STOLEN/PIRATED SOFTWARE**
- https://hcidesign.com/memtest/ (HCI Memtest free/paid & optional)
- https://www.karhusoftware.com/ramtest/ (Karhu RAM Test paid & optional)
- SCEWIN/AMISCE (BIOS modding tool without needing to flash firmware)
- AMIBCP (BIOS file modding tool for unlocking hidden menus)
- AFUWIN (BIOS R/W Tool)
- https://cdn.discordapp.com/attachments/715228846370062406/1005349661479030954/MMTool64.exe (MMTool Used for removing microcode)

###### Misc. Notes

- If you use a m.2 based drive take it out before ocing as it can break during very unstable system conditions
- Never use the iGPU (KF CPU or z490 APEX prefered)
- Good Aios to Consider, EVGA CLC 280/360, Arctic Liquid Frezzer ii 280/360

## Basic BIOS Setup

- All Spread Spectrum diabled
- All Power Gating disabled
- All C-States/Turbo/Freqency changing features disbaled
- Fixed VRM Freqency, use 500-800 (1000 can provide better results but 800 is prefered when possible)
- Voltage mode manual/overide
- Voltage "optimizations" diabled
- TVB disabled
- Raito Clipping disblaed
- V-Max Stress disbaled
- Fixed DRAM Freqency
- Power savings disabled 
- Ring Down Bin disabled
