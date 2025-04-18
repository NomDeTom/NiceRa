## NRF52 PRO MICRO PIN ASSIGNMENT

![Schematic for pro-micro ](./Schematic_NRF52_ProMicro_DIY.png)

This table is taken from the pin assignment in [variants/diy/nrf52_promicro_diy_tcxo/variant.h](https://github.com/meshtastic/firmware/blob/master/variants/diy/nrf52_promicro_diy_tcxo/variant.h)

| Pin   | Function    |     | Pin      | Function     | RF95  |
| ----- | ----------- | --- | -------- | ------------ | ----- |
| Gnd   |             |     | vbat     |              |       |
| P0.06 | Serial2 RX  |     | vbat     |              |       |
| P0.08 | Serial2 TX  |     | Gnd      |              |       |
| Gnd   |             |     | reset    |              |       |
| Gnd   |             |     | ext_vcc  | *see 0.13    |       |
| P0.17 | RXEN        |     | P0.31    | BATTERY_PIN  |       |
| P0.20 | GPS_RX      |     | P0.29    | BUSY         | DIO0  |
| P0.22 | GPS_TX      |     | P0.02    | MISO         | MISO  |
| P0.24 | GPS_EN      |     | P1.15    | MOSI         | MOSI  |
| P1.00 | BUTTON_PIN  |     | P1.13    | CS           | CS    |
| P0.11 | SCL         |     | P1.11    | SCK          | SCK   |
| P1.04 | SDA         |     | P0.10    | DIO1/IRQ     | DIO1  |
| P1.06 | Free pin    |     | P0.09    | RESET        | RST   |
|       |             |     |          |              |       |
|       | Mid board   |     |          | Internal     |       |
| P1.01 | Free pin    |     | 0.15     | LED          |       |
| P1.02 | Free pin    |     | 0.13     | 3V3_EN       |       |
| P1.07 | Free pin    |     |          |              |       |
