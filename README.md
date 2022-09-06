# Overclocking (CML, although some knowledge can be applied to other architectures)

## Why OC?
- Consistent performance compared to algorthim based "auto oc"
- If you play games (especially open world) you can see a huge boost in lows https://kingfaris.co.uk/blog/intel-ram-oc-impact/
- Responsive input (Input Delay/Lag)

## Steps

## Pre-OC Setup

- High quaility PSU and power conditioner (high quality house wiring will be more effective than a conditoner but we need to reduce as much EMI as possible)
- Use either a high quality thermal paste (Noctua NH-2) or liquid metal (Thermal Grizzly Conductonaut) with either a direct die frame or copper ihs or you are wasting time
- Use a 360mm **prefered** or 280mm (high cpm fans required) AIO or custom loop (make sure the block is copper)
- Use a 120mm or 140mm case fan for your ram sticks (with the heatsinks removed or swapped for copper) this is required as faster ram has tighter temperature requirements (sub 40c)
- One 4GB or larger usb for live linux/windows pe & bios flashing (**NEVER overclock on your os if you care about the data on it**)
- A disgusting amount of time (make sure ur doing nothing on a weekend)

###### Required Software 

- https://medicatusb.com/ (Windows PE + extra + ventoy)
- https://www.hirensbootcd.org/ (Windows PE)
- https://drive.google.com/uc?id=1TyeNihg6bKIrmyNwtJ7Fc3asD7XBnXsq&export=download (AutoGSAT CSM Required)
- https://www.mersenne.org/download/ (Prime95 CPU stress)
- https://www.techpowerup.com/download/linpack-xtreme/ (Linpack Xtreme CPU+RAM stress)
- https://github.com/BoringBoredom/Linpack-Extended (Linpack Extended CPU+RAM stress)
- Linpack Xtreme & Extended are slightly different as they use different versions of the binary (Xtreme is older) either is a good option for testing its mostly preference
- https://www.overclock.net/threads/memory-testing-with-testmem5-tm5-with-custom-configs.1751608/ (TM5 Ram Test)
- https://hcidesign.com/memtest/ (HCI Memtest free/paid & optional)
- https://www.karhusoftware.com/ramtest/ (Karhu RAM Test paid & optional)
- https://www.hwinfo.com/ (HWiNFO64 Temp/Voltage monitor **ONLY USE HWiNFO64 FOR MONITORING**)



###### Optional Software 
**I WILL NOT PROVIDE LINKS TO STOLEN/PIRATED SOFTWARE**
- SCEWIN/AMISCE (BIOS modding tool without needing to flash firmware)
- AMIBCP (BIOS file modding tool for unlocking hidden menus)
- https://cdn.discordapp.com/attachments/715228846370062406/1005349661479030954/MMTool64.exe (MMTool Used for removing microcode)
- AFUWIN (BIOS R/W Tool)

###### Misc. Notes
- If you use a m.2 based drive take it out before ocing as it can break during very unstable system conditions
- Never use the iGPU while ocing (never use it in general either)
- Good Aios to Consider, EVGA CLC 280/360 (Stock fans should be swapped for p14), Arctic Liquid Frezzer ii 280/360
- Case Fans: P14/P12 or Noctua Industral 3000RPM (Use curve for audio recording)

## BIOS Setup
- All Spread Spectrum diabled
- All C-States/Turbo/Freqency changing features disbaled
- Fixed VRM Freqency, use 500-800
- Voltage mode manual/overide
- Voltage "optimizations" diabled
- TVB disabled
- Fixed DRAM Freqency
- Power savings disabled 
- 
