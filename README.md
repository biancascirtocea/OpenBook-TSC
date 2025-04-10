# OpenBook Reader

## Descriere generala

Proiectul **OpenBook ESP32-C6** este o platforma hardware compacta si portabila, dedicata aplicatiilor embedded cu consum redus de energie. Este construit in jurul microcontrollerului **ESP32-C6-WROOM-1-N8**, oferind conectivitate wireless (Wi-Fi 6 si BLE 5.0) si numeroase interfete pentru senzori si module externe. Platforma include un e-paper display, senzor de mediu BME688, modul RTC DS3231SN, memorie externa NOR Flash de 64MB, slot pentru SD card si sistem de alimentare cu baterie LiPo cu incarcator si indicator de nivel.

---

## Diagramă bloc

![alt text](./image-2.png)

---

## BOM - Bill of Materials

# BOM (Bill Of Materials)

| Componenta | Link | Datasheet |
|-----------|--------------|-----------|
| BUTTON | [Model](https://industry.panasonic.com/global/en/products/control/switch/light-touch/number/evqpuj02k) | [Datasheet](https://www.lcsc.com/datasheet/lcsc_datasheet_2201121800_PANASONIC-EVQPUJ02K_C2936858.pdf) |
| CAPACITOR | [Model](https://componentsearchengine.com/part-view/R0402%201%25%20100%20K%20(RC0402FR-07100KL)/YAGEO) | [Datasheet](//efaidnbmnnnibpcajpcglclefindmkaj/https://www.resistor.com/assets/pdf/0402tstd.pdf) |
| CPH3225A | [Model](https://www.snapeda.com/parts/CPH3225A/Seiko+Instruments/view-part/?ref=eda) | [Datasheet](https://octopart.com/datasheet/cph3225a-seiko-25340571) |
| EVQPUJ02K | [Model](https://industry.panasonic.com/global/en/products/control/switch/light-touch/number/evqpuj02k) | [Datasheet](https://www.lcsc.com/datasheet/lcsc_datasheet_2201121800_PANASONIC-EVQPUJ02K_C2936858.pdf) |
| KP-1608SURCK | [Model](https://www.snapeda.com/parts/KP-1608SURCK/Kingbright/view-part/?ref=search&t=LED%200603) | [Datasheet](//efaidnbmnnnibpcajpcglclefindmkaj/https://media.elv.com/file/107153_led_surck1608_data.pdf) |
| USBLC6-2SC6Y | [Model](https://www.snapeda.com/parts/USBLC6-2SC6Y/STMicroelectronics/view-part/?ref=eda) | [Datasheet](https://www.digikey.com/en/htmldatasheets/production/1375342/0/0/1/usblc6-2sc6y) |
| SD0805S020S1R0 | [Model](https://ro.mouser.com/ProductDetail/KYOCERA-AVX/SD0805S020S1R0?qs=jCA%252BPfw4LHbpkAoSnwrdjw%3D%3D) | [Datasheet](https://www.alldatasheet.com/view.jsp?Searchword=SD0805S&sField=2) |
| PGB1010603MR | [Model](https://www.snapeda.com/parts/PGB1010603MR/Littelfuse/view-part/?ref=eda) | [Datasheet](https://www.alldatasheet.com/view.jsp?Searchword=Pgb1010603mr&gad_source=1&gbraid=0AAAAADcdDU8aYfZtfJfdZ9I5j6RwZ_cbA&gclid=Cj0KCQjwqcO_BhDaARIsACz62vOPBOBe0eOh5gDUFkkKl4JBcbmoFZYtJ8BOnbaWqr_BuUCcVWvbutAaAmGkEALw_wcB) |
| BD5229G-TR  | [Model](https://componentsearchengine.com/part-view/BD5229G-TR/ROHM%20Semiconductor) | [Datasheet](https://www.lcsc.com/datasheet/lcsc_datasheet_2201131330_ROHM-Semicon-BD5229G-TR_C962636.pdf) |
| XC6220A331MR-G | [Model](https://componentsearchengine.com/part-view/XC6220A331MR-G/Torex) | [Datasheet](https://www.alldatasheet.com/view.jsp?Searchword=Xc6220&gad_source=1&gbraid=0AAAAADcdDU8aYfZtfJfdZ9I5j6RwZ_cbA&gclid=Cj0KCQjwqcO_BhDaARIsACz62vPS06NB6tLgniZzfaVpKNu1m811BNk6AEPfg4DbP6f5S8QWA_pW_UQaAv-0EALw_wcB) |
| XC6220A331MR-G | [Model](https://componentsearchengine.com/part-view/XC6220A331MR-G/Torex) | [Datasheet](https://www.alldatasheet.com/view.jsp?Searchword=Xc6220&gad_source=1&gbraid=0AAAAADcdDU8aYfZtfJfdZ9I5j6RwZ_cbA&gclid=Cj0KCQjwqcO_BhDaARIsACz62vMO5_aHsn35cIZBK6oCFuB_WOxz_zKu4yOHJ69-EnaUd5Jfas_Avm8aAuk5EALw_wcB) |
| USB4110-GF-A  | [Model](https://componentsearchengine.com/part-view/USB4110-GF-A/GCT%20(GLOBAL%20CONNECTOR%20TECHNOLOGY)) | [Datasheet](//efaidnbmnnnibpcajpcglclefindmkaj/https://gct.co/files/drawings/usb4110.pdf) |
| Adafruit | [Model](https://eu.mouser.com/ProductDetail/Adafruit/4208?qs=PzGy0jfpSMtbScLbr0L5dw%3D%3D) | [Datasheet](https://www.arrow.com/en/manufacturers/adafruit-industries/datasheets) |
| Bobina | [Model](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.scribd.com/document/814581278/Datasheet-Bobina) |
| PFMF | [Model](https://www.mouser.co.uk/ProductDetail/EPCOS-TDK/B72520T0350K062?qs=dEfas%2FXlABIszF52uu7vrg%3D%3D) | [Datasheet](https://ro.mouser.com/c/ds/circuit-protection/thermistors/resettable-fuses-pptc/?m=Schurter&series=PFMF) |
| DMG2305UX-7 | [Model](https://componentsearchengine.com/part-view/DMG2305UX-7/Diodes%20Incorporated) | [Datasheet](//efaidnbmnnnibpcajpcglclefindmkaj/https://www.mouser.com/datasheet/2/115/DMG2305UX-266242.pdf?srsltid=AfmBOop22k34YTJJra1xubiU6LPiN4M4JlcWbRoSNdxSGFak8uWgXPpK) |
| Si1308EDL-T1-GE3 | [Model](https://componentsearchengine.com/part-view/SI1308EDL-T1-GE3/Vishay) | [Datasheet](https://www.alldatasheet.com/view.jsp?Searchword=Si1308edl&gad_source=1&gbraid=0AAAAADcdDU-px713ONYSnQ2O-gcwqYcFq&gclid=Cj0KCQjwqcO_BhDaARIsACz62vN_Nz3MJOc6J_03gnVBm7aSqC8v9wyP0VD-iRKP-gFrYgdhLi99I14aAlVJEALw_wcB) |
| R0402 | [Model](https://componentsearchengine.com/part-view/R0402%201%25%20100%20K%20(RC0402FR-07100KL)/YAGEO) | [Datasheet](//efaidnbmnnnibpcajpcglclefindmkaj/https://www.resistor.com/assets/pdf/0402tstd.pdf) |
| BME680 | [Model](https://www.snapeda.com/parts/BME680/Bosch/view-part/?welcome=home) | [Datasheet](//efaidnbmnnnibpcajpcglclefindmkaj/https://www.bosch-sensortec.com/media/boschsensortec/downloads/datasheets/bst-bme680-ds001.pdf) |
| SMD Solder | [Model](https://grabcad.com/library/solder-jumpers-1) | [Datasheet]() |
| W25Q512JVEIQ | [Model](https://www.snapeda.com/parts/ESP32-C6-WROOM-1-N8/Espressif+Systems/view-part/?ref=eda) | [Datasheet](//efaidnbmnnnibpcajpcglclefindmkaj/https://www.mouser.com/datasheet/2/949/W25Q512JV_SPI_RevB_06252019_KMS-2487502.pdf?srsltid=AfmBOoquExqDVgxEELF9CzuOGxHos0CD1nQDROHD6Eebdm2foNzqozqU) |
| ESP32-C6-WROOM-1-N8 | [Model](https://www.snapeda.com/parts/ESP32-C6-WROOM-1-N8/Espressif+Systems/view-part/?ref=eda) | [Datasheet](//efaidnbmnnnibpcajpcglclefindmkaj/https://www.mouser.com/catalog/specsheets/Espressif_ESP32_C6_WROOM_1%20_Datasheet_V0.1_PRELIMINARY_en.pdf?srsltid=AfmBOooHQKNitqODRaaPjoZInfWKTacDER1t5uRK6sKqT13TrzvVo_B7) |
| DS3231SN# | [Model](https://www.snapeda.com/parts/DS3231SN%23/Analog+Devices/view-part/?ref=eda) | [Datasheet](https://www.alldatasheet.com/view.jsp?Searchword=Ds3231sn%20datasheet&gad_source=1&gbraid=0AAAAADcdDU-Gy9URfMxGmqiPg7ci5L3wR&gclid=Cj0KCQjwqcO_BhDaARIsACz62vMkK3ETSnW2w7mo0Fa-wgWJGn89AxWCyIND6k5X8MmoPl6hv6VWwT8aAiS-EALw_wcB) |
| MAX17048G+T10 | [Model](https://www.snapeda.com/parts/MAX17048G+T10/Analog+Devices/view-part/?ref=eda) | [Datasheet](https://www.alldatasheet.com/view.jsp?Searchword=Max17048&gad_source=1&gbraid=0AAAAADcdDU8aYfZtfJfdZ9I5j6RwZ_cbA&gclid=Cj0KCQjwqcO_BhDaARIsACz62vNa9xrVfzjCjADRwXD0RBbo4Nret3ywwteDGLJKZui8ZL8KdVlTE7caAvQxEALw_wcB) |
| MCP73831T-5ACI/OT | [Model](https://www.mouser.co.uk/ProductDetail/Microchip-Technology/MCP73831T-5ACI-OT?qs=hH%252BOa0VZEiAcgAcEkuamXg%3D%3D) | [Datasheet](//efaidnbmnnnibpcajpcglclefindmkaj/https://ww1.microchip.com/downloads/en/DeviceDoc/MCP73831-Family-Data-Sheet-DS20001984H.pdf) |

---

## Functionalitate Hardware

### ESP32-C6:
ESP32-C6 este unitatea centrală de procesare responsabilă pentru toate operațiunile sistemului, comunicarea cu senzorii și modulele, și gestionarea energiei. (Frecvență - 160 MHz)

- Microcontroller principal, gestioneaza toate perifericele.
- Comunicatii: Wi-Fi 6, BLE 5.0
- GPIO-uri multiple configurabile pentru I2C, SPI, UART.
Arhitectură: RISC-V 32-bit

### RTC - DS3231SN:
- Timp real precis,chiar si cand este sistemul oprit, compensare de temperatură, baterie de backup
- I2C comun cu BME688.

### Senzor BME688:
- Masoara temperatura, umiditate, presiune si VOC (gaze).
- I2C: conectat la aceeasi magistrala cu RTC.
- Monitorizarea condițiilor ambientale pentru ajustarea automată a afișajului și urmărirea datelor de mediu

### E-Paper Display:
- Afișaj pasiv cu consum foarte redus.
- Control prin SPI + pini de control (RST, DC, BUSY).
- Dimensiune: 7.5 inches
- Resolutie: 800x480 pixels

### Memorie NOR Flash 64MB:
- W25Q512JVEIQ - memorie externa SPI pentru loguri sau grafica e-paper.
- Memorie externă pentru loguri sau stocare grafică e-paper

### Slot SD Card:
- Alternativa pentru stocare loguri mari.
- Controlat tot prin SPI (CS separat).
- Memorie Flash externă: W25Q512JVEIQ - 64MB NOR Flash
- Memorie externă pentru loguri sau stocare grafică e-paper

### Sistem de alimentare:
- Intrare USB-C + protecție ESD.
- Capacitate: 3.7V, minim 1500mAh
- MCP73831 pentru incarcarea bateriei LiPo.
- MAX17048 pentru citire nivel incarcare baterie (via I2C).
- Tensiune de intrare: 5V prin conector USB-C
- Regulator de tensiune: LDO pentru stabilizare la 3.3V.

### Conector USB-C și Protecție ESD
- Funcționalitate: Asigură alimentarea cu energie și capacitatea de transfer de date
- Protecție: Protecție ESD integrată și diodă Schottky pentru siguranța la polaritate inversă

###  Butoane și Interfața Utilizator
- Butoane tactile pentru navigare și control.

### Extensii:
- Header Qwiic pentru conectarea de senzori I2C plug-and-play.
- Posibilitate de extindere prin interfețele GPIO disponibile

### Interfețe de Comunicare
GPIO: Utilizat pentru controlul butoanelor și operațiuni generale I/O
SPI: Utilizat pentru cardul SD, memoria flash externă și afișajul e-paper
I2C: Utilizat pentru senzorul de mediu BME688 și modulul RTC DS3231SN
UART: Utilizat pentru debugging și comunicare serială
Wi-Fi și Bluetooth: Furnizate de ESP32-C6, permițând conectivitate wireless

## Supervisori de Tensiune și Reset
Circuit de monitorizare a tensiunii pentru reset sigur
Indicator nivel încărcare baterie

## Dimensiuni și Specificații Fizice
Dimensiuni placă PCB: aproximativ 92 x 54 mm
Formă: PCB cu design compact și eficient pentru integrare în carcasă

## Caracteristici Principale
Consum ultra-redus de energie datorită afișajului e-paper și managementului avansat al energiei
Conectivitate wireless completă prin Wi-Fi 6 și Bluetooth 5.0
Monitorizare a condițiilor de mediu în timp real
Design modular pentru extindere ușoară și personalizare
Suport pentru stocare externă prin card microSD
Autonomie extinsă a bateriei

## Caracteristici Software
Compatibil cu diverse formate de cărți electronice
Interfață utilizator intuitivă pentru navigare și citire
Capacitate de sincronizare wireless cu dispozitive și servicii externe
Personalizare avansată a experienței de citire
Monitorizare și înregistrare a datelor de mediu

## Note de Design
Layout PCB optimizat pentru minimizarea interferențelor și maximizarea eficienței energetice.
Componente selectate pentru consum redus de energie și performanță fiabilă.
Soluții de protecție integrate pentru componente sensibile.
Design compact pentru portabilitate ridicată.

---

## Conexiuni catre ESP32-C6

| Pin ESP32-C6 | Funcție | Conectat la |
|--------------|---------|-------------|
| IO0 (MOSI) | SPI MOSI | E-paper, SD Card, Flash |
| IO1 (MISO) | SPI MISO | SD Card, Flash |
| IO2 (CLK) | SPI CLK | Toate SPI devices |
| IO3 (CS) | SPI CS | E-paper Display |
| IO4 | SPI CS | W25Q512 NOR Flash |
| IO5 | SPI CS | SD Card |
| IO6 | I2C SDA | BME688, RTC, Fuel Gauge |
| IO7 | I2C SCL | BME688, RTC, Fuel Gauge |
| IO8 | Buton Boot | GND prin rezistor |
| IO10, IO11 | UART0 | Programare / Debug |
| EN | Enable MCU | Legat la 3V3 prin pullup |

## Alte Observatii
- PCB Layout: oferă separare clară între power și logică digitală.

- Posibil montaj în carcasă 3D: puncte de prindere pentru șuruburi M2 pe marginile PCB.

- Ajustări Footprint : Bobina 744043680 și U4 (MAX17048G+T10) au fost ajustate pentru a preveni erori DRC.

- Restricții de Rutare Power
  * Majoritatea traseelor de alimentare sunt pe stratul superior
  * Necesitate de rutare parțială pe stratul inferior pentru unele trasee de alimentare
  * Plan de masă prezent pe ambele straturi pentru reducerea zgomotului și îmbunătățirea integrității semnalului

- Plasarea Componentelor
  * Layout-ul respectă design-ul de referință pentru eficiență optimă
  * Bateria se potrivește perfect lângă PCB în interiorul carcasei

- Puncte de Test : Test pads prezente pentru debugging pe semnale SPI/I2C/Power

- Număr și Amplasare Via-uri : Designul include 0 vias-uri pe traseul de putere.




