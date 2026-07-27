# Circuits

A collection of PCB designs & KiCad parts that aren't part of larger projects.

### [KicadCustomParts](https://github.com/TemuWolverine/Circuits/tree/master/KicadCustomParts)
- ESP32-S3-Supermini 
    * footprint
    * symbol

### [SparkleButton](https://github.com/TemuWolverine/Circuits/tree/master/SparkleBoard)
Designed as a WS2812b/"Neopixel" push button. Uses two (linked) tactile momentary switches and a WS2812b pixel. The idea is some push buttons can also act as status lights - think the power button on a console - but most off the shelf push buttons are a fixed LED colour.

Needs 5v (LED), LED signal, switch signal and GND.

3D enclosure to come soon.

### [SparkleBoard](https://github.com/TemuWolverine/Circuits/tree/master/SparkleButton)

WIP, USB-PD decoy/trigger and buck converter to provide two voltages. ie 12v for various parts of a project, and 5v for MCU.