# Awesome M5Stack Arduino

[日本語版はこちら / Japanese](README.ja.md)

Curated links for developing with [M5Stack](https://m5stack.com/) devices using Arduino (and PlatformIO where noted). For new projects, prefer **M5Unified + M5GFX**; the classic `M5Stack` library remains useful for older Core examples.

## Official

- [m5-docs](https://docs.m5stack.com/) — Official documentation (products, Arduino, APIs)
- [Arduino Board Manager](https://docs.m5stack.com/en/arduino/arduino_board) — Install boards with Additional Board Manager URL `https://static-cdn.m5stack.com/resource/arduino/package_m5stack_index.json`
- [Arduino Library Manager](https://docs.m5stack.com/en/arduino/arduino_library) — Install M5 driver libraries from the IDE
- [Getting started](https://docs.m5stack.com/en/start) — Overview of Arduino and other M5Stack toolchains
- [M5Unified Hello World](https://docs.m5stack.com/en/arduino/m5unified/helloworld) — First sketch with the unified API
- [PlatformIO + M5Unified](https://docs.m5stack.com/en/arduino/m5unified/intro_vscode) — VS Code / PlatformIO setup ([日本語](https://docs.m5stack.com/ja/arduino/m5unified/intro_vscode))
- [Tab5 Arduino guide](https://docs.m5stack.com/en/arduino/m5tab5/program) — Build & upload for the ESP32-P4 based Tab5 (select `M5Tab5`; needs M5Unified >= 0.2.23 and M5GFX >= 0.2.30)
- [M5Stack shop](https://shop.m5stack.com/) — Hardware catalog

## Toolchain

- [arduino-esp32](https://github.com/espressif/arduino-esp32) — Espressif's Arduino core that the M5Stack board package builds on (3.3.x stable; 4.0.0-RC1 based on ESP-IDF v6.1 is in pre-release)
- [pioarduino platform-espressif32](https://github.com/pioarduino/platform-espressif32) — Community PlatformIO platform that tracks arduino-esp32 3.x and newer chips (ESP32-P4/C5/C6)

## Libraries

- [M5Unified](https://github.com/m5stack/M5Unified) — Recommended unified driver for most M5 controllers (LCD, buttons, touch, audio, IMU, power, RTC); actively released, recent versions add Tab5 / CoreP4X / ToughC5 support ([releases](https://github.com/m5stack/M5Unified/releases))
- [M5GFX](https://github.com/m5stack/M5GFX) — Graphics library used by M5Unified (fonts, canvas, displays)
- [LovyanGFX](https://github.com/lovyan03/LovyanGFX) — Fast SPI/parallel LCD graphics library for ESP32 and more; the engine M5GFX is derived from, useful for non-M5 displays
- [M5Stack (legacy)](https://github.com/m5stack/M5Stack) — Classic Arduino library for M5Stack Core / Basic / Gray / Fire
- [M5UnitUnified](https://github.com/m5stack/M5UnitUnified) — Unified drivers for Unit-series peripherals
- [M5Cardputer](https://github.com/m5stack/M5Cardputer) — Board library (keyboard and more) for the Cardputer, built on M5Unified
- [TFT_eSPI](https://github.com/Bodmer/TFT_eSPI) — Arduino and PlatformIO TFT library optimised for STM32, ESP8266, ESP32, and RP2040

## Examples

- [M5Unified examples](https://github.com/m5stack/M5Unified/tree/master/examples) — Basic and Advanced sketches (display, button, touch, speaker, mic, IMU, RTC)
- [M5GFX examples](https://github.com/m5stack/M5GFX/tree/master/examples) — Graphics demos
- [M5Stack library examples](https://github.com/m5stack/M5Stack/tree/master/examples) — Legacy Core examples (Basics, Modules, and more)

## Hardware & schematics

- [M5-Schematic](https://github.com/m5stack/M5-Schematic) — Schematics for Cores, Modules, and Units (archived, still useful)
- [M5 Core Basic schematic (2017)](https://github.com/m5stack/M5-Schematic/blob/master/Core/Basic/M5-Core-Schematic(20171206).pdf) — Original Core/Basic PDF
- [Basic product docs](https://docs.m5stack.com/en/core/basic) — Pin maps and current schematic links on m5-docs

## Community

- [M5Stack Community Forum](https://community.m5stack.com/) — Official forum (Arduino under Software)
- [日本語フォーラム](https://community.m5stack.com/category/14/%E6%97%A5%E6%9C%AC%E8%AA%9E%E3%83%95%E3%82%A9%E3%83%BC%E3%83%A0) — Japanese community section
- [m5stack on GitHub](https://github.com/m5stack) — Official organization repositories
