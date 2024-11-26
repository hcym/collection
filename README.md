# retro-console-remake是一个用来收集、记录复古游戏机改造方案的项目

项目中提到的改造方案大部分为github开源项目，少部分为本人参考网上公开资料设计的成果，仅做收集和备份。

## Contents

- [介绍](#介绍)
- [Famicom](#Famicom)
  - [设备本体改造](#设备本体改造)
  - [卡带及烧录器](#卡带及烧录器)
  - [外设](#外设)
- [Gameboy](#Gameboy)
  - [设备本体改造](#设备本体改造)
  - [卡带及烧录器](#卡带及烧录器)
  - [外设](#外设)
- [SFC](#SFC)
  - [设备本体改造](#设备本体改造)
  - [卡带及烧录器](#卡带及烧录器)
  - [外设](#外设)
- [MD](#MD)
  - [设备本体改造](#设备本体改造)
  - [卡带及烧录器](#卡带及烧录器)
  - [外设](#外设)
- [GBP](#GBP)
  - [设备本体改造](#设备本体改造)
  - [卡带及烧录器](#卡带及烧录器)
  - [外设](#外设)
- [GBC](#GBC)
  - [设备本体改造](#设备本体改造)
  - [卡带及烧录器](#卡带及烧录器)
  - [外设](#外设)
- [GBA](#GBA)
  - [设备本体改造](#设备本体改造)
  - [卡带及烧录器](#卡带及烧录器)
  - [外设](#外设)
- [WSC](#WSC)
  - [设备本体改造](#设备本体改造)
  - [卡带及烧录器](#卡带及烧录器)
  - [外设](#外设)
- [psp](#psp)
  - [设备本体改造](#设备本体改造)
  - [卡带及烧录器](#卡带及烧录器)
  - [外设](#外设)
- [nds](#nds)
  - [设备本体改造](#设备本体改造)
  - [卡带及烧录器](#卡带及烧录器)
  - [外设](#外设)
- [3ds](#3ds)
  - [设备本体改造](#设备本体改造)
  - [卡带及烧录器](#卡带及烧录器)
  - [外设](#外设)
- [N64](#N64)
  - [设备本体改造](#设备本体改造)
  - [卡带及烧录器](#卡带及烧录器)
  - [外设](#外设)
- [PS](#ps)
  - [设备本体改造](#设备本体改造)
  - [卡带及烧录器](#卡带及烧录器)
  - [外设](#外设)
- [ps2](#ps2)
  - [设备本体改造](#设备本体改造)
  - [DVD](#DVD)
  - [外设](#外设)
- [wii](#wii)
  - [设备本体改造](#设备本体改造)
  - [SD](#SD)
  - [外设](#外设)
- [ngc](#ngc)
  - [设备本体改造](#设备本体改造)
  - [免盘](#免盘)
  - [外设](#外设)
## 介绍

我们将从任天堂最早的掌机Gameboy和家用机FC/NES开始说起，直到WII/PS2

## Famicom
### 设备本体改造
#### NES解锁区
* [原贴](https://bbs.oldmantvg.net/thread-51466.htm)
* [或者看这里](./FC/NES锁区解锁方法.pdf).
#### FC-RGB
  * [LAVA-FC](http://www.lava-fc.top/) - 国产FC-rgb套件，开发作者炸大猫king.
  * [LAVARSC LITE](./FC/LavaRSCLite.zip)- 炸大猫开源的支持RGB,Svideo和复合视频信号的开源FCpcb。
  * [89版FC加装LAVA套件](./FC/89版fc改lava——孙大师.zip)
    * [孙大师改装newfc输出接口并加装lava套件的教程](./FC/任天堂FC89加装Lava%20FC%20RGB板，改newfc输出接口过程分享%20-%20创意DIY%20数码之家.pdf)
#### 89版FC改任天堂多功能尾插
  * [diy尾插](./FC/diy任天堂多功能尾插.zip)
#### 尾插
  * [有竖纹简易版](https://www.pcbway.com/project/shareproject/Famicom_AV_Power_Board_bc97a170.html)
  * [89版尾板带音频放大](https://oshwhub.com/ayong82/fc-wei-ban)
#### opentendo
  * [复刻nes](https://github.com/Redherring32/OpenTendo)
### 卡带及烧录器
 * [Coolgirl-Multicart(原版0402容阻)](https://github.com/ClusterM/coolgirl-famicom-multicart) - 俄罗斯作者Cluster的原版卡带及烧录器，使用Diptrace设计，容阻为0402封装，焊接难度较高。
   * [Famicom-dumper-writer](https://github.com/ClusterM/famicom-dumper-writer)- 烧录器需要配合[rom生成工具](https://github.com/ClusterM/coolgirl-multirom-builder)和[客户端](https://github.com/ClusterM/famicom-dumper-client)
 * [FC-kazzo烧录卡-8MB](https://oshwhub.com/hujie888/fc_2flash_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy) - 国内作者沐沐开源，支持mapper45,52,176。需要使用kazzo烧录。
 * [FC-MIX-epm240游戏卡](https://oshwhub.com/firseve/fc_mapper_240_copy)
 * [mapper4卡带](https://oshwhub.com/ayong82/fc-hong-bai-jimapper4-you-hu-ka-dian-lu)
 * [UNROM-512卡带](https://oshwhub.com/sinzo/nes-cartridge)
 * [NES-CN-ROM-256](https://github.com/emeargt/nes-cnrom)
 * [kazzo烧录器插件版](https://oshwhub.com/ayong82/kazzo-shao-lu-qi)
 * [kazzo烧录器贴片版](https://oshwhub.com/firseve/kazzo_smd)
 * [29系EPPROM编程器](https://oshwhub.com/firseve/eeprom_stc_copy)
#### 卡带相关
 * [原版卡带pcb封装](https://github.com/Gumball2415/NES-Famicom-Cartridge-Dimensions) - 原装卡带封装，用来复刻正版卡。
 * [FC60PIN转nes72pin](https://github.com/veremenko-y/famicom-to-nes)
 * [cic芯片复刻](https://github.com/krikzz/avrciczz)

### 外设
 * [手柄15针转7针9针双子星用](https://github.com/jeffqchen/TwinDiamond-Twin-Famicom-Expansion-to-NES-SNES-Controller-Adapter) - fc和双子星15针转两个7针nes手柄和两个7针sfc手柄
 * [手柄15针转7针9针原版FC用](https://github.com/jeffqchen/FamiCoun-Famicom-Front-Expansion-NES-SNES-Adapter)
 * [Fc&NES手柄改无线](https://yakaracolombia.github.io/esp32-online-tool/nes.html) - [原理图见此](./FC/fc、nes手柄改无线/diagrama-nes-lite.jpg)
 * [NES手柄pcb](https://gitlab.com/nes64/NES64) - NES controller replacement board for C64, Amiga, Atari
   *[说明](https://nes64.pryds.eu/instructions.html)
 
 * [NES手柄pcb]()
 * [NES手柄pcb]()
## Gameboy

 * **[Mesen 2](https://github.com/SourMesen/Mesen2/)** (GPL-3.0) - high accuracy, extensive built-in debugger and profiler, recommended for development.
 * [ares](https://ares-emu.net/) (ISC) - high accuracy.
 * [Mednafen](https://mednafen.github.io/) (GPL-2.0) - serial port emulation, built-in debugger.
   * [BizHawk](https://tasvideos.org/Bizhawk) - WonderSwan core based on Mednafen, features Lua scripting and rewind/movie support.
   * [wf-mednafen](https://github.com/WonderfulToolchain/wf-mednafen/releases/) - fork of Mednafen with emulation fixes and debugger UI/UX improvements, based on mednafenPceDev's work.
   * [WonderDroid Ultra](https://f-droid.org/packages/com.atelieryl.wonderdroid/) - fork of Mednafen, Android port.
 * [NitroSwan](https://github.com/FluBBaOfWard/NitroSwan) - WonderSwan emulator for Nintendo DS/DSi, user friendly WonderWitch support.
 * [StoicGoose](https://github.com/xdanieldzd/StoicGoose) (MIT) - C# WonderSwan emulator.
 * [Oswan](sourceforge.jp/projects/oswan/devel) (GPL-2.0) - legacy WonderSwan emulator with a built-in debugger.

### Peripheral emulators

These emulators are currently only supported by Mednafen by editing its `wswan.excomm` configuration option.

 * [WonderFence](https://bitbucket.org/trap15/wonderfence/src/master/) (MIT) - MobileWonderGate internet adapter emulator.

## SFC

 * [WSCPUTest](https://github.com/FluBBaOfWard/WSCPUTest) - V30MZ CPU behaviour
 * [WSHWTest](https://github.com/FluBBaOfWard/WSHWTest) - SoC interrupt/PPU timer handling
 * [WSTimingTest](https://github.com/FluBBaOfWard/WSTimingTest) - V30MZ CPU timing
 * [ws-test-suite](https://github.com/asiekierka/ws-test-suite) (MIT) - assorted hardware tests and testing tools
 * [rtctest](https://forums.nesdev.org/viewtopic.php?t=21513) - "2003 mapper + S-3511" RTC protocol and behaviour
 * [Robert Peip's test ROMs](https://github.com/MiSTer-devel/WonderSwan_MiSTer/tree/main/testroms) - sprite priority/window testing tool

## Software development

 * **[Wonderful](https://wonderful.asie.pl/)** - gcc-ia16 based C/ASM toolchain for WonderSwan and WonderWitch.
 * [owswan](https://github.com/jounikor/owswan) - OpenWatcom-based WonderSwan toolchain. 
 * [Kyoui](https://asie.pl/files/kyoui_2004_11_02.zip) - (mirror) tools for compiling WonderSwan binaries using OpenWatcom.
 * [WSLink](https://bitbucket.org/trap15/wonder/src/master/) (MIT) - NASM linker outputting WonderSwan and WonderWitch compatible binaries.

### Libraries

 * [libws](https://github.com/WonderfulToolchain/target-wswan-syslibs/tree/main/libws) (zlib) - hardware abstraction functions
 * [libwsx](https://github.com/WonderfulToolchain/target-wswan-syslibs/tree/main/libwsx) (zlib) - decompressors and other useful functions
 * [LZSS decompression routine](archive/orion-lzss-decompression-routine.asm) (public domain)

#### Music drivers

 * [WonderSwan Total Sound Driver](https://github.com/Shaw02/WTD)
 
### Tools

 * [Dekadence WonderSwan Tools](https://github.com/superjohan/wonderswan-tools) (MIT) - assorted Python scripts.
 * [splashbuilder](https://github.com/Godzil/splashbuilder) (BSD-3-Clause) - toolchain for creating custom WonderSwan Color boot splashes.

#### Graphics utilities

 * **[SuperFamiconv](https://github.com/Optiroc/SuperFamiconv)** (MIT) - tile/map converter with flexible palette/optimization options and mostly-complete WS/WSC support.
 * [bmp2swan](http://onorisoft.free.fr/retro.htm?ws/ws.htm) - simple bitmap converter.

## Source code

### Boilerplate

 * [Wonderful template](https://github.com/WonderfulToolchain/wonderful-i8086/tree/main/examples/wswan/template) - GCC/GAS-based template.
 * [wonder/template](https://bitbucket.org/trap15/wonder/src/master/samples/template/) - NASM-based template.

### Demos

 * [#wonderwitch IRC channel promo](https://github.com/tslanina/Retro-WonderSwanColor-Promo) (MIT)
 * [Bad Apple!! for WSwan](https://github.com/asiekierka/bad-apple-for-wswan) (MIT)
 * [HBlank Cylinder Effect](https://github.com/joffb/wsc-witch-cylinder)

### Games

 * [Inufuto's games](http://inufuto.web.fc2.com/8bit/) - written using a custom C-like toolchain.
 * [SwanDriving](http://sebastianmihai.com/swan-driving.html) ([Mono](http://sebastianmihai.com/swan-driving-bw.html)) - tech demo written with NASM.
 * [WonderSnake](https://github.com/tslanina/Retro-WonderSwanColor-Wondersnake) (GPL-3.0) - Snake game written with Borland TASM.

### Other programs

 * [144p Test Suite for WS](https://github.com/asiekierka/240p-test-ws) (GPL-3.0) - 240p Test Suite-inspired user-side testing tool
 * [BootFriend](https://wonderful.asie.pl/ws/bootfriend) (GPL-3.0) - WonderSwan custom "firmware"/splash screen patch - XMODEM software load to RAM and more!
 * [CartFriend](https://github.com/WonderfulToolchain/ws-cartfriend) (GPL-3.0) - WonderSwan cartridge menu/launcher
 * [Chips1](https://github.com/asiekierka/chips1) (MIT) - CHIP-8/SuperCHIP emulator.
 * [ieepview](https://github.com/asiekierka/ws-ieepview) (MIT) - internal EEPROM viewer/editor.
 * [ws-backup-tool](https://github.com/asiekierka/ws-backup-tool) (GPL-3.0) - cartridge backup/restore/flash tool and IPL dumper for BootFriend.
 * [wsmonitor](https://bitbucket.org/trap15/wsmonitor/) (MIT) - 80186 debug monitor.

### Miscellaneous

 * [vgmswan](https://github.com/asiekierka/vgmswan) (MIT/zlib) - .VGM playback and conversion tools.

## WonderWitch

 * [wonderwitchvc15](https://github.com/autumn009/wonderwitchvc15) - example on using Visual C++ 1.5 for compiling WonderWitch binaries.

### WW tools

 * [MiracleMage](https://github.com/Godzil/MiracleMage) (GPL-2.0) - high-level WonderWitch emulator, only supports "mono" software, does not require a WonderWitch ROM.
 * [romwitch](https://bitbucket.org/trap15/romwitch/) (GPL-2.0) - utility to inject executables into "static" WonderWitch software ROMs.

### WW documentation

 * [Don Walizer Jr's tutorials](https://www.donwalizerjr.com/tags/wonderswan) ([source code](https://github.com/dwalizer/wonderwitch)).
 * [wonder/doc/freya](https://bitbucket.org/trap15/wonder/src/master/doc/freya/) - initial Freya internals documentation.

### WW open-source homebrew

 * [dumpipl](https://github.com/up-n-atom/wwsoft/tree/master/dumpipl) (MIT) - WS/WSC initial program loader dumping tool (as "Soft" image).
 * [HummingCat](https://github.com/molety/HummingCat/) (MIT) - work-in-progress sound driver.
 * [vgmwitch](https://bitbucket.org/trap15/vgmwitch) (MIT) - SN76489 music player.
 * [WWTerm](https://github.com/WonderfulToolchain/WWTerm/tree/original) (GPL-2.0) - terminal emulator.
 * [yoppa](https://github.com/WonderfulToolchain/yoppa/tree/original) (BSD-3-Clause) - WWGP 2001 game.

## Hardware development

### Cartridges

 * [Bandai2003](https://github.com/up-n-atom/Bandai2003) (MIT) - Verilog "2003" mapper implementation.
 * [mbc-unlock](https://bitbucket.org/trap15/mbc-unlock) (CC0) - VHDL boot handshake implementation.
 * [nileswan](https://github.com/RSDuck/nileswan/) (GPLv3) - open-source flash cartridge.

### Peripherals

 * [ExtFriend](https://github.com/WonderfulToolchain/ws-extfriend) (GPL-3.0) - WonderSwan EXT<->USB adapter with digital audio capture.
 * [wsheadphone](https://github.com/zwenergy/wsheadphone) (CC-BY-NC-SA-4.0) - headphone DAC adapter.
 * [WS-LinkC](https://github.com/zwenergy/WS-LinkC) (CC-BY-NC-SA-4.0) - cheap, DIY-friendly link cable alternative.
 * [WSMtool](https://github.com/zwenergy/WSMtool) (CC-BY-NC-SA-4.0) - multitool adapter for the WonderSwan; headphone, serial and link cable adapter in one. 

### Screen capture

 * [nisetro_wsc](https://github.com/splash5/nisetro_wsc) (MIT) - FPGA-based screen capture solution.
 * [swancolorHD](https://github.com/zwenergy/swancolorHD) (GPL-3.0) - FPGA-based screen capture solution.
   * [swantroller](https://github.com/zwenergy/swantroller) (GPL-3.0) - WonderSwan Color-based controller PCB for the swancolorHD.

### Other hardware development

 * [USB WonderSwan Cartridge Utility](https://github.com/up-n-atom/WonderSwanCartTap) (MIT) - cartridge dumper and programmer.
 * [WonderSwan for MiSTer](https://github.com/MiSTer-devel/WonderSwan_MiSTer) (GPL-2.0)

## Historical

These are links to files and sources which are noteworthy from a historical perspective, but have been superseded.

 * [WSTech 2.4](https://github.com/OpenEmu/Mednafen-Core/blob/master/mednafen/wswan/wstech24.txt) - outdated document, incorrect in places.
