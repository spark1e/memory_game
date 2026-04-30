# memory_game
A memory sequence game implemented on the STM32 Nucleo-L476RG. The system displays an LED pattern that the user must reproduce via push buttons. Features include a buzzer for audio feedback, an LCD for score display, and a top-5 leaderboard stored in flash memory for persistence across power cycles.


Lucia:
- Sound with the buzzer
- Potentiometer reading with ADC

Cesar:
- Hardware on the breadboard
- Buttons debouncing
- Interrupts for buttons and LED on/off in the Handler

Nikita:
- Score on the 7-seg display
- Randomly generated Sequence
