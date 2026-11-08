# STM32 - 4 LEDs ON
STM32F407 Discovery Board
GPIOD Pins 12,13,14,15 ON using Register Level Programming

- MODER: 0x40020C00
- ODR: 0x40020C14
- RCC AHB1ENR: 0x40023830

No HAL library, direct register access.
