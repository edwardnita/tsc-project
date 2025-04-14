# OpenBook - eBook Reader

**Autor:** Nita Eduard-Eugen
**Data:** 06 Aprilie 2025, updated pe 14 Aprilie 2025

![block_diagram](./Images/diagram.png)

## Bill of Materials (BOM)

| Component                | Link                                                                                                                      | Datasheet                                                                                                              |
|:-------------------------|:--------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------------------------------------|
| BME680                   | [Link](https://www.snapeda.com/parts/BME680/Bosch/view-part/?welcome=home)                                                | [Datasheet](https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bme680-ds001.pdf)            |
| BUTTON                   | [Link](https://industry.panasonic.com/global/en/products/control/switch/light-touch/number/evqpuj02k)                     | [Datasheet](https://www.lcsc.com/datasheet/lcsc_datasheet_2201121800_PANASONIC-EVQPUJ02K_C2936858.pdf)                 |
| R0402                    | [Link](https://componentsearchengine.com/part-view/R0402%201%25%20100%20K%20(RC0402FR-07100KL)/YAGEO)                     | [Datasheet](https://www.resistor.com/assets/pdf/0402tstd.pdf)                                                          |
| CPH3225A                 | [Link](https://www.snapeda.com/parts/CPH3225A/Seiko+Instruments/view-part/?ref=eda)                                       | [Datasheet](https://octopart.com/datasheet/cph3225a-seiko-25340571)                                                    |
| EVQPUJ02K                | [Link](https://industry.panasonic.com/global/en/products/control/switch/light-touch/number/evqpuj02k)                     | [Datasheet](https://www.lcsc.com/datasheet/lcsc_datasheet_2201121800_PANASONIC-EVQPUJ02K_C2936858.pdf)                 |
| KP-1608SURCK             | [Link](https://www.snapeda.com/parts/KP-1608SURCK/Kingbright/view-part/?ref=search&t=LED%200603)                          | [Datasheet](https://media.elv.com/file/107153_led_surck1608_data.pdf)                                                  |
| USBLC6-2SC6Y             | [Link](https://www.snapeda.com/parts/USBLC6-2SC6Y/STMicroelectronics/view-part/?ref=eda)                                  | [Datasheet](https://www.digikey.com/en/htmldatasheets/production/1375342/0/0/1/usblc6-2sc6y)                           |
| SD0805S020S1R0           | [Link](https://ro.mouser.com/ProductDetail/KYOCERA-AVX/SD0805S020S1R0?qs=jCA%252BPfw4LHbpkAoSnwrdjw%3D%3D)                | [Datasheet](https://www.alldatasheet.com/view.jsp?Searchword=SD0805S&sField=2)                                         |
| PGB1010603MR             | [Link](https://www.snapeda.com/parts/PGB1010603MR/Littelfuse/view-part/?ref=eda)                                          | [Datasheet](https://www.alldatasheet.com/view.jsp?Searchword=Pgb1010603mr)                                             |
| BD5229G-TR               | [Link](https://componentsearchengine.com/part-view/BD5229G-TR/ROHM%20Semiconductor)                                       | [Datasheet](https://www.lcsc.com/datasheet/lcsc_datasheet_2201131330_ROHM-Semicon-BD5229G-TR_C962636.pdf)              |
| XC6220A331MR-G           | [Link](https://componentsearchengine.com/part-view/XC6220A331MR-G/Torex)                                                  | [Datasheet](https://www.alldatasheet.com/view.jsp?Searchword=Xc6220)                                                   |
| USB4110-GF-A             | [Link](https://componentsearchengine.com/part-view/USB4110-GF-A/GCT%20(GLOBAL%20CONNECTOR%20TECHNOLOGY))                  | [Datasheet](https://gct.co/files/drawings/usb4110.pdf)                                                                 |
| Adafruit LEDCHIP-LED0603 | [Link](https://eu.mouser.com/ProductDetail/Adafruit/4208?qs=PzGy0jfpSMtbScLbr0L5dw%3D%3D)                                 | [Datasheet](https://www.arrow.com/en/manufacturers/adafruit-industries/datasheets)                                     |
| Bobina                   | [Link](https://store.comet.srl.ro/Catalogue/Product/43497/)                                                               | [Datasheet](https://www.scribd.com/document/814581278/Datasheet-Bobina)                                                |
| PFMF                     | [Link](https://www.mouser.co.uk/ProductDetail/EPCOS-TDK/B72520T0350K062?qs=dEfas%2FXlABIszF52uu7vrg%3D%3D)                | [Datasheet](https://ro.mouser.com/c/ds/circuit-protection/thermistors/resettable-fuses-pptc/?m=Schurter&series=PFMF)   |
| DMG2305UX-7              | [Link](https://componentsearchengine.com/part-view/DMG2305UX-7/Diodes%20Incorporated)                                     | [Datasheet](https://www.mouser.com/datasheet/2/115/DMG2305UX-266242.pdf)                                               |
| Si1308EDL-T1-GE3         | [Link](https://componentsearchengine.com/part-view/SI1308EDL-T1-GE3/Vishay)                                               | [Datasheet](https://www.alldatasheet.com/view.jsp?Searchword=Si1308edl)                                                |
| MCP73831T-5ACI/OT        | [Link](https://www.mouser.co.uk/ProductDetail/Microchip-Technology/MCP73831T-5ACI-OT?qs=hH%252BOa0VZEiAcgAcEkuamXg%3D%3D) | [Datasheet](https://ww1.microchip.com/downloads/en/DeviceDoc/MCP73831-Family-Data-Sheet-DS20001984H.pdf)               |
| SMD Solder               | [Link](https://grabcad.com/library/solder-jumpers-1)                                                                      |                                                                                                                        |
| W25Q512JVEIQ             | [Link](https://www.snapeda.com/parts/ESP32-C6-WROOM-1-N8/Espressif+Systems/view-part/?ref=eda)                            | [Datasheet](https://www.mouser.com/datasheet/2/949/W25Q512JV_SPI_RevB_06252019_KMS-2487502.pdf)                        |
| ESP32-C6-WROOM-1-N8      | [Link](https://www.snapeda.com/parts/ESP32-C6-WROOM-1-N8/Espressif+Systems/view-part/?ref=eda)                            | [Datasheet](https://www.mouser.com/catalog/specsheets/Espressif_ESP32_C6_WROOM_1%20_Datasheet_V0.1_PRELIMINARY_en.pdf) |
| DS3231SN#                | [Link](https://www.snapeda.com/parts/DS3231SN%23/Analog+Devices/view-part/?ref=eda)                                       | [Datasheet](https://www.alldatasheet.com/view.jsp?Searchword=Ds3231sn%20datasheet)                                     |
| MAX17048G+T10            | [Link](https://www.snapeda.com/parts/MAX17048G+T10/Analog+Devices/view-part/?ref=eda)                                     | [Datasheet](https://www.alldatasheet.com/view.jsp?Searchword=Max17048)                                                 |

## Descriere Hardware

OpenBook este un e-reader open source care folosește ESP32-C6 ca unitate de control. Dispozitivul se concentrează pe eficiență energetică, conectivitate și afișaj de calitate tip e-ink.

### Microcontroller: ESP32-C6

- Procesor: RISC-V 32-bit @ 160 MHz
- Interfețe utilizate:
  - **SPI**: pentru e-paper
  - **I2C**: pentru BME688 și MAX17048
  - **USB-C**: pentru alimentare și transfer date
  - **GPIO**: pentru butoane și control încărcare

### Display: E-paper 7.5”

- Rezoluție: 800x480 px, alb-negru
- Interfață: SPI
- Refresh complet < 1s, parțial < 0.5s
- Folosit pentru afișare cărți, meniuri, informații senzori

### Senzor Mediu: BME688

- Măsoară: temperatură, umiditate, presiune, calitate aer (eCO2, TVOC)
- I2C, 400kHz
- Datele sunt afișate în interfața de utilizator și pot fi logate

### Power Management:

- **Baterie**: 2500mAh Li-Po 3.7V
- **MAX17048**: estimează nivelul de încărcare
- **MCP73831**: controlează încărcarea prin USB-C (1A max)
- **Consum**:
  - Active: ~120mA
  - Sleep: <50µA

### Butoane:

- 3 butoane fizice pentru meniu, navigare și selectare
- Interfață GPIO, debounce hardware/firmware

### USB-C:

- Alimentare și transfer fișiere (USB MSC)
- Protecție ESD

### PCB și Carcasă:

- PCB 2-layer cu layout optimizat termic și EMC
- ENIG finish
- Carcasă ABS/PC, 250g, ergonomică, rezistentă la praf și stropire (IP estimat: IP52)

## Pini ESP32-C6

| Componentă       | Pin ESP32-C6 | Motiv Alegere           |
| ---------------- | ------------ | ----------------------- |
| E-Paper SPI CLK  | GPIO10       | SPI hardware            |
| E-Paper SPI MOSI | GPIO11       | SPI hardware            |
| E-Paper CS       | GPIO9        | Chip Select dedicat     |
| BME688 I2C SDA   | GPIO4        | I2C standard            |
| BME688 I2C SCL   | GPIO5        | I2C standard            |
| MAX17048 SDA     | GPIO4        | I2C partajat cu BME688  |
| MAX17048 SCL     | GPIO5        | I2C partajat cu BME688  |
| Buton 1          | GPIO6        | Navigare                |
| Buton 2          | GPIO7        | Selectare               |
| Buton 3          | GPIO8        | Back/Menu               |
| USB D+           | GPIO18       | USB funcționalitate MSC |
| USB D-           | GPIO19       | USB funcționalitate MSC |
