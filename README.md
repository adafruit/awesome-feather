<h1 align="center">
  <img width="853" src="https://github.com/adafruit/awesome-feather/blob/main/awesome_feather.png" alt="Awesome Feather"><br>Awesome Feather
</h1>

> A curated list of awesome Feather boards, add-ons (FeatherWings), guides, videos, software and resources.


https://user-images.githubusercontent.com/1685947/115119851-7dc6bb00-9f78-11eb-99d4-84d2bf5fea2d.mp4


Adafruit [Feather](https://www.adafruit.com/category/943) is a complete line of development boards from [Adafruit](https://www.adafruit.com/) and other developers that are both standalone and stackable. They're able to be powered by LiPo batteries for on-the-go use or by their micro-USB plugs for stationary projects. Feathers are flexible, portable, and as light as their namesake.

FeatherWings are stacking boards and add functionality and room for prototyping. At its core, the Adafruit Feather is a complete ecosystem of products - and the best way to get your project flying. 

All Adafruit products are open source. Adafruit encourages other companies to utilize this form factor to maximize compatibility with dozens of pre-existing boards.

## Contents

- [Guides](#guides)
- [Community](#community)
- [Code Frameworks](#code-frameworks)
- [Feather Hardware](#feather-hardware)
- [FeatherWings](#featherwings)
- [Accessories](#accessories)
- [In the news](#news)
- [Art, logos, graphics](#art)
- [Social media](#social)
- [Contributing](#contributing)

## Guides

- [Introducing Adafruit Feather](https://learn.adafruit.com/adafruit-feather/) - An overview of Feather and the Feather ecosystem.
- [learn.adafruit.com Feather](https://learn.adafruit.com/category/feather) - Adafruit Learning Guides on Feather.

## Community

- [Adafruit Discord channel #help-with-projects](https://discordapp.com/channels/327254708534116352/330406777009209346) - 24/7 chat and support on projects with Adafruit gear.
- [Adafruit Feather Forums](https://forums.adafruit.com/viewforum.php?f=57) - The Adafruit discussion forum on Feather.

## Code Frameworks

Feathers may be programmed in various languages which may vary by board. Here are language frameworks which may be used with specific Feather processor boards.

### CircuitPython

- [circuitpython.org](https://circuitpython.org/) - home to information on CircuitPython.
- [The Mu Editor, IDE, REPL, and plotter for CircuitPython](https://codewith.mu/) - The recommended Python editor for CircuitPython.
- [For developers, Mu: A Python Code Editor](http://mu.readthedocs.io/en/latest/) - The documentation for Mu.
- [CircuitPython (latest)](https://github.com/adafruit/circuitpython/releases/latest)
- [CircuitPython 7.0.0](https://blog.adafruit.com/2021/09/20/circuitpython-7-0-0-released/) 
- [CircuitPython API Reference](http://circuitpython.readthedocs.io/en/latest/) - A list of functions and documentation available for CircuitPython.
- [CircuitPython GitHub Repository](https://github.com/adafruit/circuitpython) - The source code for CircuitPython on GitHub.
- [Adafruit CircuitPython Libraries](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/blob/master/circuitpython_library_list.md) - Current Adafruit CircuitPython Libraries. There are over 330+ libraries available.

### Arduino

Setup of Arduino for:

- [Feather 328P](https://learn.adafruit.com/adafruit-feather-328p-atmega328-atmega328p/arduino-ide-setup)
- [Feather 32u4 Boards](https://learn.adafruit.com/adafruit-feather-m0-basic-proto/setup)
- [Feather M0 Boards](https://learn.adafruit.com/adafruit-metro-m0-express-designed-for-circuitpython/arduino-ide-setup)
- [Feather M4](https://learn.adafruit.com/adafruit-feather-m4-express-atsamd51/setup)
- [Feather nRF52832 and 40](https://learn.adafruit.com/introducing-the-adafruit-nrf52840-feather/arduino-bsp-setup)

## Feather Hardware

[Feather boards, Feather Wings and accessories](https://www.adafruit.com/category/943) - Complete listing of sensors, LCDs, displays, robotics, breakout boards, and more.

| Name | Features | Flash | RAM  | SPI Flash | Speed | CircuitPython | Arduino | Wireless |
|-------|------|---|---|---|---|---|---|---|
| [Adafruit Feather 328P - Atmega328P 3.3V](https://www.adafruit.com/product/3458) | Protoboard area | 32 KB | 2 KB | - | 8 MHz | - | Yes | - |
| [Adafruit Feather 32u4 Basic Proto](https://www.adafruit.com/product/2771) | Built-in protoboard | 32 KB | 2 KB | - | 8 MHz | - | Yes | - |
| [Adafruit Feather 32u4 Adalogger](https://www.adafruit.com/product/2795) | SD card support | 32 KB | 2 KB | - | 8 MHz | - | Yes | - |
| [Adafruit Feather 32u4 Bluefruit LE](https://www.adafruit.com/product/2829) | Bluetooth support | 32 KB | 2 KB | - | 8 MHz | - | Yes | BTLE |
| [Adafruit Feather 32u4 FONA](https://www.adafruit.com/product/3027) | Cellular network support | 32 KB | 2 KB | - | 8 MHz | - | Yes | Cellular |
| [Adafruit Feather HUZZAH with ESP8266](https://www.adafruit.com/product/2821) | WiFi support | 4 MB | 32KB 80KB | - | 80 MHz | - | Yes | WiFi |
| [Adafruit Feather HUZZAH32 with ESP32](https://www.adafruit.com/product/3405) | WiFi and Bluetooth | 4 MB | 520 KB | - | 240 MHz | - | Yes | WiFi / BTLE |
| [Adafruit ESP32 Feather V2](https://www.adafruit.com/product/5400) | WiFi and Bluetooth | 8MB | 2MB | - | 240 MHz | - | Yes | WiFi, Bluetooth, STEMMA QT, Low Power |
| [Adafruit Feather M0 Basic Proto](https://www.adafruit.com/product/2772) | Built-in protoboard | 256 KB | 32 KB | - | 48 MHz | Reduced  | Yes | - |
| [Adafruit Feather M0 Adalogger](https://www.adafruit.com/product/2796) | SD card support | 256 KB | 32 KB | - | 48 MHz | Reduced | Yes | - |
| [Adafruit Feather M0 Bluefruit LE](https://www.adafruit.com/product/2995) | Bluetooth support | 256 KB | 32 KB | - | 48 MHz | Reduced  | Yes | BTLE |
| [Adafruit Feather M0 WiFi](https://www.adafruit.com/product/3010) | ATWINC1500 Wi-Fi support | 256 KB | 32 KB | - | 48 MHz | Reduced  | Yes | WiFi |
| [Adafruit Feather M0 WiFi with uFL](https://www.adafruit.com/product/3061) | WiFi support | 256 KB | 32 KB | - | 48 MHz | Reduced  | Yes | WiFi |
| [Adafruit Feather STM32F205 with WICED](https://www.adafruit.com/product/3056) | WICED WiFi | 1024 KB | 128 KB | 2 MB | 120 MHz | - | Yes | WiFi |
| [Adafruit Feather 32u4 with RFM69HCW Packet Radio - 433MHz - RadioFruit](https://www.adafruit.com/product/3077) | RF Radio Support | 32 KB | 2 KB | - | 8 MHz | - | Yes | Packet |
| [Adafruit Feather 32u4 RFM69HCW Packet Radio - 868/915 MHz - RadioFruit](https://www.adafruit.com/product/3076) | RF Radio Support | 32 KB | 2 KB | - | 8 MHz | - | Yes | Packet |
| [Adafruit Feather 32u4 RFM96 LoRa Radio - 433MHz - RadioFruit](https://www.adafruit.com/product/3079) | RF Radio Support | 32 KB | 2 KB | - | 8 MHz | - | Yes | LoRa |
| [Adafruit Feather 32u4 RFM95 LoRa Radio - 868/915 MHz - RadioFruit](https://www.adafruit.com/product/3078) | RF Radio Support | 32 KB  | 2 KB | - | 8 MHz | - | Yes | LoRa |
| [Adafruit Feather M0 RFM69HCW Packet Radio - 433MHz - RadioFruit](https://www.adafruit.com/product/3177) |  RF Radio Support | 32 KB | 2 KB | - | 48 MHz | Reduced | Yes | Packet |
| [Adafruit Feather M0 RFM69HCW Packet Radio - 868 or 915 MHz - RadioFruit](https://www.adafruit.com/product/3176) | RF Radio Support | 32 KB | 2 KB | - | 48 MHz | Reduced  | Yes | Packet |
| [Adafruit Feather M0 with RFM95 LoRa Radio - 900MHz - RadioFruit](https://www.adafruit.com/product/3178) | RF Radio Support | 32 KB | 2 KB | - | 48 MHz | Reduced  | Yes | LoRa |
| [Adafruit Feather M0 RFM96 LoRa Radio - 433MHz - RadioFruit](https://www.adafruit.com/product/3179) | RF Radio Support | 32 KB | 2 KB | - | 48 MHz | Reduced  | Yes | LoRa |
| [Adafruit Feather nRF52 Bluefruit LE - nRF52832](https://www.adafruit.com/product/3406) | Bluetooth support | 512 KB | 64 KB | - | 64 MHz | - | Yes | BTLE |
| [Adafruit Feather nRF52832 Pro with myNewt Bootloader](https://www.adafruit.com/product/3574) | Bluetooth support | 512 KB | 64 KB |  | 64 MHz | - | Yes | BTLE |
| [Adafruit Feather nRF52840 Express](https://www.adafruit.com/product/4062) | Bluetooth support | 1 MB  | 256 KB | - | 64 MHz | Yes | Yes | BTLE |
| [Adafruit Feather nRF52840 Sense](https://www.adafruit.com/product/4516) | Bluetooth + Sensors | 1 MB  | 256 KB | - | 64 MHz | Yes | Yes | BTLE |
| [Adafruit Feather RP2040](https://www.adafruit.com/product/4884) | RP2040 chip | - | 264KB | 4MB | 125 MHz | Yes | Yes | - |
| [Adafruit Feather RP2040 SCORPIO](https://www.adafruit.com/product/5650) | 8 channel NeoPixel Driver | - | 264KB | 4MB | 125 MHz | Yes | Yes | - |
| [Adafruit M0 Express](https://www.adafruit.com/product/3403) | 1.44" display, sensors, amp | 256 KB | 32 KB | 2 MB | 48 MHz | Yes | Yes | - |
| [Adafruit HalloWing M0 Express](https://www.adafruit.com/product/3900) | 1.44" display, sensors, amp | 256 KB | 32 KB | 8 MB | 48 MHz | Yes | Yes | - |
| [Adafruit Feather M4 Express Cortex M4](https://www.adafruit.com/product/3857) | Proto area | 512 KB | 192 KB | 2 MB | 120 MHz | Yes | Yes | - |
| [Adafruit PyBadge](https://www.adafruit.com/product/4200) | 1.8" display, sensors, badge | 512 KB | 192 KB | 2 MB | 120 MHz | Yes | Yes | - |
| [Adafruit PyBadge LC](https://www.adafruit.com/product/3939) | 1.8" display, badge, budget | 512 KB | 192 KB | 2 MB | 120 MHz | Yes | Yes | - |
| [Adafruit PyGamer](https://www.adafruit.com/product/4242) | 1.8" display, sensors, gaming | 512 KB | 192 KB | 8 MB | 120 MHz | Yes | Yes | - |

Note: See the [Introduction to Feather Guide](https://learn.adafruit.com/adafruit-feather/circuitpython) on Reduced CircuitPython Capability boards (without off-processor Flash).

### Feather Compatible Processor Boards

| Company | Board | Features |
|---|---|---|
| Particle | [Xenon](https://www.adafruit.com/product/3999) | nRF52840 with BLE and Mesh  |
| Particle | [Argon](https://www.adafruit.com/product/3997) | nRF52840 with Mesh and WiFi |
| Particle | [Boron LTE](https://www.adafruit.com/product/3998) | nRF52840 with Mesh and LTE Cellular Modem |
| SD4Projects | [MiniMega2560 Adapter](https://github.com/Sd4Projects/MiniMega2560_Adapter) | Adapt the MiniMega256 to Feather for Wing compatibility |
| [Groboards](https://groboards.com/) | [Giant Board](https://www.crowdsupply.com/groboards/giant-board) | ATSAMA5D27C-D1G Linux system in Feather form factor |
| Wilderness Labs | [Meadow](https://www.kickstarter.com/projects/meadow/meadow-full-stack-net-standard-iot-platform) | STM32F7 .NET with WiFi and Bluetooth |
| Maxim | [MAX32620FTHR](https://www.maximintegrated.com/en/products/microcontrollers/MAX32620FTHR.html) | Cortex M4 Darwin MCU |
| Maxim | [MAX32630FTHR](https://www.maximintegrated.com/en/products/microcontrollers/MAX32630FTHR.html) | Cortex M4F with PMIC |
| minh7a6 | [MINHF4](https://hackaday.io/project/163853-minhf4-an-stm32f4-arduino-compatible-board) | STM32F411CE, Cortex M4F, Arduino Compatible |
| [Accumulatos](https://www.accumulatos.com/) | [AWS Re:Invent Lanyard](https://github.com/accumulatos/lanyard/tree/master/hardware) | Mongoose OS, AWS, ESP32 ([info](https://twitter.com/accumulatos/status/936156099484442624)) |
| Max Holliday | [SAM32](https://github.com/maholli/SAM32) | SAMD51, ESP32, SD Card, Camera Interface |
| [MCCI](https://store.mcci.com/) | [Catena 4610](https://store.mcci.com/collections/lorawan-iot-and-the-things-network/products/mcci-catena-4610-integrated-node-for-lorawan-technology) | Murata CMWX1ZZABZ-078, LoRaWAN 1.0/1.1 865-923 MHz |
| MCCI | [Catena 4612](https://mcci.com/lorawan/products/catena-4612/) | Murata CMWX1ZZABZ-078, LoRaWAN 1.0/1.1 865-923 MHz, FRAM |
| MCCI | [Catena 4801](https://mcci.com/lorawan/products/catena-4801/) | Murata CMWX1ZZABZ-078, LoRaWAN 1.02/1.1 865-923 MHz, RS-485/Modbus | 
| MCCI | [Catena 4618](https://mcci.com/lorawan/products/catena-4618/) | Murata CMWX1ZZABZ-078. LoRaWAN 1.1 865-923 MHz, SHT31-DIS-F Temp/Humidity, Si1133 IR/light/UV sensor |
| SparkFun | [ESP32 Thing Plus](https://www.sparkfun.com/products/14689) | Espressif ESP32 WROOM, WiFi, Bluetooth, Qwiic connector |
| SparkFun | [ESP32 Thing Plus - ESP32 WROOM (U.FL)](https://www.sparkfun.com/products/17381) | Espressif ESP32 WROOM, WiFi, Bluetooth, Qwiic connector, U.FL antenna connector |
| SparkFun | [ESP32 Thing Plus SkeleBoard - ESP32 WROOM (U.FL)](https://www.sparkfun.com/products/18581) | Espressif ESP32 WROOM, WiFi, Bluetooth, Qwiic connector, U.FL antenna connector |
| SparkFun | [Thing Plus - SAMD51](https://www.sparkfun.com/products/14713) | SAMD51 in a Feather size board with Qwiic |
| SparkFun | [Thing Plus - XBee3 Micro (U.FL)](https://www.sparkfun.com/products/15435) | XBee3 Micro Module (Zigbee 3.0) with Qwiic |
| SparkFun | [Thing Plus - XBee3 Micro (Chip Antenna)](https://www.sparkfun.com/products/15454) | XBee3 Micro Module (Zigbee 3.0) with Qwiic |
| SparkFun | [SparkFun Thing Plus - RP2040](https://www.sparkfun.com/products/17745) | RP2040 Microcontroller, 16MB Flash memory, SD card slot, Qwiic connector |
| SparkFun | [RED-V Thing Plus](https://www.sparkfun.com/products/15799) | SiFive RISC-V FE310 SoC with Qwiic connector and USB C |
| SparkFun | [SparkFun LoRa Thing Plus - expLoRaBLE](https://www.sparkfun.com/products/17506) | A Semtech SX1262 LoRa module paired with the Apollo3 MCU, used in the Artemis Module, Qwiic Connector |
| SparkFun | [SparkFun Thing Plus - nRF9160](https://www.sparkfun.com/products/17354) | Nordic nRF9160 microcontroller, CAT M1 LTE and NB-IoT cellular communication, Qwiic Connector |
| SparkFun | [SparkFun Thing Plus - STM32](https://www.sparkfun.com/products/17712) | STM32F405 Processor with a 32-bit ARM Cortex®-M4 core, Qwiic connector |
| SparkFun | [MicroMod Thing Plus](https://www.sparkfun.com/products/18027) | Feather form factor MicroMod CPU board with USB-C and Qwiic port |
| SparkFun / QuickLogic | [SparkFun Thing Plus - QuickLogic EOS S3](https://www.crowdsupply.com/sparkfun/thing-plus-quicklogic-eos-s3) | EOS S3 MCU + eFPGA SoC, LIS2DH12TR & PDM mic |
| [Quicklogic](https://www.quicklogic.com/) | [QuickFeather](https://www.quicklogic.com/products/eos-s3/quickfeather-development-kit/) | S3 Low Power MCU with embedded FPGA |
| The Things Network Sevilla | [T.O.G Mk1](https://twitter.com/ttn_sevilla/status/1117725090693767168) | Feather M0 clone with LoRaWAN |
| Ingenuity | [Micro Kea](http://www.ingenuity.co.nz/) | STM32F411 plus flash and ESP32 Pico-D-4 |
| [Makertronika Labs](https://www.tindie.com/stores/makertronika-labs/) | [TinyLoRa SAMR34 LoRA](https://www.tindie.com/products/makertronika-labs/tinylora-samr34-based-lora-devboard/) | ATSAMR34J18 based LoRA DevBoard |
| [Makertronika Labs](https://www.tindie.com/stores/makertronika-labs/) | [Penguino Feather 4260](https://www.tindie.com/products/makertronika-labs/penguino-feather-4260-samr34-lora-dev-board/) | ATSAMR34J18 based LoRa DevBoard - uses the RAK4260 module from @RAKWireless |
| [Makertronika Labs](https://www.tindie.com/stores/makertronika-labs/) | [Penguino STM32WL MAMWLE-C1](https://www.tindie.com/products/makertronika-labs/penguino-stm32wl-mamwle-c1-lora-dev-board/) | STM32WLE5JC Wireless SoC based LoRa DevBoard |
| [Actinius](https://www.actinius.com/) | [Icarus IoT Board](https://www.actinius.com/icarus) | nRF91: ARM Cortex M33, modem, low power, GPS and Cellular data (LTE-M / NB-IoT), accelerometer | 
| [Seeed](https://www.seeedstudio.com/) | [Wio Lite W600](https://www.seeedstudio.com/Wio-Lite-W600-p-4155.html) | W600 module and SAMD21, WiFi, Arduino compatible |
| [Seeed](https://www.seeedstudio.com/) | [Wio Lite RISC-V (GD32VF103) with ESP8266](https://www.seeedstudio.com/Wio-Lite-RISC-V-GD32VF103-p-4293.html) | RISC-V development board with RISC-V GD32VF103 and onboard ESP8266 Wio Core |
| [Ingenuity Micro](https://store.ingenuitymicro.com/) | [Kea](https://store.ingenuitymicro.com/kea) | STM32F411 based NETMF Feather board with a ESP32 coprocessor |
| [Wilderness Labs](https://store.wildernesslabs.co/) | [Meadow F7](https://store.wildernesslabs.co/products/meadow-f7) | STM32F7 uC with WiFi, BLE, 216MHz, 16MB RAM, 32MB Flash, 2D graphics and JPEG acceleration |
| Jed Hodson | [UWB Localization Feather](https://prototypingcorner.io/projects/uwb-feather/) | Decawave DWM1000 module and ATSAMD21 ARM Cortex M0 |
| Gregory Davill | [Orange Crab](https://github.com/gregdavill/OrangeCrab/) | Lattice ECP5 FPGA |
| [Electronic Cats](https://electroniccats.com/) | [BastWAN](https://electroniccats.com/blog/rak4260-el-microcontrolador-todo-en-uno-de-lora-ahora-en-arduino-ide) | Microchip SAM R34-based LoRa 868MHz and 915MHz and ATTEC608A security |
| [MakerTronika Labs](https://www.tindie.com/stores/makertronika-labs/) | [Penguino Feather SAMR34 LoRa Dev-Board](https://www.tindie.com/products/makertronika-labs/penguino-feather-samr34-lora-dev-board/) | ATSAMR34J18 System-in-Package (SiP) based MCU+LoRA RF module |
| Deshipu | [Fluff M0](https://hackaday.io/project/171381-fluff-m0) | A minimal SAMD21 M0 board in the Feather form factor |
| [Jared Wolff](https://www.jaredwolff.com.com/) | [nRF9160 Feather](https://www.jaredwolff.com/store/nrf91-feather/) | nRF9160: ARM Cortex M33, modem, low power, Cellular data (LTE-M / NB-IoT), active GPS antenna support, onboard flash, high efficency power supply | 
| Unexpected Maker | [FeatherS2](https://unexpectedmaker.com/shop/feathers2-esp32-s2) | ESP32-S2, 8MB PSRAM, 16MB SPI Flash, WiFi, STEMMA QT |
| Seth Kerr | [MSP432 Feather](https://github.com/skerr92/msp432-feather) | Feather using an MSP432P401R |
| PCB Arts | [Zynq Feather](https://www.pcb-arts.com/en/zynq_feather) | Zync systemn on chip in Feather form factor |
| [Reclaimer Labs](https://www.reclaimerlabs.com/) | [STM32WB Feather](https://www.reclaimerlabs.com/stm32wb-feather) | STM32WB Bluetooth SoC |
| [QuickLogic Corp.](https://www.quicklogic.com/) | [QuickFeather Dev Kit](https://shop.quicklogic.com/product/quickfeather-development-kit-uart-cable/) | Powered by QuickLogic’s EOS™ S3, the first FPGA-enabled Arm Cortex®-M4F MCU, fully supports Zephyr RTOS. 16-Mbit of flash memory, mCube MC3635 accelerometer, Infineon DPS310 pressure sensor, Infineon IM69D130 PDM digital microphone |
| Invector Labs | [Challenger Model 2040](https://site.invector.se/produkt/challenger-2040/) | RP2040, ESP8285 WiFi, USB-C connector |
| Move Solutions | [Penguino – MAMWLExx Breakout Board](https://www.movesolutions.it/2021/04/09/mamwlexx-breakout-board/) | STM32WLE5JB SoC, SX1262 RF Transceiver 150-960 MHz, LoRa (G)FSK, (G)MSK, BPSK |
| [Melopero](https://www.melopero.com/) | [Shake RP2040](https://www.melopero.com/shop/development-boards/melopero-shake-rp2040/) | RP2040 uC, 16MB Flash, Qwiic/Stemma QT |
| [ThingPulse](https://thingpulse.com/) | [ePulse Feather](https://thingpulse.com/product/epulse-feather-low-power-esp32-development-board/) | ESP32, 8MB PSRAM, 8MB Flash. Low Power |
| Unexpected Maker | [FeatherS2 Neo](https://www.adafruit.com/product/5629) | ESP32-S2, 4MB Flash, 2MB PSRAM, 5x5 RGB LED Matrix |
| Unexpected Maker | [FeatherS2](https://www.adafruit.com/product/4769) | ESP32-S2, 16MB Flash, 8MB PSRAM, STEMMA QT |
| Unexpected Maker | [FeatherS3](https://www.adafruit.com/product/5399) | ESP32-S3, 16MB Flash, 8MB PSRAM, 2xSTEMMA QT |

## FeatherWings

| Name  | Features  |
|---|---|
| [FeatherWing Proto - Prototyping Add-on](https://www.adafruit.com/product/2884) | Single Feather sized proto board, optional headers |
| [FeatherWing Doubler - Prototyping Add-on](https://www.adafruit.com/product/2890) | Two side-by-side Feather sockets |
| [FeatherWing Tripler Mini Kit - Prototyping Add-on](https://www.adafruit.com/product/3417)  | Three side-by-side feather sockets |
| [Adafruit Quad 2x2 FeatherWing Kit with Headers](https://www.adafruit.com/product/4253) | Base holding 4 FeatherWings 2x2 |
| [Adafruit Quad Side-By-Side FeatherWing Kit with Headers](https://www.adafruit.com/product/4254) | Base  holding 4 FeatherWings 1x4 |
| [Assembled Terminal Block Breakout FeatherWing](https://www.adafruit.com/product/2926) | Fully assembled |
| [Adafruit Prop-Maker FeatherWing](https://www.adafruit.com/product/3988) | Multiple drivers for props |
| [Adafruit Ultimate GPS FeatherWing](https://www.adafruit.com/product/3133) | GPS receiver with battery backup |
| [Adafruit CRICKIT FeatherWing](https://www.adafruit.com/product/3343) | Multiple motor drivers, NeoPixel driver, amplifier, GPIO |
| [Adafruit Music Maker FeatherWing](https://www.adafruit.com/product/3357) | MicroSD Card, MP3 OGG WAV MIDI Synth Player |
| [Adafruit Music Maker FeatherWing with Amplifier](https://www.adafruit.com/product/3436) | MP3 OGG WAV MIDI Synth Player - Stereo 3W Amplifier |
| [Adafruit Ethernet FeatherWing](https://www.adafruit.com/product/3201) | WIZ5500 Ethernet Client |
| [Adafruit DC Motor + Stepper FeatherWing](https://www.adafruit.com/product/2927) | 4 DC Motors or 2 Steppers |
| [Adafruit INA219 FeatherWing](https://www.adafruit.com/product/3650) | Power monitoring |
| [Adafruit Power Relay FeatherWing](https://www.adafruit.com/product/3191) | Relay rated to 250V AC |
| [Adafruit Latching Mini Relay FeatherWing](https://www.adafruit.com/product/2923) |  Latching Relay 250V AC |
| [Adafruit Non-Latching Mini Relay FeatherWing](https://www.adafruit.com/product/2895) | Non-latching relay 250V AC |
| [Adafruit 8-Channel PWM or Servo FeatherWing Add-on](https://www.adafruit.com/product/2928) | 8 x 12-bit PWM outputs |
| [Adafruit AMG8833 IR Thermal Camera FeatherWing](https://www.adafruit.com/product/3622) | Panasonic AMG8833 8x8 GridEYE sensor |
| [Adafruit Joy FeatherWing](https://www.adafruit.com/product/3632) | 2-axis joystick, 5 momentary button controller |
| [DS3231 Precision RTC FeatherWing - RTC Add-on](https://www.adafruit.com/product/3028) | I2C-integrated Real Time Clock (RTC) |
| [Adalogger FeatherWing - RTC + SD Add-on](https://www.adafruit.com/product/2922) | Adds a SD card slot and real-time clock |
| [Adafruit Teensy 3.x Feather Adapter](https://www.adafruit.com/product/3200) | Use Teensy 3 with all FeatherWings / Feather accessories |
| [Adafruit AirLift FeatherWing – ESP32 WiFi Co-Processor](https://www.adafruit.com/product/4264) | ESP32 WiFi and Bluetooth |
| [Adafruit LoRa Radio FeatherWing - RFM95W 433 MHz - RadioFruit](https://www.adafruit.com/product/3232) | LoRa Radio at 433 MHz |
| [Adafruit LoRa Radio FeatherWing - RFM95W 900 MHz - RadioFruit](https://www.adafruit.com/product/3231) | LoRa Radio at 900 MHz |
| [Adafruit Radio FeatherWing - RFM69HCW 433MHz - RadioFruit](https://www.adafruit.com/product/3230) | RFM69 radio at 433 MHz |
| [Adafruit Radio FeatherWing - RFM69HCW 900MHz - RadioFruit](https://www.adafruit.com/product/3229) | RFM69 radio at 900 MHz | 
| [Adafruit FeatherWing OLED - Loose Headers](https://www.adafruit.com/product/2900) | 128x32 OLED Display |
| [Adafruit FeatherWing OLED - Soldered Headers](https://www.adafruit.com/product/3045) | 128x32 OLED Display |
| [Adafruit Mini Color TFT with Joystick FeatherWing](https://www.adafruit.com/product/3321) | 0.96" 160x80 Color TFT Display with 16-bit full color |
| [Adafruit TFT FeatherWing](https://www.adafruit.com/product/3315) | LCD 320x200 2.4" with touchscreen |
| [Adafruit TFT FeatherWing](https://www.adafruit.com/product/3651) | LCD 480x320 3.5" with touchscreen |
| [Adafruit NeoPixel FeatherWing - 4x8 RGB LED](https://www.adafruit.com/product/2945) | 4x8 matrix of RGB NeoPixels |
| [Adafruit DotStar FeatherWing - 6x12](https://www.adafruit.com/product/3449) | 6 x 12 RGB DotStar LEDs |
| [Adafruit RGB Matrix Featherwing Kit](https://www.adafruit.com/product/3036) | For M0 or M4, drive 16 or 32-pixel tall matrix boards |
| [Adafruit NeoPXL8 FeatherWing for Feather M0](https://www.adafruit.com/product/3249) | DMA 8 strands of NeoPixels concurrently (8x250) | 
| [Adafruit 15x7 CharliePlex LED Matrix Display - Red](https://www.adafruit.com/product/3134) | Red LEDs in a 15x7 matrix |
| [Adafruit 15x7 CharliePlex LED Matrix Display - Green](https://www.adafruit.com/product/3136) | Green LEDs in a 15x7 matrix |
| [Adafruit 15x7 CharliePlex LED Matrix Display - Blue](https://www.adafruit.com/product/3137) | Blue LEDs in a 15x7 matrix |
| [Adafruit 15x7 CharliePlex LED Matrix Display - Yellow](https://www.adafruit.com/product/3135) | Yellow LEDs in a 15x7 matrix |
| [Adafruit 15x7 CharliePlex LED Matrix Display - Cool White](https://www.adafruit.com/product/3138) | Cool white LEDs in a 15x7 matrix |
| [Adafruit 15x7 CharliePlex LED Matrix Display - Warm White](https://www.adafruit.com/product/3163) | Warm white LEDs in a 15x7 matrix |
| [Adafruit 0.8" 8x16 LED Matrix FeatherWing Display - Red](https://www.adafruit.com/product/3152) | 8x16 LED matrix display |
| [Adafruit 0.8" 8x16 LED Matrix FeatherWing Display - White](https://www.adafruit.com/product/3149) | 8x16 LED matrix display |
| [Adafruit 0.8" 8x16 LED Matrix FeatherWing Display - Blue](https://www.adafruit.com/product/3150) | 8x16 LED matrix display |
| [Adafruit 0.8" 8x16 LED Matrix FeatherWing Display - Green](https://www.adafruit.com/product/3151) | 8x16 LED matrix display |
| [Adafruit 0.8" 8x16 LED Matrix FeatherWing Display - Yellow](https://www.adafruit.com/product/3153) | 8x16 LED matrix display |
| [Adafruit 0.8" 8x16 LED Matrix FeatherWing Display - Yellow/Green](https://www.adafruit.com/product/3154) | 8x16 LED matrix display |
| [Adafruit 4-Digit 7-Segment LED Matrix Display Driver](https://www.adafruit.com/product/3088) | Add a 4-digit 7-segment numeric display |
| [Adafruit 0.56" 4-Digit 7-Segment FeatherWing Display - Red](https://www.adafruit.com/product/3108) | 0.56" 4-Digit 7-Segment Display w/Wing Combo Pack |
| [Adafruit 0.56" 4-Digit 7-Segment FeatherWing Display - Blue](https://www.adafruit.com/product/3106) | 0.56" 4-Digit 7-Segment Display w/Wing Combo Pack |
| [Adafruit 0.56" 4-Digit 7-Segment FeatherWing Display - Green](https://www.adafruit.com/product/3107) | 0.56" 4-Digit 7-Segment Display w/Wing Combo Pack |
| [Adafruit 0.56" 4-Digit 7-Segment FeatherWing Display - Yellow](https://www.adafruit.com/product/3110) | 0.56" 4-Digit 7-Segment Display w/Wing Combo Pack |
| [Adafruit 0.56" 4-Digit 7-Segment FeatherWing Display - White](https://www.adafruit.com/product/3109) | 0.56" 4-Digit 7-Segment Display w/Wing Combo Pack |
| [Adafruit 14-Segment Alphanumeric LED Driver](https://www.adafruit.com/product/3089) | Add a 4-digit 14-segment alphanumeric display |
| [Adafruit 0.54" Quad Alphanumeric FeatherWing Display - Red](https://www.adafruit.com/product/3130) | Red Adafruit 0.54" Dual Alpha Display w/Wing Combo Pack |
| [Adafruit 0.54" Quad Alphanumeric FeatherWing Display - Blue](https://www.adafruit.com/product/3128) | Blue Adafruit 0.54" Dual Alpha Display w/Wing Combo Pack |
| [Adafruit 0.54" Quad Alphanumeric FeatherWing Display - Yellow/Green](https://www.adafruit.com/product/3132) | Yellow/Green Adafruit 0.54" Dual Alpha Display w/Wing Combo Pack |
| [Adafruit 0.54" Quad Alphanumeric FeatherWing Display - Green](https://www.adafruit.com/product/3129) | Green Adafruit 0.54" Dual Alpha Display w/Wing Combo Pack |
| [Adafruit 0.54" Quad Alphanumeric FeatherWing Display - Yellow](https://www.adafruit.com/product/3131) | Yellow Adafruit 0.54" Dual Alpha Display w/Wing Combo Pack |
| [Adafruit 0.54" Quad Alphanumeric FeatherWing Display - White](https://www.adafruit.com/product/3127) | White Adafruit 0.54" Dual Alpha Display w/Wing Combo Pack |

### FeatherWings (non-Adafruit)

| Company | Board | Features |
|---|---|--------|
| [Pimoroni](https://shop.pimoroni.com/) | [Enviro+ FeatherWing](https://shop.pimoroni.com/products/enviro-plus-featherwing) | Color LCD, 3 sensors and microphone for air quality |
| Capable Robot Components | [SenseTemp](https://www.crowdsupply.com/capable-robot-components/sensetemp) | Four-channel temperature sensor for instrumenting electronics |
| Particle | [Ethernet FeatherWing](https://www.adafruit.com/product/4003) | Ethernet with two Feather slots |
| Particle | [Particle Classic Adapter](https://store.particle.io/) | Use classic Photon accessories with Feather Footprint |
| Seeed | [Grove Shield for Particle Mesh](https://www.seeedstudio.com/Grove-Shield-for-Particle-Mesh-p-4080.html) | Large FeatherWing with eight Grove sensor connections |
| davedarko | [USB Host FeatherWing](https://hackaday.io/project/161845-max3421e-featherwing) | USB Host add-on for MAX3421E |
| armin.von_collrepp | [CAN Bus FeatherWing](https://easyeda.com/armin.von_collrepp/Adafruit_CAN_FeatherWing-0YRL3lfxP) | MCP2515 based CAN controller with an 3.3V CAN transceiver |
| [Argo](https://twitter.com/olygineer) | [CANbus FeatherWing](https://twitter.com/olygineer/status/1146133929235308544) | CAN Bus, regulated DC in, I2C STEMMA/Grove/Qwiic connection |
| [IAmOrion](https://www.tindie.com/stores/iamorion/) | [Feather CANBus Shield](https://www.tindie.com/products/iamorion/feather-canbus-shield/) | CAN Bus FeatherWing (PCB Only) |
| Tisham Dhar | [ADS1115 Featherwing](http://whatnicklife.blogspot.com/2016/01/extending-energy-monitoring-ads1115.html) | Energy monitoring specific ADS1115 breakout |
| Tisham Dhar | [ATM90E26 FeatherWing](https://www.tindie.com/products/whatnick/atm90e26-featherwing/) | ATM90E26 Utility Grade Energy Monitor |
| Justin Jordan | [1-Wire Wing Data Logger](https://www.hackster.io/justin-jordan/1-wire-wing-data-logger-w-max32630fthr-ada46a?ref=part&ref_id=31815&offset=1) | DS2484 I2C to 1-Wire master, RJ-11 Connector, Sharp LS012B7DD01 LCD, 4 push buttons |
| Radomir Dopieralski | [PewPew FeatherWing](https://hackaday.io/project/21578-pewpew-featherwing) | Buttons and a LED matrix display for simple games |
| Dan Watson | [LoRaWAN FeatherWing](https://syncchannel.blogspot.com/2016/06/lorawan-featherwing-for-adafruit-feather.html) |  MicroChip RN2483/RN2903 LoRaWAN module |
| Dan Watson | [LoRa FeatherWing IOX](http://syncchannel.blogspot.com/2016/03/lora-featherwing-iox-for-adafruit.html) | RFM95/96(W) with MCP23008 8-bit I/O expander |
| Dan Cogliano | [e-Paper FeatherWing](https://danthegeek.com/2019/02/04/iot-calendar-creating-a-custom-featherwing/) | Add a Waveshare e-Paper display and two buttons |
| PatternAgents | [Agent-DRV2605](http://www.patternagents.com/store/index.html#!/FeatherWing-Haptic-DRV2605L/p/130591584/category=33456145) | TI DRV2605L Haptic Driver and ADI ADXL345 Accelerometer |
| PatternAgents | [Agent-DA7280](http://www.patternagents.com/store/index.html#!/FeatherWing-Haptic-DA7280/p/130591623/category=33456145) | DialogSemi DA7280L Haptic Driver and ADI ADXL345 Accelerometer |
| [Justin Nesselrotte](https://twitter.com/jnesselr/status/1097276091901726720) | [Snack Machine Controller](https://github.com/Jnesselr/Vending-Machine) | Wireless snack machine controller board |
| [MCCI](https://mcci.com/) | [Catena 4450](https://store.mcci.com/collections/lorawan-iot-and-the-things-network/products/catena-4450-lorawan-iot-device) | FRAM, BME-280 Sensor, lux sensor, I2C multiplexer, LoRaWAN |
| MCCI | [Catena 4460](https://store.mcci.com/collections/lorawan-iot-and-the-things-network/products/catena-4460-sensor-wing-w-bme680) | LoRaWAN 1.0/1.1, BME680 Sensor, lux sensor, FRAM, I2C Multiplexer |
| MCCI | [Catena 4470](https://store.mcci.com/collections/lorawan-iot-and-the-things-network/products/mcci-catena-4470-modbus-node-for-lorawan-technology) | LoRaWAN 1.0.2/1.1, RS-485, BME-280 Sensor, lux sensor, FRAM, SPI Flash |
| SparkFun | [ESP32 Thing Plus DMX to LED Shield](https://www.sparkfun.com/products/15110) | DMX board with XLR-3 and ArtNet jacks |
| SparkFun | [SparkFun Qwiic Shield for Thing Plus](https://www.sparkfun.com/products/16138) | Provides 4 Qwiic/STEMMA QT sockets |
| SparkFun | [SparkFun Thing Plus Dual-Port Logging Shield](https://www.sparkfun.com/products/19217) | SD Card for logging with USB-C access |
| Steiert Solutions | [Feather Qwiing](https://www.crowdsupply.com/steiert-solutions/qwiikit#qwiing) | Adds 2 Quiic connectors, MicroSD and locations for UEXT and SAO headers |
| JTinker | [6 Channel, 24 bit ADC Full Bridge Sensor FeatherWing](https://www.tindie.com/products/jtinker/6-ch-24-bit-full-bridge-sensor-featherwing/) | 6 Channel 24bit ADC FeatherWing for full bridge sensors |
| Sean Hodgins | [WIND Project Development Board](https://github.com/IdleHandsProject/wind_breakout) | Breakout board for Feather, sensor, and 18650 battery |
| John Sartzetakis | [Scale FeatherWing](https://gitlab.com/jousis/scale-featherwing) | RC Filter and LDO for Load Cell Excitation (ADS1232 24-bit ADC) |
| [Dan O'Shea (uXe)](https://twitter.com/uXeBoy) | [uXeBoy GBA Cartridge FeatherWing](https://community.arduboy.com/t/arduino-gameboy-cartridge/7057/90) | Lattice FPGA interface from a Feather to the GameBoy Advance. [Code](https://github.com/uXeBoy/GBArduboy). |
| [Pier42 Design](https://www.tindie.com/stores/pier42/) | [Watt-a-Live](https://www.tindie.com/products/pier42/watt-a-live-currentpowervoltage-monitor-sensor/) | INA209 Power Monitoring FeatherWing |
| Cedar Grove Studios | [Classic MIDI FeatherWing](https://github.com/CedarGroveStudios/Classic_MIDI_FeatherWing) | MIDI interface with provisions for DIN-5 and TRS Type B connectors |
| Cedar Grove Studios | [AD9833 FeatherWing](https://github.com/CedarGroveStudios/AD9833_FeatherWing) | Waveform Generator using the Analog Devices AD9833, 0 to 300 kHz, 0.1Hz resolution |
| Cedar Grove Studios | [AD9833 ADSR FeatherWing](https://github.com/CedarGroveStudios/AD9833_ADSR_FeatherWing) | Amplitude-controlled version of the AD9833 Waveform Generator FeatherWing, 0 to 300 kHz, 0.1Hz resolution, 8-bit amplitude control |
| Cedar Grove Studios | [Robot Friend FeatherWing](https://hackaday.io/project/168428-cedar-grove-robot-friend-featherwing) | Passively connect a PyBadge or PyGamer with a Crickit FeatherWing |
| Cedar Grove Studios | [RoverWing](https://github.com/CedarGroveStudios/RoverWing) | Stackable, LiPo-powered interface for connecting the Adafruit Trinket M0 to the Feather ecosystem |
| EmotiBit | [EmotiBit Sensor Module](https://www.emotibit.com/) | Multisensor FeatherWing compatible |
| Brian Lough | [Huzzah 32 Matrix FeatherWing](https://www.tindie.com/products/brianlough/huzzah-32-matrix-featherwing/) | Connect an Adafruit HUZZAH 32 Feather to an RGB LED matrix display |
| Joey Castillo | [The E-Book FeatherWing](https://github.com/joeycastillo/The-Open-Book) | e-paper display and optional peripherals in an eReader form factor |
| [Connected Future Labs](http://connectedfuturelabs.com/) | [Emotibit](https://www.emotibit.com/) | Multi-sensor board with SD Card |
| [Jared Wolff](https://www.jaredwolff.com) | [Air Quality Wing](https://store.groupgets.com/collections/frontpage/products/air-quality-wing-for-particle-mesh) | Supports the Honeywell HPMA115S0 dust sensor, AMS CCS811 eC02/TVOC and Silicon Labs Si7021 Temperature and Humidity Sensors  |
| [Loop Research](https://www.tindie.com/stores/loopresearch/) | [PowerWing](https://www.tindie.com/products/loopresearch/powerwing-6-36v-power-supply-featherwing/) | Can power Feather devices, 5V up to 1A, from 6-36V |
| Loop Research | [SwitchWing](https://www.tindie.com/products/loopresearch/switchwing-high-side-driver-featherwing-kit/) | Switch 5 to 28 volts at up to 20A |
| [Maker Buoy](https://www.makerbuoy.com/) | [Maker Buoy](https://www.makerbuoy.com/products-1) | PCB for an Adafruit Feather M0 Basic + Ultimate GPS and an Iridium radio for GPS tracking |
| [BORKA](https://www.tindie.com/stores/bokra/) | [Adapter for Adafruit Feather](https://www.tindie.com/products/bokra/adapter-for-adafruit-feather/) | Board combining a Feather footprint, a MikroBUS module connector, temperature sensor, STEMMA and power regulation |
| [Mikroe](https://www.mikroe.com/) | [Feather Click Shield](https://www.mikroe.com/blog/feather-click-shield) | Feather to dual mikroBUS Click board adapter |
| [Binho](https://binho.io/) | [Feather Interface Board](https://binho.io/collections/accessories/products/feather-interface-board) | Provides UART and Qwiic interfaces, primarily for using the Binho Multi-Protocol USB Host Adapter |
| sirmylesavery | [u-blox SAM-M8Q GPS Featherwing](https://hackaday.io/project/168430-u-blox-sam-m8q-gps-featherwing) | GPS FeatherWing using the ublox SAM-M8Q GPS module |
| [Maxim Integrated](https://www.maximintegrated.com/) | [MAX30101WING](https://www.maximintegrated.com/en/products/interface/sensor-interface/MAX30101WING.html) | MAX30101 pulse oximetry sensor development board |
| [Maxim Integrated](https://www.maximintegrated.com/) | [MAX86150](https://www.maximintegrated.com/en/products/interface/sensor-interface/MAX86150.html) | MAX86150 BioSensor Module development board |
| [Actinius](https://www.actinius.com/) | [Environmental Sensor FeatherWing](https://www.actinius.com/environmental-sensor-featherwing) | features the Bosch BME280, AMS CCS811, TI OPT3002 and SI SI7060 sensors. |
| PCBWay | [ATM90E26 FeatherWing](https://www.pcbway.com/project/gifts_detail/ATM90E26_FeatherWing.html) | ATMEL E9026 Energy monitor with power supply |
| [n°Garage](https://www.tindie.com/stores/ndgarage/) | [Hippo](https://www.tindie.com/products/ndgarage/hippo/) | A hippo PCB with twelve NeoPixel LEDs |
| AbleGamers | [Freedom Wing Adapter](https://www.youtube.com/watch?v=FgKNWc-EpHQ) | Connect a power wheelchair joystick to Feather and the Xbox Adaptive Controller |
| [Omron](https://www.omron.co.jp/ecb) | [2JCIE-EV01-FT1](https://www.omron.co.jp/ecb/sensor/evaluation-board/2jcie) | Temperature, humidity, ambient light, MEMS pressure/motion/microphone multisensor board for HUZZAH32 |
| Silicognition | [PoE FeatherWing](https://www.crowdsupply.com/silicognition/poe-featherwing) | Wiz5500 Ethernet plus 4W Power over Ethernet |
| [Glen Akins](https://twitter.com/bikerglen) | [DMX FeatherWing](https://bikerglen.com/blog/dmx-featherwing-light-controller/) | DMX 512 interface wing |
| José Miguel Sánchez García | [OrthoWing](https://github.com/jmi2k/OrthoWing) | A Feather-compatible keyboard, 5x12 Cherry MX layout |
| Thea Flowers | [Hostess FeatherWing](https://twitter.com/theavalkyrie/status/1261802769964363777?s=21) | USB Host with USB-A connector |
| Lex Kravitz | [Feather ULN2003 Stepper Wing](https://hackaday.io/project/173995-feather-uln2003-stepper-wing) | ULN2003 stepper motor driver |
| Philippe Cadic | [RPi to Feather Adapter](https://github.com/ccadic/RPI_Feather) | A Raspberry Pi header to Feather pinout adapter board |
| Solder Party | [Keyboard FeatherWing](https://www.tindie.com/products/arturo182/keyboard-featherwing-qwerty-keyboard-26-lcd/) | BlackBerry keyboard, 320x240 color LCD display, microSD, buttons |
| [DTRONIXS](https://www.tindie.com/stores/DTronixs/) | [Prototyping / Breadboard board for Adafruit Feather](https://zuzebox.wordpress.com/2020/08/30/a-prototyping-breadboard-board-for-adafruit-feather-modules/) | Prototyping: header, buttons, LEDs, breadboard area |
| David Bershadsky and Alexander Kirillov | [RoverWing](https://www.crowdsupply.com/alexander-kirillov/roverwing) | Robotics Wing similar to Crickit, handles 6-12 volt motors |
| [SK Pang](http://skpang.co.uk/catalog/) | [CAN-Bus FeatherWing for ESP32](http://skpang.co.uk/catalog/canbus-featherwing-for-esp32-p-1556.html) | CAN-Bus FeatherWing for an ESP32 Feather. Uses the SN65HVD231 CAN transceiver with PESD1CAN ESD protection |
| [Würth Elektronik](https://www.we-online.de/katalog/de/SENSOR_FEATHERWING) | [Sensor FeatherWing](https://github.com/WurthElektronik/FeatherWings/tree/main/SensorFeatherWing) | 4-sensor FeatherWing with temperature, humidity, absolute pressure, 3-axis acceleration sensors |
| [Würth Elektronik](https://www.we-online.de/katalog/de/THYONE-I_FEATHERWING) | [Thyone Wireless FeatherWing](https://github.com/WurthElektronik/FeatherWings/tree/main/ThyoneWirelessFeatherWing) | 2.4 GHz proprietary wireless connectivity with integrated secure element |
| [Würth Elektronik](https://www.we-online.de/catalog/de/CALYPSO_FEATHERWING) | [Calypso Wi-Fi FeatherWing](https://github.com/WurthElektronik/FeatherWings/tree/main/CalypsoWiFiFeatherWing) | 2.4 GHz WiFi connectivity with support for SNTP, HTTP(S), MQTT(S) and cloud connectivity |
| [Würth Elektronik](https://www.we-online.de/katalog/de/pm) | [MagI³C Power FeatherWing](https://github.com/WurthElektronik/FeatherWings/tree/main/MagI3CPowerFeatherWing) | 5 V and 3.3 V power supply with a range of industrial input voltages (5 V, 9 V, 12 V, 15 V, 18 V and 24 V) |
| [tinyledmatrix](https://twitter.com/tinyledmatrix)| [NeoPixel_HD Feather Wing](https://hackaday.io/project/168448-neopixelhd-feather-wing) | High density neoPixel RGB-Matrix using 198 neoPixels |
| Spudworks | [DynaFeather](https://www.tindie.com/products/spudworks/dynafeather/) | Connect to Dynamixel brand smart servo motors with power |
| [Glen Akins](https://twitter.com/bikerglen) | [Sushi FeatherWing](https://github.com/bikerglen/sushi-featherwing) | The Sushi FeatherWing is a board to inteface the Adafruit HUZZAH ESP32 Feather to the slim 640x48 LCDs found in the various dragon, wizard, and fairy magic wand toys. |
| Blues Wireless | [Feather Starter Kit](https://shop.blues.io/products/feather-starter-kit) | Feather to Quectel cellular modem, Integrated GPS and Accelerometer |

## Accessories

- [MCCI weatherproof commercial enclosure](http://mcci.io/model-4050-case) 
- [3D Printed Case for the Adafruit Feather](https://learn.adafruit.com/3d-printed-case-for-adafruit-feather/overview) - Adafruit tutorial for a 3D printed case.
- [MCCI Feather-box](https://www.shapeways.com/shops/mcci-reg-iot-enclosures) - confgurable Feather Enclosure, design by Mike Doell, listed on Shapeways.
- [AT Makers](https://www.thingiverse.com/thing:3212895) - Feather Snap Case (Thingiverse)
- [AdLab](https://www.thingiverse.com/thing:1367270) - Simple Feather Case (Thingiverse)
- [3D Printed Case for Keyboard Featherwing](https://www.thingiverse.com/thing:4726225) - by masterjoseph (Thingiverse)
- [Adafruit Feather Tripler Enclosure](https://www.thingiverse.com/thing:3147564) - by mohit (Thingiverse)
- [Adafruit Feather mountable case](https://www.thingiverse.com/thing:2591165) | - by cschmitz81 (Thingiverse)
- [Adafruit Huzzah Feather Case](https://www.thingiverse.com/thing:2627086) - by peeter123 (Thingiverse)
- [Adafruit Feather HUZZAH + Neopixel FeatherWing enclosure](https://www.thingiverse.com/thing:1509869) - by seajseven (Thingiverse)
- [Feather and 1200 mAh Feather Battery Pack](https://www.thingiverse.com/thing:1776743) - by Powernet19xx (Thingiverse)
- [Adafruit Feather ESP8266 / ESP32 cases](https://www.thingiverse.com/thing:2581394) - by keyglitch (Thingiverse)
- [Adafruit Featherbox](https://www.thingiverse.com/thing:2139358) - by pouyak (Thingiverse)
- [Tall Adafruit Feather Box Components](https://www.thingiverse.com/thing:2438577) - by rcolbert (Thingiverse)
- [Additional items on Thingiverse](https://www.thingiverse.com/search?q=Feather&dwh=175c7d2f63b0faf)

## News

- [Freedom Wing Adapter](https://blog.adafruit.com/2020/01/31/freedom-wing-adapter-adapter-allows-power-wheelchairs-to-control-an-xbox-ablegamers-at_makers-soeveryonecangame-feather/), Adafruit blog, January 31, 2020
- Freedom Wing interfaces wheelchair joysticks to Xbox - [Hackster.io](https://www.hackster.io/news/you-can-now-use-your-power-wheelchair-as-an-xbox-controller-0aa52acd82eb), [Engadget](https://www.engadget.com/2020/02/02/adapter-turns-wheelchair-into-xbox-controller/), [MAKE](https://makezine.com/2020/02/03/connect-power-wheel-chairs-directly-to-game-consoles-with-the-freedom-wing/)
- [The 2019 Take Flight with Feather Contest](https://hackaday.io/contest/168107-take-flight-with-feather) - sponsored by Hackaday, Digi-Key, and Adafruit which sought manufacturable boards in several categories. [Here are the winners]( https://hackaday.com/2020/01/22/winners-of-the-take-flight-with-feather-contest/).
- [Poll results: FEATHER wins Twitter poll for "form factor of choice"](https://twitter.com/xoseperez/status/1146327118302916609) - read more on the [Adafruit blog post here](https://blog.adafruit.com/2019/07/05/feather-form-factor-of-choice-in-twitter-poll-by-xoseperez-feather-adafruit/), July 4, 2019.
- [The next generation of low-cost, open-source oceanographic instruments is here! Meet the OpenCTD rev 2!](http://www.southernfriedscience.com/the-next-generation-of-low-cost-open-source-oceanographic-instruments-is-here-meet-the-openctd-rev-2/) - OpenCTD switches to Feather products for reliability and cost.
- [Tiny, Linux-driven Cortex-A5 SBC supports FeatherWing add-ons](http://linuxgizmos.com/tiny-linux-driven-cortex-a5-sbc-supports-featherwing-add-ons/) - by Eric Brown, LinuxGizmos.com, July 7, 2019.
- [Adafruit’s Feather nRF52840 Express Board and Developing with CircuitPython](https://blog.nordicsemi.com/getconnected/adafruits-feather-nrf52840-express-board-and-developing-with-circuitpython) - by John Leonard, the Nordic [Connected] blog, June 5, 2019
- ["...adopting Adafruit’s Feather as the next standard"](https://blog.hackster.io/a-sparkfun-feather-board-65cddf5b7a98) - Hackster article on Adafruit's Feather becoming the defacto standard as well as CircuitPython adoption.
- [The Adafruit Feather is a Thing](https://hackaday.com/2018/05/06/the-adafruit-feather-is-a-thing/) - Hackaday article on the Adafruit Feather ecosystem.
- [A Quick Rundown on Adafruit’s Feather Ecosystem](https://makezine.com/2016/11/02/a-quick-rundown-on-adafruits-feather-ecosystem/) - Make article on the Feather products.
- [Feather on the Adafruit blog](https://blog.adafruit.com/category/feather/) - Adafruit Blog posts discussing Feather.
- [Feather on Hackaday](https://hackaday.com/?s=feather) - Hackaday posts related to Feather.
- [Feather on MAKE](https://makezine.com/?s=feather) - Feather related content on MAKE.

## Art

- [Feather Art](https://www.dropbox.com/sh/w98kneh9skq581y/AAAWWp3WNwsdtUrUPna9Wehka?dl=0) - Adafruit art/images relating to Feather. Please email legal@adafruit.com for Adafruit art use on designs and in advertising. 

## Social

- [Adafruit Feather on Twitter, latest](https://twitter.com/search?f=tweets&vertical=default&q=adafruit%20feather) - Twitter posts tagged Adafruit Feather.
- [Feather videos on YouTube, latest](https://www.youtube.com/results?search_query=adafruit+feather&sp=CAI%253D) - YouTube posts tagged Adafruit Feather.
- [#AdafruitFeather tagged photos & videos on Instagram](https://www.instagram.com/explore/tags/adafruitfeather/) - Posts on Instagram tagged #AdafruitFeather.
- [Feather tagged on Reddit](https://www.reddit.com/search?q=adafruit%20feather) - Reddit posts relating to Adafruit Feather.
- [Feather on Hackaday.io](https://hackaday.io/search?term=Adafruit+Feather) - List of projects on hackaday.io
- [Feather on hackster.io](https://www.hackster.io/search?i=projects&q=Adafruit%20Feather) - Adafruit Feathere projects on hackster.io.
- [Feather on Instructables](https://www.instructables.com/howto/Adafruit+Feather/) - How-tos, guides, and more, using Feather on Autodesk's Instructables.

## Contributing

Contributions and suggestions are always welcome! Please make pull requests to modify Awesome Feather.

## License & Trademarks

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighbouring rights to this work.

Updated October 15, 2021
