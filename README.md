# [EFR32FG14](https://doc.soc.xin/EFR32FG14)

* [Silicon Labs](https://www.silabs.com/): [Cortex-M4](https://github.com/SoCXin/Cortex)
* [L1R3](https://github.com/SoCXin/Level): 40 MHz

## [简介](https://github.com/SoCXin/EFR32FG14/wiki)

[EFR32FG14](https://cn.silabs.com/wireless/proprietary/efr32fg14-series-1-sub-ghz-2-4-ghz-socs) 无线解决方案将节能型微控制器 (MCU) 与支持 2.4 GHz 和 1 GHz 以下专有无线协议的高度集成无线电收发器相结合。该单芯片解决方案非常适用于专有调制方式，包括 OOK、成形 FSK、成形 OQPSK、DSSS 调制技术和 FEC，可提供行业领先的能源效率、超快的唤醒时间、可扩展的功率放大器、集成的平衡-不平衡转换器以及性能不妥协的 MCU 功能。

### 关键参数

* 40MHz Cortex-M4 (67 µA/MHz)
* 32KB SRAM + 256 kB Flash
* 集成的 2.4 GHz BALUN 和功率放大器
    * -103.3 dBm @125 kbps，GFSK
    * -103.3 dBm @250 kbps，DSSS-OQPSK
    * 可编程的输出功率：+19.5 dBm
    * 有源模式 RX：8.8 mA @1 Mbps，2 GFSK
    * 有源模式 TX：8.5 mA @0 dBm , 34 mA @10.5 dBm
    * 低功率收音机包括 RFSENSE (51 nA)
    * 天线分集
* Sub-GHz专有协议，无线 M-BUS，支持的调制：2/4 (G)FSK，OQPSK/(G)MSK，OOK/ASK，BPSK/DBPSK，可选的 DSSS 调制技术和 FEC 信道编码
    * -126.2 dBm @600 bps, GFSK, 915 MHz
    * -120.6 dBm @2.4 kbps, GFSK, 868 MHz
    * -109.9 dBm @4.8 kbps, OOK, 433 MHz
    * -112.2 dBm @38.4 kbps, GFSK, 169 MHz
    * 可编程的输出功率：+20 dBm
    * 有源模式 RX：8.6 mA @38.4 kbps，2GFSK
    * 有源模式 TX：20.3 mA @10 dBm, 433 MHz，35.3 mA @14 dBm, 868 MHz
    * 天线分集
* 能耗模式 2 （深度睡眠）电流：1.3 µA
* 超快唤醒：从 EM3 仅 3 µS
* 1.8 至 3.8 V 的宽电源电压范围

## [资源收录](https://github.com/SoCXin)

* [参考资源](src/)
* [参考文档](docs/)
* [参考工程](project/)

## [选型建议](https://github.com/SoCXin/EFR32FG14)

[EFR32FG14](https://github.com/SoCXin/EFR32FG14)


## [www.SoC.xin](http://www.SoC.Xin)
