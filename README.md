# PCB-Start
我用立创 EDA 的画的第一块 STM32 核心板，吐槽一下立创 EDA，Ctrl+Z 撤销功能有问题，有时候撤销到一个莫名奇妙的状态，然后也退不回去了（痛苦）。

## STM32 选型
- 小巧
- 低功耗
- 实惠
- SPI 用于驱动 128 * 128 or 256 * 160 的单色点阵屏
- UART 用于 tty 数据交互
- 中等容量的片上 SRAM
- 256K+ 片上 FLASH

发现 STM32F103VET 这款就不错，是官网可以拿样片的型号，然后到某宝上采购时发现首片 5 块钱（原价应该要 2 美元，窃喜），于是就买了一片

to be continue
