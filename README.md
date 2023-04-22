# WeCan-Tool

The main purpose of the project is to provide convenient and quick firmware upgrade and log collection functions for devices. Users can easily connect the device through a USB interface and upload new firmware, while real-time monitoring of the serial port output information for logging and analysis. In addition to that, the project also incorporates a command-line interface and Bootloader function, making device operation more efficient and flexible, even in cases where the device encounters issues, repairs, and maintenance can still be carried out.

------

The mainly consists of the following three parts:

1. **Command Line Interface**

   - Serial port tool

   - dfu-util

2. **Device upgrade tool**

   - DFU
   - CDC
   - Two Wire Communication
   - Protocol

3. **Target device**
   - Bootloader
   - Two Wire Communication
   - Protocol


------

**The Showcase**

[![WeCAN Tool](https://img.youtube.com/vi/AGaWB8fERRE/0.jpg)](https://www.youtube.com/watch?v=AGaWB8fERRE "WeCAN Tool")

This video demonstrates the process of updating firmware on an STM8S003 development board using the WeCan software and hardware tools.

------

**To-Do List**

1. **Command Line Interface**
   - [x] Windows
   - [ ] macOS
   - [ ] Ubuntu
2. **Device upgrade tool**
   1. [x] Prototype
   2. [ ] New PCBA
3. Target MCU Support List
   - [x] Stm8s
   - [ ] others

