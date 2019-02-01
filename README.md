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
- [Feather Hardware](#feather)
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
| [Adafruit Feather 328P - Atmega328P 3.3V](https://www.adafruit.com/product/3458) | Protoboard area | 32KB | 2KB | None | 8 MHz | No | Yes |   |
| [Adafruit Feather 32u4 Basic Proto](https://www.adafruit.com/product/2771) | Built-in protoboard | 32 KB | 2 KB | None | 8 MHz | No | x  |    |
| [Adafruit Feather 32u4 Adalogger](https://www.adafruit.com/product/2795) | SD card support | 32 KB | 2 KB | None | 8 MHz | No |   |   |
| [Adafruit Feather 32u4 Bluefruit LE](https://www.adafruit.com/product/2829) | Bluetooth support | 32 KB | 2 KB | None | 8 MHz | No | Yes | BTLE |
| [Adafruit Feather HUZZAH with ESP8266](https://www.adafruit.com/product/2821) | WiFi support | 4 MB | 32 KB / 80 KB | None | 80 MHz | No |   | WiFi |
| [Adafruit Feather HUZZAH32 with ESP32](https://www.adafruit.com/product/3405) | WiFi support | 4 MB | 520 KB | None | 240 MHz | No | Yes | Wi-Fi / BTLE |
| [Adafruit Feather M0 Basic Proto](https://www.adafruit.com/product/2772) | Built-in protoboard | 256 KB | 32 KB | None |   |   |   |   |
| [Adafruit Feather M0 Adalogger](https://www.adafruit.com/product/2796) | SD card support | 256 KB | 32 KB | None | 48 MHz |   | Yes |   |
| [Adafruit Feather M0 Bluefruit LE](https://www.adafruit.com/product/2995) | Bluetooth support | 256 KB | 32 KB | None | 48 MHz | No | Yes | BTLE |
| [Adafruit Feather M0 WiFi](https://www.adafruit.com/product/3010) | ATWINC1500 Wi-Fi support | 256 KB | 32 KB | 48 MHz | None | Yes | No  | WiFi |
| [Adafruit Feather M0 WiFi with uFL](https://www.adafruit.com/product/3061) | WiFi support | 256 KB | 32 KB |   |   |   |   | WiFi |
| [Adafruit Feather 32u4 FONA](https://www.adafruit.com/product/3027) | cellular network support | 32 KB | 2 KB | None |   | No |   | Cellular |
| [Adafruit Feather STM32F205 with WICED](https://www.adafruit.com/product/3056) | WICED WiFi | 1024 KB | 128 KB | 2 MB | 120 MHz | No | Yes | WiFi |
| [Adafruit Feather 32u4 RFM69HCW (868/915 MHz)](https://www.adafruit.com/product/3078) | RF Radio Support | 2 KB | None |   |   |   |   | Radio |
| Adafruit Feather 32u4 RFM69HCW (433 MHz) | RF Radio Support | 32 KB | 2 KB | None |   |   |   | Radio |
| Adafruit Feather 32u4 32u4 RFM95W LoRa Radio (900 MHz) | RF Radio Support | 32 KB | 2 KB | None |   |   | LoRa |
| [Adafruit Feather nRF52 Bluefruit LE - nRF52832](https://www.adafruit.com/product/3406) | Bluetooth support | 512 KB | 64 KB | None | 64 MHz | No | Yes | BTLE |
| [Adafruit Feather nRF52832 Pro with myNewt Bootloader](https://www.adafruit.com/product/3574) | Bluetooth support |    |    | None |   |   |   | BTLE |
| [Adafruit Feather M4 Express](https://www.adafruit.com/product/3857)  | - |   |   |   |   |   |   |   |
| [Adafruit Feather nRF52840 Express](https://www.adafruit.com/product/4062) | Bluetooth support | 1 MB  | 256 KB | None | Yes | Yes |   | BTLE |
| [Adafruit HalloWing M0 Express](https://www.adafruit.com/product/3900) | 1.44" 128x128 display, sensors, amp | 256 KB | 32 KB | 8 MB | Yes | Yes |   |

### Feather Compatible Processor Boards

| Company | Board | Features |
|---|---|---|
| Particle | [Xenon](https://www.adafruit.com/product/3999) | nRF52840 with BLE and Mesh  |
| Particle | [Argon](https://www.adafruit.com/product/3997) | nRF52840 with Mesh and WiFi |
| Particle | [Boron LTE](https://www.adafruit.com/product/3998) | nRF52840 with Mesh and LTE Cellular Modem |
| SD4Projects | [MiniMega2560 Adapter](https://github.com/Sd4Projects/MiniMega2560_Adapter) | Adapt the MiniMega256 to Feather for Wing compatibility |
| Groboards  | [Giant Board](https://groboards.com/giant-board/) | ATSAMA5D27C-D1G Linux system in Feather form factor |
| Wilderness Labs | [Meadow](https://www.kickstarter.com/projects/meadow/meadow-full-stack-net-standard-iot-platform) | STM32F7 .NET with WiFi and Bluetooth |
| Maxim | [MAX32620FTHR](https://www.maximintegrated.com/en/products/microcontrollers/MAX32620FTHR.html) | Cortex M4 Darwin MCU |
| Maxim | [MAX32630FTHR](https://www.maximintegrated.com/en/products/microcontrollers/MAX32630FTHR.html) | Cortex M4F with PMIC |

## FeatherWings

| Name  | Features  |
|---|---|
| [FeatherWing Proto - Prototyping Add-on](https://www.adafruit.com/product/2884) | Singe Feather sized proto board, optional headers |
| [FeatherWing Doubler - Prototyping Add-on](https://www.adafruit.com/product/2890) | Two side-by-side Feather sockets |
| [FeatherWing Tripler Mini Kit - Prototyping Add-on](https://www.adafruit.com/product/3417)  | Three side-by-sidde feather sockets |
| [Assembled Terminal Block Breakout FeatherWing](https://www.adafruit.com/product/2890) | Fully assembled |
| [Adafruit Prop-Maker FeatherWing](https://www.adafruit.com/product/3988) | Multiple drivers for props |
| [Adafruit Ultimate GPS FeatherWing](https://www.adafruit.com/product/3133) | GPS receiver with battery backup |
| [Adafruit CRICKIT FeatherWing](https://www.adafruit.com/product/3343) | Multiple motor drivers, NeoPixel driver, amplifier, GPIO |
| [Adafruit Music Maker FeatherWing](https://www.adafruit.com/product/3357) | MicroSD Card, MP3 OGG WAV MIDI Synth Player |
| [Adafruit Music Maker FeatherWing with Amplifier](https://www.adafruit.com/product/3436) | MP3 OGG WAV MIDI Synth Player - Stereo 3W Amplifier |
| [Adafruit DC Motor + Stepper FeatherWing](https://www.adafruit.com/product/2927) | 4 DC Motors or 2 Steppers |
| [Adafruit INA219 FeatherWing](https://www.adafruit.com/product/3650) | Power monitoring |
| [Adafruit Power Relay FeatherWing](https://www.adafruit.com/product/3191) | Relay rated to 250V AC |
| [Adafruit Non-Latching Mini Relay](https://www.adafruit.com/product/2895) | Non-latching relat 250V AC |
| [Adafruit 8-Channel PWM or Servo FeatherWing Add-on](https://www.adafruit.com/product/2928) | 8 x 12-bit PWM outputs |
| [Adafruit LoRa Radio FeatherWing - RFM95W 433 MHz - RadioFruit](https://www.adafruit.com/product/3232) | LoRa Radio at 433 MHz |
| [Adafruit LoRa Radio FeatherWing - RFM95W 900 MHz - RadioFruit](https://www.adafruit.com/product/3231) | LoRa Radio at 900 MHz |
| [Adafruit Radio FeatherWing - RFM69HCW 433MHz - RadioFruit](https://www.adafruit.com/product/3230) | RFM69 radio at 433 MHz |
| [Adafruit Radio FeatherWing - RFM69HCW 900MHz - RadioFruit](https://www.adafruit.com/product/3229) | RFM69 radio at 900 MHz |
| [Adafruit FeatherWing OLED - Loose Headers](https://www.adafruit.com/product/2900) | 128x32 OLED Display |
| [Adafruit FeatherWing OLED - Soldered Headers](https://www.adafruit.com/product/3045) | 128x32 OLED Display |
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
| [Adafruit 4-Digit 7-Segment LED Matrix Display Driver](https://www.adafruit.com/product/3088) | Add a 4-digit 7-segment numeric display |
| [Adafruit 14-Segment Alphanumeric LED Driver](https://www.adafruit.com/product/3089) | Add a 4-digit 14-segment alphanumeric display |
| [Adafruit AMG8833 IR Thermal Camera FeatherWing](https://www.adafruit.com/product/3622) | Panasonic AMG8833 8x8 GridEYE sensor |
| [Adafruit Joy FeatherWing](https://www.adafruit.com/product/3632) | 2-axis joystick, 5 momentary button controller |
| [Adalogger FeatherWing - RTC + SD Add-on](https://www.adafruit.com/product/2922) | Adds a SD card slot and real-time clock |
| [Adafruit Teensy 3.x Feather Adapter](https://www.adafruit.com/product/3200) | Use Teensy 3 with all FeatherWings / Feather accessories |

### Feather Wings (non-Adafruit)

| Company | Board | Features |
|---|---|--------|
| Capable Robot Components | [SenseTemp](https://www.crowdsupply.com/capable-robot-components/sensetemp) | four-channel temperature sensor for instrumenting electronics |
| Particle | [Ethernet FeatherWing](https://www.adafruit.com/product/4003) | Ethernet with two Feather slots |
| Particle | [Particle Classic Adapter](https://store.particle.io/) | Use classic Photon accessories with Feather Footprint |
| davedarko | [USB Host FeatherWing](https://hackaday.io/project/161845-max3421e-featherwing) | USB Host add-on for MAX3421E |

## Accessories

- [3D Printed Case for the Adafruit Feather](https://learn.adafruit.com/3d-printed-case-for-adafruit-feather/overview) - Adafruit tutorial for a 3D printed case.

## News

- [Feather on the Adafruit blog](https://blog.adafruit.com/category/feather/) - Adafruit Blog posts discussing Feather.
- [The Adafruit Feather is a Thing](https://hackaday.com/2018/05/06/the-adafruit-feather-is-a-thing/) - Hackaday article on the Adafruit Feather ecosystem.
- [A Quick Rundown on Adafruit’s Feather Ecosystem](https://makezine.com/2016/11/02/a-quick-rundown-on-adafruits-feather-ecosystem/) - Make article on the Feather products.
- [Feather on Hackaday](https://hackaday.com/?s=feather) - Hackaday posts related to Feather.
- [Feather on MAKE](https://makezine.com/?s=feather) - Feather related content on MAKE.

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
