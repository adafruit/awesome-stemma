<h1 align="center">
  <img width="853" src="https://github.com/adafruit/awesome-stemma/blob/master/awesome-stemma.jpg" alt="Awesome Stemma"><br>Awesome Stemma
</h1>

> A curated list of awesome Stemma connector resources including Stemma-equipped microcontrollers and breakout boards.

Adafruit Stemma is a collection of solderless digital/analog/power/I2C connection standards based on JST PH 3 and 4 pin connectors. For smaller footprint breakout boards, the JST SH 4 pin connector may be used for I2C connections.

Stemma equipped boards may be compatible with Seed Studio Grove connectors, SparkFun Qwiic connectors or DFRobot Gravity connectors. Cross-compatibility should be checked before interconnecting Stemma/Stemma QT boards with other manufacturer boards, as there could be connector incompatibilities or voltage issues (with Qwiic boards).

## Contents

- [Stemma Compatible and Stemma-like Systems](#Stemma-Compatible-and-Stemma-like-Systems)
- [Guides](#guides)
- [Compatibility](#compatability)
- [Stemma Hardware](#stemma-hardware)
- [Accessories](#accessories)
- [In the news](#news)
- [Art, logos, graphics](#art)
- [Social media](#social)
- [Contributing](#contributing)

## Stemma Compatible and Stemma-like Systems

- [Stemma / Stemma QT](https://www.adafruit.com/category/1005) (Adafruit.com)
- [Grove](https://www.seeedstudio.com/category/Grove-c-1003.html) (Seeedstudio.com)
- [Qwiic](https://www.sparkfun.com/qwiic) (SparkFun.com)
- [Gravity](https://www.dfrobot.com/index.php?route=page/gravity) (DFRobot.com)
- [easyC](https://e-radionica.com/en/easyc-system.html) (e-radionica.com)

## Guides

- [Adafruit STEMMA and STEMMA QT](https://learn.adafruit.com/introducing-adafruit-stemma-qt) - Adafruit Learning System primary guide on all things Stemma
- [Qwiic Tutorials](https://learn.sparkfun.com/tutorials/tags/qwiic) from SparkFun

## Compatibility

Stemma and Stemma QT have compatibility with similar connections used by manufacturers other than Adafruit. STEMMA attempts to be as cross-compatible as possible with both Grove, easyC and Gravity (compatible connectors & 3-5V power/logic). STEMMA QT is cross-compatible with Qwiic - STEMMA QT connector/cable is same as Qwiic. You can use STEMMA QT devices with Qwiic devices/controllers.

See the chart on the Adafruit Stemma/StemmaQT Guide for the latest compatibility charts between Stemma, Stemma QT, Grove, Qwiic, and Gravity connections.

## Stemma Hardware

### Adafruit Microcontroller Boards with Stemma

| Microcontroller Board | Stemma Connectors | Features |
|---|---|---|
| [Feather STM32F405 Express](https://www.adafruit.com/product/4382) | 1 Stemma QT | STM32F405 Cortex M4, 168MHz, 192KB RAM, 1MB Flash |
| [PyBadge](https://www.adafruit.com/product/4200) | 1x 4 pin Stemma, 2x 3 pin Stemma | ATSAMD51J19, 120MHz, 512KB of FLASH, 192KB RAM, 2MB Flash |
| [EdgeBadge](https://www.adafruit.com/product/4400) | 1x 4 pin Stemma, 2x 3 pin Stemma | ATSAMD51J19, 120MHz, 512KB of FLASH, 192KB RAM, 2MB Flash |
| [PyGamer](https://www.adafruit.com/product/4242) | 1x 4 pin Stemma, 2x 3 pin Stemma | ATSAMD51J19, 120MHz, 512KB of FLASH, 192KB RAM, 8MB Flash |
| [MONSTER M4SK](https://www.adafruit.com/product/4343) | 1x 4 pin Stemma, 2x 3 pin Stemma | ATSAMD51G19, 120MHz, 512KB of FLASH, 192KB RAM, 8MB Flash |
| [HalloWing M4 Express](https://www.adafruit.com/product/4300) | 1x 4 pin Stemma, 2x 3 pin Stemma | ATSAMD51J19, 120MHz, 512KB of FLASH, 192KB RAM, 8MB Flash |
| [NeoTrellis M4](https://www.adafruit.com/product/3938) | 1x 4 pin Stemma | ATSAMD51G19, 120MHz, 512KB of FLASH, 192KB RAM, 8MB Flash |

### Adafruit Sensors with Stemma

| Board | Stemma Connectors | Features |
|---|---|---|
| [AS7341](https://www.adafruit.com/product/4698) | 2 Stemma QT | 10-Channel Light / Color Sensor |
| [BH1750](https://www.adafruit.com/product/4681) | 2 Stemma QT | Light Sensor |
| [BME680](https://www.adafruit.com/product/3660) | 2 Stemma QT | Temperature, Humidity, Pressure and Gas Sensor |
| [BNO055](https://www.adafruit.com/product/4646) | 2 Stemma QT | 9-DOF Absolute Orientation IMU Fusion |
| [DPS310](https://www.adafruit.com/product/4494) | 2 Stemma QT | Precision Barometric Pressure / Altitude Sensor |
| [DS3502](https://www.adafruit.com/product/4286) | 2 Stemma QT | I2C Digital 10K Potentiometer |
| [H3LIS331](https://www.adafruit.com/product/4627) | 2 Stemma QT | Ultra High Range Triple-Axis Accelerometer |
| [ICM-20649](https://www.adafruit.com/product/4464) | 2 Stemma QT | Wide Range ±30g ±4000dps 6-DoF IMU |
| [ICM-209480](https://www.adafruit.com/product/4554) | 2 Stemma QT | TDK InvenSense 9-DoF IMU (MPU-9250 Upgrade) |
| [ISM330DHCX](https://www.adafruit.com/product/4502) | 2 Stemma QT | 6 DoF IMU - Accelerometer and Gyroscope |
| [ISM330DHCX + LIS3MDL](https://www.adafruit.com/product/4569) | 1 Stemma QT | High Precision 9-DoF IMU FeatherWing |
| [LIS2MDL](https://www.adafruit.com/product/4488) | 2 Stemma QT | Triple-axis Magnetometer |
| [LIS3MDL](https://www.adafruit.com/product/4479) | 2 Stemma QT | Triple-axis magnetometer compass module |
| [LPS22HB](https://www.adafruit.com/product/4633) |  2 Stemma QT | Pressure Sensor 260 to 1260 hPa, 24-bit, 75Hz |
| [LPS25HB](https://www.adafruit.com/product/4530) | 2 Stemma QT | Pressure Sensor 260-1260 hPa, 24-bit, 25Hz |
| [LPS33HW](https://www.adafruit.com/product/4414) | 2 Stemma QT | Water resistant pressure sensor |
| [LSM6DS33 + LIS3MDL](https://www.adafruit.com/product/4485) | 2 Stemma QT | 9 DoF IMU with accelerometer, gyroscope, magnetometer |
| [LSM6DSOX](https://www.adafruit.com/product/4438) | 2 Stemma QT | An I2C/SPI 6 DoF accelerometer and gyroscope |
| [LSM6DS33](https://www.adafruit.com/product/4480) | 2 Stemma QT | 6 DoF IMU accelerometer + gyroscope |
| [LSM9DS1](https://www.adafruit.com/product/4634) | 2 Stemma QT | 9-DOF sensor |
| [LSM303AGR](https://www.adafruit.com/product/4413) | 2 Stemma QT | Triple-axis accelerometer/magnetometer compass module |
| [MCP4728 Quad DAC](https://www.adafruit.com/product/4470) | 2 Stemma QT | Four 12-bit DACs with integrated EEPROM for settings |
| [MPU-6050](https://www.adafruit.com/product/3886) | 1 Stemma QT | An I2C 6 DoF accelerometer and gyroscope |
| [MS8607](https://www.adafruit.com/product/4716) | 2 Stemma QT | Pressure Humidity Temperature PHT Sensor |
| [MSA301](https://www.adafruit.com/product/4344) | 2 Stemma QT | Low Cost Triple Axis Accelerometer |
| [PA1010D Mini GPS](https://www.adafruit.com/product/4415) | 2 Stemma QT | GPS, GLONASS, GALILEO, QZSS receiver, 1"x1" |
| [PCT2075](https://www.adafruit.com/product/4369) | 2 Stemma QT | Temperature Sensor, LM75 upgrade |
| [PMSA003I](https://www.adafruit.com/product/4632) | 2 Stemma QT | Air Quality Breakout |
| [STEMMA Soil Sensor](https://www.adafruit.com/product/4026) | 1 Stemma | Capacitive I2C smart soil sensor |
| [TLV493D](https://www.adafruit.com/product/4366) | 2 Stemma QT | Triple-Axis magnetometer |
| [TMP235](https://www.adafruit.com/product/4686) | 1 Stemma | Analog Temperature Sensor |
| [TSL2561](https://www.adafruit.com/product/3611) | 1 Stemma  | Digital lux / light sensor |
| [VCNL4040](https://www.adafruit.com/product/4161) | 2 Stemma QT | Proximity and Lux sensor |
| [VL6180X](https://www.adafruit.com/product/3316) | 2 Stemma QT | Time of Flight Distance Ranging Sensor |

### Adafruit Devices

| Board | Stemma Connectors | Features |
|---|---|---|
| [Soil Sensor](https://www.adafruit.com/product/4026) | 1 Stemma | I2C capacitive moisture sensor |
| [NeoTrellis RGB Driver](https://www.adafruit.com/product/3954) | 1 Stemma | Provides a 4x4 matrix of RGB NeoPixel lit elastomer keys |
| [Stemma Speaker](https://www.adafruit.com/product/3885) | 1 Stemma | A class D audio amplifier and an oval speaker |
| [Mini Relay, Nonlatching](https://www.adafruit.com/product/4409) | 1 Stemma | A single pole/double throw relay up to 250V AC or DC |
| [NeoPixel Strip](https://www.adafruit.com/product/3919) | 1 Stemma | 60 pixels per meter density, 30 pixels 0.5 meter |
| [Tactile Push Buttons](https://www.adafruit.com/product/4431) | 1 Stemma each | Pack of 5 breakaway tactile buttons |
| [Micro Servo](https://www.adafruit.com/product/4326) | 1 Stemma | Standard micro servo with Stemma connector |
| [10K Analog Linear Potentiometer](https://www.adafruit.com/product/4493) | 1 Stemma | Wired Potentiometer Breakout Board with a 10K ohm linear taper |
| [DS1841 10K Digital Log Potentiometer](https://www.adafruit.com/product/4570) | 2 Stemma QT | Digital 10K ohm logarithmic taper potentiometer |
| [MLX90640 IR Thermal Camera](https://www.adafruit.com/product/4469) | 2 Stemma QT | A 24x32 array of IR thermal sensors, 110°x70° field of view |
| [TRUST M SLS 32AIA](https://www.adafruit.com/product/4351) | 2 Stemma QT | OPTIGA Trust M RSA 1K/2K + ECC256/384 Crypto |
| [ATECC608](https://www.adafruit.com/product/4314) | 2 Stemma QT | Crypto ECDH and AES-128, SHA-256/HMAC hash |
| [MCP2221A](https://www.adafruit.com/product/4471) | 1 Stemma QT | General Purpose USB to GPIO ADC I2C |
| [ST25DV16K](https://www.adafruit.com/product/4701) | 2 Stemma QT | I2C ISO/IEC 15693 (13.56MHz) RFID EEPROM |
| [PCF8591](https://www.adafruit.com/product/4648) | 2 Stemma QT | Quad 8-bit ADC + 8-bit DAC |

### Adafruit Displays

| Display | Stemma Connectors | Features |
|---|---|---|
| [OLED Graphics](https://www.adafruit.com/product/326) | 2 Stemma QT | 128x64, 0.96" mono |
| [Mini PiTFT](https://www.adafruit.com/product/4484) | 1 Stemma QT | 240x240 pixel, 1.3", Raspberry Pi connector |
| [Mini PiTFT](https://www.adafruit.com/product/4393) | 1 Stemma QT | 135x240 pixel, 1.14", Raspberry Pi connector |
| [TFT Gizmo](https://www.adafruit.com/product/4367) | 2x 3 pin Stemma | 240x240 pixel, 1.54", round for Circuit Playground |
| [E-Ink Gizmo](https://www.adafruit.com/product/4428) | 2x 3 pin Stemma | 152x152 pixel, 1.54", tricolor, round for Circuit Playground |
| [Monochrome E-Ink Bonnet](https://www.adafruit.com/product/4687) | 1 Stemma QT | 250x122 pixel, 2.13", mono eInk for Raspberry Pi |

### Processor to Stemma/Grove/Qwiic Breakout Boards

| Breakout | Connectors | Features |
|---|---|---|
| [Particle Grove FeatherWing](https://www.adafruit.com/product/4309) | 8 Grove | 3 Grove analog, 2 digital, 2 I2C, 1 UART |
| [Grove Shield FeatherWing](https://www.adafruit.com/product/4357) | 10 Grove | 4 Grove analog, 4 digital, 1 I2C, 1 UART |
| [SparkFun Qwiik / Stemma QT FeatherWing](https://www.adafruit.com/product/4515) | 4 Qwiic / Stemma QT | Feather processor form factor (FeatherWing) |
| [Binho Qwiic / Stemma QT Interface Board](https://www.adafruit.com/product/4462) | 4 Qwiic / Stemma QT | Binho ribbon cable to Qwiic/Stemma QT connections |
| [SparkFun Stemma QT / Qwiic Mux Breakout - 8 Channel](https://www.adafruit.com/product/4704) | 8 Qwiic / Stemma QT | Connect 8 devices to one address |
| [SparkFun Qwiic / STEMMA QT HAT for Raspberry Pi](https://www.adafruit.com/product/4688) | 4 Qwiic / Stemma QT | Raspberry Pi GPIO 4 port I2C breakout |

### Qwiic Boards from SparkFun

- [Qwiic Main Page](https://www.sparkfun.com/qwiic) on Sparkfun.com
- [One page list of Qwiic products from SparkFun](https://cdn.sparkfun.com/assets/home_page_posts/3/1/7/7/SparkFun_s_Qwiic_Ecosystem.pdf)

## Accessories

### Cables

Note: lengths are approximate

| Vendor | Connector type(s) | Length | Connector 1 | Connector 2 |
|---|---|---|---|---|
| Adafruit | [Stemma QT - Pin Header](https://www.adafruit.com/product/4397) | 150mm | 4-pin JST SH female | 4 Female pin header sockets |
| Adafruit | [Stemma QT - Alligator clips](https://www.adafruit.com/product/4398) | 150mm | 4-pin JST SH | 4 Alligator Clips |
| Adafruit | [Stemma QT - Stemma QT](https://www.adafruit.com/product/4210) | 100mm | 4-pin JST SH female | 4-pin JST SH female |
| Adafruit | [Stemma QT - Stemma QT](https://www.adafruit.com/product/4401) | 200mm | 4-pin JST SH female | 4-pin JST SH female |
| Adafruit | [Stemma - Stemma QT](https://www.adafruit.com/product/4424) | 200mm  | 4-pin JST PH female | 4-pin JST SH female |
| Adafruit | [Stemma - Stemma QT](https://www.adafruit.com/product/4424) | 200mm | 4-pin JST SH female | 4-pin JST SH female |
| Adafruit | [Stemma QT -  4-pin JST PH female](https://www.adafruit.com/product/4209) | 150mm | 4-pin JST-PH female | 0.1" male pin headers |
| Adafruit | [Stemma QT - 4 Female Pin Headers](https://www.adafruit.com/product/3950) | 200mm | 4-pin JST-PH female | 0.1" female pin headers |
| Adafruit | [Grove - Stemma QT/Qwiic](https://www.adafruit.com/product/4528) | 100mm | 4-pin JST-PH female | Grove 4 Pin |
| Adafruit | [Stemma 3 wire - leads](https://www.adafruit.com/product/4046) | 200mm | 3-pin JST PH male | 3 tinned wires |
| Adafruit | [Stemma 3 wire - male headers](https://www.adafruit.com/product/3893) | 200mm | 3-pin JST PH female | 0.1" male pin headers |
| Adafruit | [Stemma  - Alligator clips](https://www.adafruit.com/product/4030) | 195mm | 3-pin JST PH | 3 Alligator Clips |
| Adafruit | [Stemma  - Alligator clips](https://www.adafruit.com/product/4029) | 195mm | 4-pin JST PH | 4 Alligator Clips |
| Adafruit | [Stemma - Stemma](https://www.adafruit.com/product/3568) | 100mm | 4-pin JST PH female |  4-pin JST PH female |
| Adafruit | [Stemma - Stemma](https://www.adafruit.com/product/3568) | 150mm | 4-pin JST PH female |  4-pin JST PH female |
| Adafruit | [Stemma -  4 Male Pin Headers](https://www.adafruit.com/product/3955) | 200mm | 4-pin JST PH |  0.1" male pin headers |
| Adafruit | [Stemma -  4 Female Pin Headers](https://www.adafruit.com/product/3894) | 200mm | 4-pin JST PH |  0.1" female pin headers |
| Adafruit | [5-pin Arduino MKR - Stemma QT](https://www.adafruit.com/product/4483) | 100mm | 5-pin JST SJ | 4-pin JST SH |

### Breakouts

| Vendor | Item | Features |
|---|---|---|
| SparkFun | [Stemma QT / Qwiic Adapter](https://www.adafruit.com/product/4527) | 2 Qwiic / Stemma QT connectors, pinouts for SCL/SDA/3V/GND |
| SparkFun | [Stemma QT/Qwiic Shim for Raspberry Pi](https://www.adafruit.com/product/4463) |Press fit Raspberry Pi GPIO to Stemma QT/Qwiic connector |

### Contectors

| Vendor | Item | Quantity |
|---|---|---|
| Adafruit | [JST SH 4-pin right angle connector](https://www.adafruit.com/product/4208) | 10 pack |
| Adafruit | [JST SH 4-pin vertical connector](https://www.adafruit.com/product/4328) | 10 pack |
| Adafruit | [JST PH 4-pin horizontal connector](https://www.adafruit.com/product/4392) | 10 pack |
| Adafruit | [JST PH 3-pin vertical connector](https://www.adafruit.com/product/4389) | 10 pack |
| Adafruit | [JST PH 4-pin vertical connector](https://www.adafruit.com/product/4390) | 10 pack |
| Adafruit | [JST PH 3-pin horizontal connector](https://www.adafruit.com/product/4391) | 10 pack |
| Adafruit | [JST PH 0.2mm connector kit](https://www.adafruit.com/product/4422) | 220 pieces |

## News

- 2020-03-10 - [Welcome EasyC to the STEMMA/STEMMA QT/QWIIC/GROVE/GRAVITY connector ecosystem!](https://blog.adafruit.com/2020/03/01/welcome-easyc-to-the-stemma-stemma-qt-qwiic-grove-gravity-connector-ecosystem-sparkfun-seeedstudio-dfrobotcn-arduino-qwiic-grove-gravity-stemma-stemmaqt-easyc/), Adafruit Blog

## Art

- [Logos](https://www.dropbox.com/sh/7r8udc4s4pvwsno/AABL-BkGBWIufJwX5uKvxTNla?dl=0) from Adafruit
- [Qwiic Logos](https://cdn.sparkfun.com/assets/custom_pages/3/3/4/Qwiic-Registered-Logo.zip) from Sparkfun

## Social Media

- Twitter searches: [Stemma](https://twitter.com/search?q=stemma&src=typed_query&f=live), [StemmaQT](https://twitter.com/search?q=stemmaqt&src=typed_query&f=live), and [Qwiic](https://twitter.com/search?q=qwiic&src=typed_query&f=live).
- Instagram searches: [Stemma](https://www.instagram.com/explore/tags/stemma/), [StemmaQT](https://www.instagram.com/explore/tags/stemmaqt/), and [Qwiic](https://www.instagram.com/explore/tags/qwiic/).
- YouTube searches: 
[Stemma](https://www.youtube.com/results?search_query=%23stemma&sp=CAI%253D), [StemmaQT](https://www.youtube.com/results?search_query=%23stemmaqt), and [Qwiic](https://www.youtube.com/results?search_query=%23qwiic).
## Contributing

Contributions and suggestions are always welcome! Please make pull requests to modify Awesome Stemma.

## License & Trademarks

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the authors have waived all copyright and related or neighbouring rights to this work.
