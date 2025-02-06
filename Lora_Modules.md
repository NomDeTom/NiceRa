# Module dimensions & formats

## SX1262

| Mfr        | Module                                                                                 | Dimensions        | TCXO | MCU / Lora       | IPEX | Pins                    | RF Switch |
| ---------- | -------------------------------------------------------------------------------------- | ----------------- | ---- | ---------------- | ---- | ----------------------- | --------- |
| Ebyte      | [E22-900M22S](https://www.cdebyte.com/products/E22-900M22S)                            | 20x14x3           | Yes  | SX1262           | Yes  | 1.27mm castle           | Ext       |
| Ebyte      | E22-900MM22S                                                                           | 10x10x2.5         | No   | SX1262           | No   | 1.27mm castle           | Ext       |
| Ebyte      | E22-900M30S                                                                            | 38.5x24x3.9       | Yes  | SX1262           | Yes  | 2.54mm castle           | Ext       |
| AI-Thinker | [RA-01SH](https://docs.ai-thinker.com/en/lora)                                         | 17x16x3.2         | No   | SX1262           | Yes  | 2.0mm castle            | Int       |
| Heltec     | [HT-RA62](https://docs.heltec.org/en/node/ht-ra62/index.html)                          | 17x16x1.8         | Yes  | SX1262           | Yes  | 2.0mm castle            | Int       |
| NiceRF     | [Lora1262](https://www.nicerf.com/lora-module/868mhz-sx1262-lora-module-lora1262.html) | 16x16x2.1         | yes  | SX1262           | No   | 2.0mm pin and castle    | Int       |
| Waveshare  | [Core1262-HF](https://www.waveshare.com/core1262-868m.htm)                             | 22x19x3.27        | yes  | SX1262           | Yes  | 2.54mm pin and castle   | Ext       |
| Waveshare  | [LoRa Node Module](https://www.waveshare.com/wiki/Pico-LoRa-SX1262)                    | 21x52             | yes  | SX1262           | Yes  | Breakout board          | Int       |
| RAK        | [4631](https://docs.rakwireless.com/Product-Categories/WisBlock/RAK4631/Overview/)     | 20x30             | Yes  | NRF52 & SX1262   | Yes2 | Wis connector           | Int       |
| RAK        | 4630                                                                                   | 15x23x3           | Yes  | NRF52 & SX1262   | Yes2 | 1.2mm castle on 4 sides |           |
| Minew      | [MS24SF1](https://www.minewstore.com/product/nrf52840-sx1262-ms24sf1/)                 | 25x23.5x2.8       | No   | NRF52 & SX1262   | Yes2 | Underside pads          | Ext P1.02 |
| Heltec     | [HT-CT62](https://docs.heltec.cn/en/node/esp32/ht_ct62/index.html)                     | 17.78x 17.78x 2.8 | Yes  | ESP32C3 & SX1262 | Yes2 | 1.27mm stamp            | Int       |
| Minew      | [SX1262-MS21SF13](https://en.minewsemi.com/lora-module/sx1262-ms21sf13)                | 16.4x 15x 3       | Yes  |                  |      |                         |           |
| Seeed      | [Wio-SX1262](https://www.seeedstudio.com/Wio-SX1262-Wireless-Module-p-5981.html)       | 11.6x11x 2.95     | Yes  | SX1262           | Yes  | 1.27mm stamp            | Ext[^1]   |

[^1]: For the WIO SX1262, RXEN is connected to RF_SW, and is required for full reception.


## MCU (NRF52840 & ESP32)

| Mfr            | Module                                                                              | Dimensions        | TCXO | MCU / Lora       | IPEX | Pins             | RF Switch |
| -------------- | ----------------------------------------------------------------------------------- | ----------------- | ---- | ---------------- | ---- | ---------------- | --------- |
| RAK            | [4631](https://docs.rakwireless.com/Product-Categories/WisBlock/RAK4631/Overview/)  | 20x30             | Yes  | NRF52 & SX1262   | Yes2 | Wis connector    | Int       |
| Minew          | [MS24SF1](https://en.minewsemi.com/lora-module/nrf52840-sx1262-ms24sf1)             | 25x23.5x2.8       | Unk  | NRF52 & SX1262   | Yes2 | Underside pads   | Ext P1.02 |
| Ebyte          | E73-2G4M08S1C                                                                       | 13x18x3           | __   | NRF52            | No   | Edge & Underside | Na        |
| Ebyte          | E73-2G4M08S1CX                                                                      | 13x18x3           | __   | NRF52            | Yes  | Edge & Underside | Na        |
| Nice!Keyboards | [Nicenano2](https://nicekeyboards.com/nice-nano/)                                   | 33x17.8x3.2       | __   | NRF52            | No   | 2.54mm holes     | Na        |
| SuperMini      | [nRF52840 Pro Micro](https://wiki.icbbuy.com/doku.php?id=developmentboard:nrf52840) | 33x17.8x3.2       | __   | NRF52            | No   | 2.54mm holes     | Na        |
| Seeed          | [Xiao BLE](https://wiki.seeedstudio.com/XIAO_BLE/)                                  | 21x17.5           | __   | NRF52            | No   | 2.54mm holes     | Na        |
| Heltec         | [HT-CT62](https://docs.heltec.cn/en/node/esp32/ht_ct62/index.html)                  | 17.78x 17.78x 2.8 | Yes  | ESP32C3 & SX1262 | Yes2 | 1.27mm stamp     | Int       |
| Seeed          | MDBT50Q-U1M                                                                         | 10.5x15.5x2.2     | __   | NRF52            | Opt  | Underside pads   | Na        |


## LR11xx

| Mfr    | Module                                                                      | Dimensions   | TCXO | MCU / Lora     | IPEX | Pins          | RF Switch |
| ------ | --------------------------------------------------------------------------- | ------------ | ---- | -------------- | ---- | ------------- | --------- |
| Ebyte  | [E80-900M2213S](E80-xxxM2213S_UserManual_EN_v1.0.pdf)                       | 26x16x3      | Yes  | LR1121         | Yes  | 1.27mm castle | Int       |
| Minew  | [ME25LS01](https://en.minewsemi.com/lora-module/lr1110-nrf52840-me25LS01)   | 25.5x20x2.6  | Yes  | NRF52 & LR1110 | No   | Underside     | Int       |
| NiceRF | [Lora1121](https://www.nicerf.com/lora-module/lora1121-module.html)         | 19.7x 15x2.2 | Yes  | LR1121         | No   | 2.0mm castle  | Int       |
| NiceRF | [LoRa1121F33-1G9](https://www.nicerf.com/lora-module/lora-1121f33-1g9.html) | 39x 21x3.3   | Yes  | LR1121         | No   | 3.93mm castle | Int       |


## LLCC68

| Mfr        | Module        | Dimensions  | TCXO | MCU / Lora | IPEX | Pins          | RF Switch |
| ---------- | ------------- | ----------- | ---- | ---------- | ---- | ------------- | --------- |
| Ebyte      | E220-900M22S  | 20x14x3     | Yes  | LLCC68     | Yes  | 1.27mm castle | Ext       |
| Ebyte      | E220-900MM22S | 10x10x2.5   | No   | LLCC68     | No   | 1.27mm castle | Ext       |
| Ebyte      | E220-900M30S  | 38.5x24x3.9 | Yes  | LLCC68     | Yes  | 2.54mm castle | Ext       |
| AI-Thinker | RA-01SCH      | 17x16x3.2   | No   | LLCC68     | Yes  | 2.0mm castle  | Int       |
