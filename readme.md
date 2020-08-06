# XDS100V2Emu

TI DSPC2000系列调试器XDS100V2 PCB工程

### 说明

原理图参照LAUNCHPADF28379D上的调试器部分电路，把FT2232芯片的封装换成LQFP64，更便于手动焊接。PCB工程使用的AD19绘制，在XDS100V2Emu文件中，包含两个PCB文件XDS100V2Emu.PcbDoc和XDS100V2EmuMini.PcbDoc。XDS100V2Emu.PcbDoc为接口带有隔离芯片的PCB(可不焊接隔离芯片)，XDS100V2EmuMini.PcbDoc是去掉隔离芯片，只有FT2232芯片的PCB。

MProg 3.5 Release.rar：给FE2232的EEPROM烧写配置信息的软件。

XDS100V2.ept：给软件MProg使用烧写软件。



注：PCB已完成制板并调试成功，完全实现LAUNCHPAD上的调试器功能。