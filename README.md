# retro-console-mod是一个用来收集、记录复古游戏机改造方案的项目

项目中提到的改造方案大部分为github开源项目，少部分为本人参考网上公开资料设计的成果，仅做收集和备份。我没有涉及的机器就不多说了。欢迎在Issues中补充。如果某项内容的作者不希望我放在这里，可以联系我删除。

## 目录

- [介绍](#介绍)
- [Famicom](#Famicom)
- [SFC](#SFC)
- [MD](#MD)
- [Gameboy](#Gameboy) 
- [GBPGBC](#GBPGBC)
- [GBA](#GBA)
- [WSC](#WSC)
- [nds](#nds)
- [N64](#N64)
- [PS](#ps)
- [ps2](#ps2)
- [wii](#wii)
- [ngc](#ngc)
- [game&watch](#game&watch)
## 介绍

我们将从任天堂最早的掌机Gameboy和家用机FC/NES开始说起，直到WII/PS2。文章内容来自多个网站如：
* [consolemods](https://consolemods.org/wiki/Main_Page)

## Famicom
### 本体mod
  * [NES解锁区]
    * [原贴](https://www.consolesunleashed.com/guides/nintendo-entertainment-system-region-free-mod-install-guide/)
    * [或者看这里](./FC/NES锁区解锁方法.pdf).
  * [FC-RGB]
    * [LAVA-FC](http://www.lava-fc.top/) - 国产FC-rgb套件，开发作者炸大猫king.
    * [LAVARSC LITE](./FC/LavaRSCLite.zip)- 炸大猫开源的支持RGB,Svideo和复合视频信号的开源FCpcb。
    * [89版FC加装LAVA套件](./FC/89版fc改lava转接板.zip)
      * [数码之家@hanshgq改装newfc输出接口并加装lava套件的教程](./FC/任天堂FC89加装Lava%20FC%20RGB板，改newfc输出接口过程分享%20-%20创意DIY%20数码之家.pdf)
        * [原贴](https://www.mydigit.cn/forum.php?mod=viewthread&tid=418696&page=1)
      * [改lava的转接板](./FC/(红白机、NewFC、双子星)改lava转接板PCB源文件/)
  * [89版FC改任天堂多功能尾插]
    * [diy尾插](./FC/diy任天堂多功能尾插.zip)
  * [其他尾插]
    * [有竖纹简易版](https://www.pcbway.com/project/shareproject/Famicom_AV_Power_Board_bc97a170.html)
    * [89版尾板带音频放大](https://oshwhub.com/ayong82/fc-wei-ban)
  * [复刻NES]
    * [Opentendo](https://github.com/Redherring32/OpenTendo)
  * 小天才复刻
    * [复刻小天才](https://github.com/mleonid2000/dendy_junior_remastered)
  * [Candy 8bit]
    * [全集成复刻fc](https://github.com/HotPixelChannel/Candy_8bit/tree/main)
  * [红白机工程原理图](https://oshwhub.com/ayong82/hong-bai-ji-fu-ke_copy)
  * [FC CIC 复刻]
    * [avrciczz-ATTINY13](./FC/avrciczz-master.zip)
      * [ATTINY固件](https://github.com/krikzz/avrciczz)
  * [FC NES 蓝牙接收器]
    * [blueretro HW1 分支](https://github.com/darthcloud/BlueRetro/wiki/BlueRetro-Cables-Build-Instructions#fc--nes-adapter-cable)
### 卡带及烧录器
 * [Coolgirl-Multicart(原版0402容阻)](https://github.com/ClusterM/coolgirl-famicom-multicart) - 俄罗斯作者Cluster的原版卡带及烧录器，使用Diptrace设计，容阻为0402封装，焊接难度较高。
   * [Famicom-dumper-writer 新版烧录器stm32+cpld](https://github.com/ClusterM/famicom-dumper-writer)- 烧录器需要配合[rom生成工具](https://github.com/ClusterM/coolgirl-multirom-builder)和[客户端](https://github.com/ClusterM/famicom-dumper-client)
 * [旧版famicom-dumper-writer avr版](https://github.com/ClusterM/famicom-dumper)
 * [FC-kazzo烧录卡-8MB](https://oshwhub.com/hujie888/fc_2flash_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy_copy) - 国内作者沐沐开源，支持mapper45,52,176。需要使用kazzo烧录。
 * [FC-MIX-epm240游戏卡](https://oshwhub.com/firseve/fc_mapper_240_copy)
 * [mapper4卡带](https://oshwhub.com/ayong82/fc-hong-bai-jimapper4-you-hu-ka-dian-lu)
 * [UNROM-512卡带mapper30](https://oshwhub.com/sinzo/nes-cartridge)
 * [NES-CN-ROM-256 mapper3\mapper185](https://github.com/emeargt/nes-cnrom)
 * [norom unrom卡带不支持卡带烧录](./FC/烧录卡烧录器相关/norom%20unrom%20board/)
 * [kazzo烧录器插件版](https://oshwhub.com/ayong82/kazzo-shao-lu-qi)
 * [kazzo烧录器贴片版](https://oshwhub.com/firseve/kazzo_smd)
 * [29系EPPROM编程器](https://oshwhub.com/firseve/eeprom_stc_copy)
#### 卡带相关
 * [原版卡带pcb封装](https://github.com/Gumball2415/NES-Famicom-Cartridge-Dimensions) - 原装卡带封装，用来复刻正版卡。
 * [FC60PIN卡槽转nes72pin](https://github.com/veremenko-y/famicom-to-nes)
 
### 外设
 * [手柄15针转7针9针双子星用](https://github.com/jeffqchen/TwinDiamond-Twin-Famicom-Expansion-to-NES-SNES-Controller-Adapter) - fc和双子星15针转两个7针nes手柄和两个7针sfc手柄
 * [手柄15针转7针9针原版FC用](https://github.com/jeffqchen/FamiCoun-Famicom-Front-Expansion-NES-SNES-Adapter)
 * [Fc&NES手柄改无线](https://yakaracolombia.github.io/esp32-online-tool/nes.html) - [原理图见此](./FC/fc、nes手柄改无线/diagrama-nes-lite.jpg)
 * [NES手柄pcb（给C64雅达利用的）](https://gitlab.com/nes64/NES64) - NES controller replacement board for C64, Amiga, Atari
   * [说明](https://nes64.pryds.eu/instructions.html)
 * [NES手柄原理图](https://gamesx.com/wiki/doku.php?id=controls:nes_snes_controller)
 * [NES原理图大全](https://gamesx.com/wiki/doku.php?id=schematics:console_related_schematics)
 * [NES手柄转USB](https://github.com/MickGyver/DaemonBite-Retro-Controllers-USB/tree/master/NESControllersUSB)
 * [NES光枪](https://boojakascha.ch/index.php?page=NESLCDgun)
 * [鼠标转nes手柄](https://github.com/HotPixelChannel/Mouse-To-NES)

### 游戏资源及工具
 * [FC & FDS & NES 精选游戏 717](./FC/FC%20&%20FDS%20&%20NES%20精选游戏%20717.zip)
 * [mapper分类工具](./FC/各种工具/MapperTools.exe)
 * [旋风大佬网盘链接](http://flamecyclone.ysepan.com/)


## SFC
### 本体mod
 * [SNES RGB BYPASS MOD](https://github.com/borti4938/SNES_RGB_Bypass) - 包括1chip、JR和早期2chip的机型改装。
  * [2chip改rgb模块](https://www.pcbway.com/project/shareproject/W441760ASH29_2chip_snes_rgbmod_519bcb95.html)
 * [SNES_MultiRegion_with_DeJitter_QID](https://github.com/borti4938/SNES_MultiRegion_with_DeJitter_QID) - sfc用全区全制式模块以及去抖动。
 * [supercic](https://github.com/FluBBaOfWard/WSTimingTest) - V30MZ CPU timing
 * [sfc原理图](./SFC/snes_schematic_color.pdf)
 * [sfc jr 改s端子](./SFC/sfc%20jr%20改s端子.zip)
 * [SFC视频输出口3d复刻件](https://github.com/TRP-Retromods/SNES_AV_Connector) 
 * [PAL制sfc复刻](https://github.com/stonedDiscord/nonSNES)
 * [超任rgbs转VGA输出](https://github.com/jeffqchen/SNES2VGA)
 * [sfc蓝牙接收器 BR分支](https://github.com/darthcloud/BlueRetro/wiki/BlueRetro-Cables-Build-Instructions#sfc--snes-adapter-cable)
### 卡带及烧录器
 * [sd2snes](https://github.com/mrehkopf/sd2snes)
 * [SNES 2mb flashcard Lorom/Hirom no save pcb](https://www.pcbway.com/project/shareproject/SNES_2_mb_flashcard_Lorom_Hirom_nosave_pcb_a6cb9002.html)
 * **[Super Nintendo Game Cartridges](https://github.com/MouseBiteLabs/Super-Nintendo-Cartridges)**
 * [Snes Flash cart by RetroCircuits](https://www.pcbway.com/project/shareproject/Snes_Flash_cart_by_RetroCircuits_dc8cc488.html)
 * [SNES M27C801 HiRom 8Mib 无存档单卡5V片](https://www.pcbway.com/project/shareproject/SNES_M27C801_HiRom_8Mib_without_save_PCB_Single_Game_b414b148.html)
 * [SNES M27C801 LoRom 8Mib 无存档单卡5V片](https://www.pcbway.com/project/shareproject/SNES_M27C801_LoRom_8Mib_without_save_PCB_Single_Game_b11b7da3.html)
 * [SNES FlashCard Lorom/Hirom , 4mb max save pcb](https://www.pcbway.com/project/shareproject/SNES_FlashCard_Lorom_Hirom_4mb_max_save_pcb_eea1d7f7.html)
 * [SNES DIP 42 Lorom/hirom 2MO max save pcb](https://www.pcbway.com/project/shareproject/SNES_DIP_42_Lorom_hirom_2MO_max_save_pcb_3727cc9f.html)
 * [SNES FeRAM Cart](https://github.com/soniccd123/SNES-FeRAM-Cart)
 * [通用烧录器sanni cartreader](https://github.com/sanni/cartreader) - 支持国产d卡，以及上述多种卡带烧录。
### 外设
 * [锅仔片手柄板](https://www.pcbway.com/project/shareproject/SNES_Controller_Tac_Switch_Mod_6247d2dd.html)
 * [Super Game Boy Plus自制sgb](https://github.com/MouseBiteLabs/Super-Game-Boy-Plus/tree/main) - A replacement circuit board for improving the Super Game Boy, or for creating a standalone Game Boy game for the SNES.
 * [SNES / SUPER FAMICOM Region free unlock pcb](https://www.pcbway.com/project/shareproject/SNES_SUPER_FAMICOM_Region_free_unlock_pcb_b60baff7.html)
 * [原装双ic手柄pcb](https://www.pcbway.com/project/shareproject/SNES_OEM_Controller_PCB_Replacement_a41ce13c.html)
 * [sfc手柄改无线](https://yakaracolombia.github.io/esp32-online-tool/snes.html)- [原理图见此](./SFC/sfc手柄改无线.jpg)
 * [sfc手柄转USB](https://github.com/MickGyver/DaemonBite-Retro-Controllers-USB/tree/master/SNESControllersUSB)
 * [NES/SNES 双手柄转usb](https://www.raphnet.net/electronique/2nes2usb/index_en.php)
 ### 软件、rom及周边
 * [SFC游戏rom处理工具1](./SFC/Advanced_SNES_ROM_Utility.exe)-[SFC游戏rom处理工具2](./SFC/IpsAndSum.exe)
 * [SFC游戏老男人精选毕业包v1.0](./SFC/SFC游戏老男人精选毕业包v1.0.zip)
 * [sfc全部rom分类列表](./SFC/超任游戏分类.xlsx)
 * [經典SFC特輯杂志](./SFC/經典SFC特輯.zip)
 * [SFC官方说明书](./SFC/SNES%20Dev%20Manual.pdf)


## MD
### 本体mod
 * [MD转区转制式原理](https://mdpal60.net/regionmod)
   * [安装教程](https://immerhax.com/?p=386)
 * [Switchless_SEGA_MasterSystem_MegaDrive](https://github.com/borti4938/Switchless_SEGA_MasterSystem_MegaDrive)
   * [教程](https://www.consolesunleashed.com/guides/sega-mega-drive-switchless-region-mod-install-guide/srsltid=AfmBOor8aeRmFNeUghGUDB7NJx2qkr_vsDF6CyV0qAYE3aI9WQ8uvczm)
 * [Megadrive++](https://github.com/SukkoPera/MegaDrivePlusPlus) - 转区、改制式、手柄复位等功能
 * [md++简易版](https://github.com/pcm720/mdpp-r)
 * [双晶振模块](https://immerhax.com/?p=386)
   * [双晶振模块教程](https://www.consolesunleashed.com/guides/sega-mega-drive-dual-frequency-oscillator-install-guide/)
 * [初版triple bypass模块](https://github.com/db-electronics/triple-bypass-kicad) - MD三旁路模块，视频音频增强模块，绕过原始电路。
 * [Triple Bypass Version 2](https://github.com/tianfeng33/triple-bypass-Version-2) - 在初版基础上的更新
 * [Triple Bypass V2 Plus](https://github.com/zaxour/TripleBypassV2Plus) -在V2版本基础上的更新
 * [Mega Amp 2.0 Pro](https://github.com/TRP-Retromods/MegaAmp2Pro) - 音频改善模块非常适用于一些音效差的型号
 * [MD改S端子](https://consolemods.org/wiki/Genesis:S-Video_Mod)
 * [MD原理图](./MD/原理图/)
 * [各型号主板区别](https://consolemods.org/wiki/Genesis:Motherboard_Differences)
 * [rgbs转vga](https://github.com/jeffqchen/9DIN2VGA)
 * [复刻世嘉MDCD机主板](https://github.com/Board-Folk/MegaCD-Main-BD)
 * [MD蓝牙接收器HW1 BR分支](https://github.com/darthcloud/BlueRetro/wiki/BlueRetro-Cables-Build-Instructions#genesis-adapter-cable)
 ### 卡带及烧录器
 * [Genesis FeRAM Cart芯片记忆卡5V](https://github.com/soniccd123/Genesis-FeRAM-Cart)
 * [OpenDrive-Genesis芯片记忆卡带3V电平转换](https://github.com/soniccd123/OpenDrive-Genesis)
   * [上述两张卡的配套烧录器](https://github.com/soniccd123/OpenDrive-Programmer)
   * [上位机](https://github.com/soniccd123/OpenDrive-Editor)
 * [简易2合1md卡无存档](https://oshwhub.com/firseve/md-cart_copy)
 * [Sega Megadrive/Genesis , 27芯片带存档](https://www.pcbway.com/project/shareproject/Sega_Megadrive_Genesis_4Mo_FRAM_save_repro_PCB_0d6f159b.html)
 * [简易4MB单卡 无存档](./MD/卡带/PCB_MD短板_Final_2024-09-10.rar) - 老男人论坛@雷帕德安布雷拉
 * [简易4MB单卡带存档](./MD/卡带/PCB_MD记忆版美观版_2024-09-10.rar) - 老男人论坛@雷帕德安布雷拉
 * [乌克兰OPEN-ED](https://github.com/krikzz/open-ed)
 * [简易编程器](https://oshwhub.com/firseve/stc-md-tsop56)
 * [sanni cartreader](https://github.com/sanni/cartreader) - 目前固件仅支持MX29F1610卡带


### 其他改装
 * [SM801X复刻MD](https://github.com/HotPixelChannel/EHODRIVE_SM801_Sega_MD_Clone) - 支持rgbs输出
 * [鼠标转md控制器](https://github.com/HotPixelChannel/Mouse-To-SEGA-MD)
 * [MD大3键手柄改无线](https://yakaracolombia.github.io/esp32-online-tool/genesis.html)- [原理图见此](./MD/md手柄改无线.jpg)

### 游戏资源
 * [老男人精选](./MD/游戏精选/)



## Gameboy
### 设备本体mod
 * VIS_Modding改装
   * [VIS_Game_Boy_DMG支持原装屏幕的完全复刻](https://www.pcbway.com/project/shareproject/Replacement_PCB_for_the_original_gameboy_DMG_with_1_watt_speaker_lipo_battery_a_745f43ad.html) - 自带反显芯片，也支持锂电池、ips屏幕
   * [VIS Game Boy DMG 2.0仅支持ips屏幕](https://github.com/VISmodding/VIS-DMG-2.0/)
 * 原装主板复刻typec-DC口
   * [Super DMG-01](https://github.com/kamicane/Super-DMG-01)
 * MouseBiteLabs改装
   * [Game Boy DMG Color](https://github.com/MouseBiteLabs/Game-Boy-DMG-Color) - GBC改成厚GB，仅支持ips屏幕。
 * 加装反显芯片改背光
   * [74hc04d改装方案](https://www.instructables.com/Game-Boy-BivertBiversion-Moditication/)
   * [图例](./GAMEBOY/gb反显/)
   * [图文教程](https://consolemods.org/wiki/Game_Boy:Backlight_Mod)
 * 内录机
   * [GBHDMI](https://github.com/Martoni/GbHdmi)
 * 原理图
   * [DMG厚GB原理图大全](./GAMEBOY/gameboy系列全原理图/) - gekkio贡献的全系列原理图,包含主板、屏幕驱动板、电源板、耳机板
### 卡带及烧录器
 * [MBC1电池存档卡](https://github.com/MouseBiteLabs/Game-Boy-MBC1-Cartridge)
 * [MBC1芯片存档卡-小吞](./GAMEBOY/卡带相关/ProPrj_MBC1%20%20FRAM（AM29F016）(定稿)_2024-09-28.epro)
 * [原装mbc1改烧录卡](https://github.com/timville85/MBC1-Flash)
 * [MBC1芯片存档卡](https://github.com/ConsolesandCasks/MBC1-Jumper-Flash)
 * [烧录器统一见后文GBA部分](#GBA)
 * [卡带按mbcx分类查询](https://gbhwdb.gekkio.fi/cartridges/)
### GB卡带示波器
 * [GBDSO](https://github.com/pyroesp/GBDSO)
### 游戏资源精选
 * [老男人精选gameboy游戏](./GAMEBOY/GAMEBOY游戏老男人精选毕业包v1.0.zip)
### gameboy屏幕检测rom
 * [240ptest](./GAMEBOY/gb240p.gb)


## GBPGBC

### 本体mod
 * [GBP原装屏幕改反显](./GAMEBOY/gbp反显/)
 * [电源板 仅支持ips版](https://github.com/Jackv-makes/SGR/)
 * [GBC改gbp 仅支持ips屏幕](https://github.com/MouseBiteLabs/Game-Boy-Pocket-Color)
 * [GBC 主板复刻](https://github.com/ConsolesandCasks/Game-Boy-Pocket-Color) - 采用gbpc原理图仅支持ips屏
 * [gbc电源板复刻支持原装屏幕](https://github.com/ConsolesandCasks/CGB-R)
 * [GBC CPU-04主板逆向](https://github.com/nataliethenerd/CGB_ReverseEngineer)
 * [CPU-E gbc改gbpc](https://github.com/nataliethenerd/CPU-E-MGBC)
 * [系列原理图](./GAMEBOY/gameboy系列全原理图/MGB/)

### 卡带及烧录器
* [MBC5震动卡合卡5V芯片](https://github.com/conker19to21/Game-Boy-MBC5-Rumble-Multicart) - 需要原装MBC5 电池存档 MouseBiteLabs版改进
* [NekoCart](https://github.com/zephray/NekoCart-GB) Xilinx cpld模拟mbc芯片
* [正版卡改烧录卡各种flash转接板](https://github.com/JRodrigoTech/FLASH-ROM-Adapter-for-GameBoy)
* [MBC3时钟烧录卡5V芯片](https://github.com/MouseBiteLabs/Game-Boy-MBC3-Cartridge) - 电池存档MouseBiteLabs版
* [MBC3时钟烧录卡5V芯片](https://github.com/HDR/MBC3-Flashcart) - 芯片存档
* [MBC5烧录卡5V](https://github.com/HDR/MBC5-Flashcart) -芯片存档
* [gb相机卡复刻](https://github.com/HDR/Gameboy-Camera-Flashcart) - 需要原装卡芯片
* [MBC30口袋水晶烧录卡复刻](https://github.com/HDR/MBC30-Flashcart) - 水晶专用版型
* [白橙复刻3V芯片的MBC5震动卡](https://oshwhub.com/chrise/gameboy-mbc5-flashcart) - 芯片存档
* [小吞复刻3V芯片的MBC3时钟卡](https://oshwhub.com/hetunzi/mbc3-ldo-sram-test4) - 电池存档
* [小吞复刻3V芯片的MBC5](./GAMEBOY/卡带相关/ProPrj_MBC5%20电池%20(ldo)定稿_2024-09-28.epro) - 电池存档
* [Chisflash-MBC5](./GAMEBOY/卡带相关/chisflash%20mbc5/) - 支持nds烧录
* [正版卡pcb复刻](https://github.com/HDR/NintendoPCBs)
* [gba卡带版型的MBC5卡带](https://github.com/nm3210/GB_Flashcarts)
* [烧录器见GBA部分](#GBA)


## GBA


### 本体mod
 * [agb-03主板复刻](https://github.com/nataliethenerd/AGB_ReverseEngineer)
  * [文件](./GBA/AGB_ReverseEngineer-main.zip)
 * [gbasp原理图](./GAMEBOY/gameboy系列全原理图/AGS/)
 * [gbasp普亮复刻主板](https://oshwhub.com/morinaka/mori-de-gbasp-yuan-ji-fu-ke)
 * [gbasp改TYPEC充电](https://github.com/thatdecade/gba-sp-usb-c)
 * [gba内录机](https://github.com/zwenergy/gbaHD)
   * [内录机all in one](https://github.com/Zekfoo/gbaHD-AIO-Shield)
 * [GBA锂电池充电模块](https://oshwhub.com/morinaka/moripower-gba-yong-li-dian-chong-fang-mo-kuai)
 * [GBA逆向文档](https://problemkaputt.de/gbatek.htm#gbacartbackupids)
### 卡带及烧录器
 * [chisflash1.0普罗米修斯](https://oshwhub.com/chisbread/chisflash-prometheus) - 1M fram
   * [固件](./GBA/固件/chisflash1.0普罗米修斯.pof)
 * [ChisFlash V0.1 青春版 ](https://oshwhub.com/chisbread/chisflash-pichu) - 1M sram
    * [固件](./GBA/固件/chisflash0.1青春版.pof)
 * [ChisFlash v1.1 雪拉比 时钟卡](https://oshwhub.com/chisbread/chisflash-celebi) - 1Mflash+RTC 固件未开源
 * [ChisFlash v1.2 大岩蛇 震动卡](./GBA/开源卡带pcb/chisflash1.2震动卡.epro) - 1MFRAM+震动 固件未开源
 * [ChisFlash v1.1.1 老男人特供flash卡](./GBA/开源卡带pcb/老男人特供flash卡.epro)
   * [固件](./GBA/固件/ChisFlash1MFlash%20完美Flash识别固件+512Kb补丁.zip)
 * [烧录器旧版1.3gbxcart](https://www.pcbway.com/project/shareproject/FLASH_DIP_40_gb_gba_reader_burner_flashgbx_compatible_b89f0985.html) - 已经过时 固件hex可以在flashgbx的文件夹中找到cfw.hex(AVR熔丝位设置高位熔丝是0xda，低位是0xaf)
 * [BaconFlasher - GB/GBA卡带SPI读写模块](https://oshwhub.com/chisbread/baconflasher)
   * [配套PC端程序](改版FlashGBX：https://github.com/ChisBread/FlashGBX)

### 烧录相关

