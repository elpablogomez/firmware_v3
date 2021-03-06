[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![Build Status](https://travis-ci.com/epernia/firmware_v3.svg?branch=master)](https://travis-ci.com/epernia/firmware_v3) (Travis CI status)

# Embedded Systems development Firmware in C/C++ 

## IMPORTANT

**This environment is under construction!!**

**Always use the [released versions](../../../../releases) because in these all examples are tested and the API documentation is consistent. The master branch may contain inconsistencies because this environment is currently under development. See the Travis CI tag above to know the status of this repository.**

## About firmware_v3

**firmware_v3** is a makefile-based project that act as a framework for Embedded Systems firmware development in C/C++ language. It support toolchain, libraries and examples for several platforms.

## Supported boards

- [CIAA-NXP (LPC4337)](documentation/CIAA_Boards/NXP_LPC4337/CIAA-NXP/CIAA-NXP%20v1.0%20Board%20-%202019-01-04%20v3r0.pdf).
- [EDU-CIAA-NXP (LPC4337)](documentation/CIAA_Boards/NXP_LPC4337/EDU-CIAA-NXP/EDU-CIAA-NXP%20v1.1%20Board%20-%202019-01-03%20v5r0.pdf).

## Examples

[See examples](../firmware/examples/examples-en.md).

## Supported toolchains

- gcc-arm-none-eabi 

## Available libraries:

- CMSIS 5.4.0 (Core and DSP). [CMSIS_5 Repository](https://github.com/ARM-software/CMSIS_5).
- LPCOpen v3.02 [LPCOpen Software Development Platform LPC43XX NXP website](https://www.nxp.com/design/microcontrollers-developer-resources/lpcopen-libraries-and-examples/lpcopen-software-development-platform-lpc43xx:LPCOPEN-SOFTWARE-FOR-LPC43XX).
- LPCUSBlib. [LPCUSBlib documentation](http://67.222.144.123/lpcopen/v1.03/group___l_p_c_u_s_blib.html)
- sAPI v0.5.2. [sAPI API Reference (spanish)](../../libs/sapi/documentation/api_reference_es.md).
- Arduino (wiring). [Language Reference](https://www.arduino.cc/reference/en/).
- Elm-Chan FatFS R0.13b. [FatFS documentation](http://elm-chan.org/fsw/ff/00index_e.html). Generic FAT Filesystem module with support for SD Card (SSP) and Pendrive (USB MSD) disks.
- FreeRTOS Kernel V10.0.1. [FreeRTOS_Reference_Manual_V10.0.0.pdf](../../examples/c/freertos_book/FreeRTOS_Reference_Manual_V10.0.0.pdf).
- RKH 3.2.3 [RKH Reference Manual](https://vortexmakes.com/rkh/).

## Usage

[firmware_v3 usage](../firmware/usage/usage-en.md).



[Back to main README](../../README.md).