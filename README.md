# Vevor 3018 CNC controller

## Components

* STM32G030C8T6 cpu, 64MHz, 8k RAM, 64k FLASH
* HS24C08 serial EEPROM
* HR4988 DMOS stepper driver
* XL1410 switching regulator (3.3V ?)
* XL4015E1 switching regulator
* EL357N optocoupler for spindle FET drive(?)
* IRF540NS (international rectifier) GET (spindle PWM)
* Clock oscillator, 24MHz

## SWD pins

* PA13 -> SWIO, pin 35 on LQPF48
* PA14 -> SWCLK, pin 36 on LQPF48
* BOOT0 is multiplexed with PA14, pin 36
* NRST is pin 10 on LQFP48
