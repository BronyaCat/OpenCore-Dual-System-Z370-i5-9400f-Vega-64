# OpenCore-Dual-System-Z370-i5-9400f-Vega-64
OpenCore EFI files, build with Mac/Win dual system.  

## Main Hardware Detail  

CPU: i5-9400f  
GPU: Vega 64 with 220 Watts Sapphire BIOS  
MotherBoard: ASRock Z370M Pro4  
PCIE Wifi Card: BCM94360CD From 小齐本本配件  

## Mac OS  
Version 10.15.6, fully functional EFI files.  

Lastes Notes 2020-09-10  
Update to OC 0.6.1  
Update all kexts to lastes version.  
Blackscreen tips：Disable hardware acceleration  in Chrome (Edge or other Chroium based browsers).



Notes 2020-09-05  
Fix unknow black screen issue.  
Add hibernation kext.    

Notes 2020-09-01  
Fix CPU frequency and sensor issue by CPUFriend and CPUFriendProvider.  
Delete SSDT of fake NVram control，use native NVRAM on motherboard.  
NO NEED to fix USB port on Z370.  
Rename PR00 in SSDT-GPRW.  
Inject RedaonBoost.kext V1.1 to fix stuck 945Mhz ram clock on GPU.  

## Win OS  
Version Win10 2005, fake motherboard ID as apple chassie.  

Lastes Notes 2020-09-10  
Flash 220W Sapphire Vega 64 BIOS.  



Notes 2020-09-01  
Stop gaming, start working.  

_____



### Warnning  
Change Platforminfo in Config before install the full EFIs if you don't want your Apple ID get baned.  
Change Mac type as imac pro1.1 or mac pro7.1 if you are using intel CPUs end with F.                *[important]*  
Check BIOS setting about CFG lock and XCHI-USB if you can find it.  



### (Also) Hardware tweak tips  

Flash 260w GPU BIOS without water cooling module can let you BBQ in your case.  
!!! Flash any Sapphire Vega BIOS helps lot in MacOS gaming and Android sitmulating !!!