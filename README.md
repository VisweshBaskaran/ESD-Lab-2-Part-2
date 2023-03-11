# ESD-Lab-2-Part-2

This code is written to be run on an STM32F411-E Discovery dev board, it can be used in any STM32F4 series of dev boards.

This code utilizes the green and red LEDs connected to GPIOD pin 12 and pin 14 and, the USER button connected GPIOA pin 0. With the help of a timer interrupt the red and green LEDs toggle on and off (red on, green off or red off, green on). When button press is detected, with the help of a flag variable the button state is stored till next button press and the LED sequence is changed, when button press is detected the red and green toggling stops and it stays in the state it was in the moment the button was pressed
