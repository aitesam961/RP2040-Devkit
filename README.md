




[![Issues](https://img.shields.io/github/issues/maitesam/OpenADSP)](https://github.com/maitesam/OpenADSP/actions)
[![Forks](https://img.shields.io/github/forks/maitesam/OpenADSP)](https://github.com/maitesam/OpenADSP/actions)
[![Stars](https://img.shields.io/github/stars/maitesam/OpenADSP)](https://github.com/maitesam/OpenADSP/actions)
[![License](https://img.shields.io/github/license/maitesam/OpenADSP)](https://github.com/maitesam/OpenADSP/blob/main/LICENSE)


![](https://github.com/maitesam/RP2040-Devkit/blob/main/Documents/ezgif.com-gif-maker.gif)

# RP2040-Devkit 
This is a development board embedding a very popular RP2040 Microcontroller developed by Raspberry Pi Foundation. The idea is to design a very basic set of hardware for people getting started with RP2040 who just need a custom Board other than RP2040 Pico or if they want to design their own.

The RP2040 is supported with both C/C++ and MicroPython cross-platform development environments, including easy access to runtime debugging. It has UF2 boot and floating-point routines baked into the chip. The built-in USB can act as both device and host. It has two symmetric cores and high internal bandwidth, making it useful for signal processing and video. While the chip has a large amount of internal RAM, the board includes an additional 16MB external QSPI flash chip to store program code.

More About RP2040 Could be found here: [RP2040](https://www.raspberrypi.com/documentation/microcontrollers/rp2040.html)

#### Some Highlights about RP2040 Before we go Ahead

<p align="center">
  <img width="400" src="https://www.raspberrypi.com/documentation/microcontrollers/images/rp2040_explanation.svg" alt="Material Bread logo">
</p>

## Features:
* [ ] RP2040 Processor
* [ ] Raspberry PI silicon MCU
* [ ] Capable of handling python Codes
* [ ] USB-C for power
* [ ] On-Board Serial Wire Debug
* [ ] GPIO pins extended to 2.54mm pitch Headers
* [ ] Convenient for soldering on Boards
* [ ] Easy To flash directly through VS or Arduino IDE
* [ ] Low Power consumption
* [ ] Cost effective design
* [ ] Small Size. Perfect for tight Fit projects

## What's Special About it!!

The RP2040 utilizes dual ARM Cortex-M0+ processors (up to 133MHz) and features:
- 264kB of embedded SRAM in six banks
- Six dedicated IO for SPI Flash (supporting XIP)

## Connectivity
- 30 multifunction GPIO
- Dedicated hardware for commonly used peripherals
- Programmable IO for extended peripheral support
- Four channel ADC with internal temperature sensor, 0.5 MSa/s, 12-bit conversion
- USB 1.1 Host/Device

> **Note:** The GPIO pins are muxed so you can reconfigure the pins for the digital interface of your choice! Check out the RP2040 datasheet for more information on the pins that are broken out on the board.



=== Software Development

https://datasheets.raspberrypi.com/pico/raspberry-pi-pico-c-sdk.pdf[Raspberry Pi Pico C/{cpp} SDK]:: Libraries and tools for C/C++ development on RP2040 microcontrollers

https://datasheets.raspberrypi.com/pico/raspberry-pi-pico-python-sdk.pdf[Raspberry Pi Pico Python SDK]:: A MicroPython environment for RP2040 microcontrollers

The API level Doxygen documentation for the Raspberry Pi Pico C/{cpp} SDK is also available https://rptl.io/pico-doxygen[as a micro-site].

## Contributions

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

> [NOTE]
If you are building applications with the C/C++ SDK and targeting boards other than the Raspberry Pi Pico, you will need to pass `-DPICO_BOARD=boardname` to CMake. Here `boardname` is the name of your board, e.g. for the Adafruit Feather RP2040 you should pass `-DPICO_BOARD=adafruit_feather_rp2040`. See the https://github.com/raspberrypi/pico-sdk/tree/master/src/boards[`boards/` directory] in the Pico SDK, and the https://forums.raspberrypi.com/viewtopic.php?f=147&t=304393[forums], for more information.

For More Information, refer to The [Datasheet](https://datasheets.raspberrypi.com/pico/pico-datasheet.pdf)


## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



