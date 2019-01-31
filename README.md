<h1 align="center">
  <img width="853" src="https://github.com/adafruit/awesome-feather/blob/master/awesome_feather.png" alt="Awesome Feather"><br>Awesome Feather
</h1>

> A curated list of awesome Feather boards, add-ons (FeatherWings), guides, videos, libraries, software and resources.

The Adafruit [Feather](https://www.adafruit.com/category/943) are a complete line of development boards from [Adafruit](https://www,adafruit.com/) that are both standalone and stackable. They're able to be powered by LiPo batteries for on-the-go use or by their micro-USB plugs for stationary projects. Feathers are flexible, portable, and as light as their namesake. Feather Wings are stacking boards and add functionality and room for prototyping. At its core, the Adafruit Feather is a complete ecosystem of products - and the best way to get your project flying.

## Contents

- [Guides](#guides)
- [Community](#community)
- [Code](#code)
- [Frameworks](#frameworks)
- [Hardware](#hardware)
- [In the news](#news)
- [Art, logos, graphics](#art)
- [Social media](#social)
- [Contributing](#contributing)

## Guides

- [Introducing Adafruit Feather](https://learn.adafruit.com/adafruit-feather/) - An overview of Feather and the Feather ecosystem.
- [learn.adafruit.com Feather](https://learn.adafruit.com/category/feather) - Adafruit Learning Guides on Feather.

## Community

- [Adafruit CircuitPython Discord channel #help-with-projects](https://discordapp.com/channels/327254708534116352/330406777009209346) - 24/7 chat and support on projects with Adafruit gear.
- [Adafruit Feather Forums](https://forums.adafruit.com/viewforum.php?f=57) - The Adafruit discussion forum on Feather.

## Code

- [CircuitPython (latest)](https://github.com/adafruit/circuitpython/releases/latest)
- [CircuitPython 4.0.0 Beta](https://github.com/adafruit/circuitpython/releases/tag/4.0.0-beta.0) - [And the announcement](https://blog.adafruit.com/2019/01/23/circuitpython-4-0-0-beta-0-released/)
- [CircuitPython API Reference](http://circuitpython.readthedocs.io/en/latest/) - A list of functions and documentation available for CircuitPython.
- [CircuitPython GitHub Repository](https://github.com/adafruit/circuitpython) - The source code for CircuitPython on GitHub.
- [Adafruit CircuitPython Libraries](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/blob/master/circuitpython_library_list.md) - Current Adafruit CircuitPython Libraries. There are over 130+ libraries available.

## Frameworks

Feathers may be programmed in various languages which may vary by board. Here are language frameworks which may be used with specific Feather processor boards.

### CircuitPython

- [The Mu Editor, IDE, REPL, and plotter for CircuitPython](https://codewith.mu/) - The recommended Python editor for CircuitPython.
- [For developers, Mu: A Python Code Editor](http://mu.readthedocs.io/en/latest/) - The documentation for Mu.

## Feather Hardware

[Feather boards, Feather Wings and accessories](https://www.adafruit.com/category/943) - Complete listing of sensors, LCDs, displays, robotics, breakout boards, and more.

| Name | Features | Flash | RAM  | SPI Flash | Speed | CircuitPython | Arduino | Wireless |
|---|---|---|---|---|---|---|---|---|
| Adafruit Feather 328P - Atmega328P 3.3V | Protoboard area | 32KB | 2KB | None | 8 MHz | No | Yes |   |
| Adafruit Feather 32u4 Basic Proto | Built-in protoboard | 32 KB | 2 KB | None | 8 MHz | No | x  |    |
| Adafruit Feather 32u4 Adalogger | SD card support | 32 KB | 2 KB | None | 8 MHz | No |   |   |
| Adafruit Feather 32u4 Bluefruit LE | Bluetooth support | 32 KB | 2 KB | None | 8 MHz | No | Yes | BTLE |
| Adafruit Feather HUZZAH with ESP8266 | WiFi support | 4 MB | 32 KB / 80 KB | None | 80 MHz | No |   | WiFi |
| [Adafruit Feather HUZZAH32 with ESP32](https://www.adafruit.com/product/3405) | WiFi support | 4 MB | 520 KB | None } 240 MHz | No | Yes | Wi-Fi / BTLE |
| Adafruit Feather M0 Basic Proto | Built-in protoboard | 256 KB | 32 KB | None |   |   |   |   |
| Adafruit Feather M0 Adalogger | SD card support | 256 KB | 32 KB | None | 48 MHz |   | Yes |   |
| Adafruit Feather M0 Bluefruit LE | Bluetooth support | 256 KB | 32 KB | None | 48 MHz | No | Yes | BTLE |
| Adafruit Feather M0 WiFi | Wi-Fi support | 256 KB | 32 KB |   |   |   |   | WiFi |
| Adafruit Feather 32u4 FONA | cellular network support | 32 KB | 2 KB | None |   | No |   | Cellular |
| Adafruit Feather M0 WiFi with uFL | WiFi support | 256 KB | 32 KB |   |   |   |   | WiFi |
| Adafruit Feather STM32F205 with WICED | WICED WiFi | 1024 KB | 128 KB | 2 MB | 120 MHz | No | Yes | WiFi |
| Adafruit Feather 32u4 RFM69HCW (868/915 MHz) | RF Radio Support | 2 KB | None |   |   |   |   | Radio |
| Adafruit Feather 32u4 RFM69HCW (433 MHz) | RF Radio Support | 32 KB | 2 KB | None |   |   |   | Radio |
| Adafruit Feather 32u4 32u4 RFM95W LoRa Radio (900 MHz) | RF Radio Support | 32 KB | 2 KB | None |   |   | LoRa |
| Adafruit Feather nRF52 Bluefruit LE - nRF52832 | Bluetooth support | 512 KB | 64 KB | None | 64 MHz | No | Yes | BTLE |
| Adafruit Feather nRF52832 Pro with myNewt Bootloader | Bluetooth support |   |   |   |   |   |   | BTLE |
| Adafruit Feather M4 Express  | - |   |   |   |   |   |   |   |
| Adafruit Feather nRF52840 Express  | Bluetooth support |   |   |   |   |   |   | BTLE |

## Feather Compatible Processor Boards

| Company | Board | Features | Flash | RAM  | SPI Flash | Speed | CircuitPython | Arduino | Part Number |
|---|---|---|---|---|---|---|---|---|---:|
| Particle | Xenon | nRF52840 with BLE and Mesh  |   |   |   |   |   |   |   |   |
| Particle | Argon | nRF52840 with Mesh and WiFi |   |   |   |   |   |   |   |   |
| Particle | Boron LTE | nRF52840 with Mesh and LTE Cellular Modem |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |   |

## Feather Wings

| Name  | Features  |
|---|---|
| FeatherWing Doubler - Prototyping Add-on | Two side-by-side Feather sockets |
| FeatherWing Tripler Mini Kit - Prototyping Add-on  | Three side-by-sidde feather sockets |
| FeatherWing Proto - Prototyping Add-on | Singe Feather sized proto board, optional headers |
| Adafruit FeatherWing OLED - 128x32 OLED  | OLED Display |
| Adafruit Prop-Maker FeatherWing | Multiple drivers for props |
| Adafruit Ultimate GPS FeatherWing | GPS receiver with battery backup |
| Adafruit CRICKIT FeatherWing | Multiple motor drivers, NeoPixel driver, amplifier, GPIO |
| Adafruit TFT FeatherWing | LCD 480x320 3.5" with touchscreen |
| Music Maker FeatherWing w/ Amp | MP3 OGG WAV MIDI Synth Player - Stereo 3W Amplifier |
| Adafruit Music Maker FeatherWing | MP3 OGG WAV MIDI Synth Player |
|   |   |

### Feather Wings (non-Adafruit)

[SenseTemp](https://www.crowdsupply.com/capable-robot-components/sensetemp) - An accurate and flexible four-channel temperature sensor for instrumenting electronics.

## News

- [HackSpace Magazine - Issue 15](https://blog.adafruit.com/2019/01/24/issue-15-hackspace-magazine-circuitpython-hackspacemag-by-ben-everard-ben_everard-circuitpython-circuitpython-madewithmu/) - CircuitPython makes the cover on HackSpace Magazine with feature article, and projects.
- [CircuitPython in 2019](https://blog.adafruit.com/2018/12/17/what-do-you-want-from-circuitpython-in-2019-circuitpython2019-circuitpython/) - Community call for what's wanted and needed in CircuitPython for 2019.
- [CircuitPython in 2018](https://blog.adafruit.com/2018/01/29/circuitpython-in-2018/) - An article discussing the future directions for CircuitPython 2018 edition.
- [CircuitPython on the Adafruit.com/blog](https://blog.adafruit.com/category/circuitpython/) - Adafruit Blog posts discussing CircuitPython.
- [CircuitPython in MicroSolutions Digital Magazine](https://blog.adafruit.com/2018/08/27/circuitpython-in-microsolutions-digital-magazine-microchiptech-microchipmakes-circuitpython-adafruit/) - Microchip’s MicroSolutions, “Python on Microcontrollers” in Design Corner article. MicroSolutions is Microchip’s bi-monthly digital magazine.
- [CircuitPython Snakes its Way onto Adafruit Hardware](http://makezine.com/2017/08/11/circuitpython-snakes-way-adafruit-hardware/) - An article by MAKE on CircuitPython.
- [Adafruit Circuit Playground Express review](https://hackspace.raspberrypi.org/features/adafruit-circuit-playground-express-review) - Raspberry Pi reviews the Circuit Playground Express.
- [The Amp Hour #383](https://www.youtube.com/watch?v=d-Uw3YOf7dE) - An Interview with Scott Shawcroft.
- [CircuitPython on Hackaday](https://hackaday.com/?s=circuitpython) - Hackaday posts related to CircuitPython.
- [CircuitPython on MAKE](https://makezine.com/?s=circuitpython) - CircuitPython related content on MAKE.

## Art

- [Feather Art](https://www.adafruit.com/) - Adafruit art relating to Feather (TBD).

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

- [Adafruit CircuitPython boards](https://www.adafruit.com/circuitpython) - Adafruit Circuit Playground Express, Adafruit Feather M0 Express, Adafruit Feather M4 Express, Adafruit Feather nRF52840 Express, Adafruit GEMMA M0, Adafruit Grand Central M4 Express featuring the SAMD51, Adafruit HalloWing M0 Express, Adafruit ItsyBitsy M0, Adafruit ItsyBitsy M4, Adafruit METRO M0 Express, Adafruit Metro M4, Adafruit NeoTrellis M4, Adafruit Trinket M0.
- [Arduino](https://www.arduino.cc/) - Arduino MKR 1300, Arduino MKR ZERO, Arduino ZERO.
- [Electronic Cats](https://electroniccats.com/) - CatWAN USB Stick, Meow Meow.
- [MakerDiary](https://wiki.makerdiary.com/nrf52840-mdk-usb-dongle/) - nRF52840 Micro Dev Kit USB Dongle.
- [Mini Sam](https://www.minisam.cc/) - Mini SAM development board.
- [Nordic Semiconductor](https://www.nordicsemi.com/Products/Low-power-short-range-wireless/nRF52840) - nRF52840 DK board [PCA10056](http://infocenter.nordicsemi.com/index.jsp?topic=%2Fcom.nordic.infocenter.nrf52%2Fdita%2Fnrf52%2Fdevelopment%2Fnrf52840_pdk%2Fintro.html), nRF52840 dongle [PCA10059](http://infocenter.nordicsemi.com/index.jsp?topic=%2Fcom.nordic.infocenter.nrf52%2Fdita%2Fnrf52%2Fdevelopment%2Fnrf52840_dongle%2Fkit_hw_content.html).
- [Particle](https://www.particle.io/) - Particle Argon, Particle Boron, Particle Xenon.
- [SparkFun](https://www.sparkfun.com/) - SparkFun Pro nRF52840 Mini - Bluetooth Development Board, SparkFun SAMD21 Mini Breakout, SparkFun SAMD21 Dev Breakout. *Sparkfun LumiDrive LED Driver, and SparkFun RedBoard Turbo - SAMD21 Development Board, support CircuitPython but are not in releases until pull request is received to add.*
