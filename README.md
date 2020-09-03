# OpenCore-Dual-System-Z370-i5-9400f-Vega-64
OpenCore EFI files, build with Mac/Win dual system.

## Main Hardware Detail

CPU: i5-9400f
GPU: Vega 64 with 260 Watts BIOS
MotherBoard: ASRock Z370M Pro4
PCIE Wifi Card: BCM94360CD From 小齐本本配件

## Mac OS
Version 10.15.6, fully functional EFI files.

Lastes Notes 2020-09-01
Fix CPU frequency and sensor issue by CPUFriend and CPUFriendProvider.
Delete SSDT of fake NVram control，use native NVRAM on motherboard.
NO NEED to fix USB port on Z370.
Rename PR00 in SSDT-GPRW.
Inject RedaonBoost.kext V1.1 to fix stuck 945Mhz ram clock on GPU.

## Win OS
Version Win10 2005, fake motherboard ID as apple chassie.

Lastes Notes 2020-09-01
Stop gaming, start working.

### Warnning
Change Platforminfo in Config before install the full EFIs.
Change Mac type as imac pro1.1 or mac pro7.1 if you are using intel CPU with F. *important*
Check BIOS setting about CFG lock and XCHI-USB.
Don't flash 260w GPU BIOS without water cooling module, but EFIs still works with original GPU BIOS.
