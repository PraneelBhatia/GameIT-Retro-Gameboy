At the end of the project, we aspire to output a Gameboy which incorporates the use of certain hardware and software combinations which enable the user to engage in and play chosen game(s) on the Gameboy. 

The user can maneuver in the game with the help of buttons built into the PCB. The games are loaded onto or programmed into the microcontroller and can be displayed to the user by the display, where the user can also view his maneuvers and manipulation of the objects or characters in the game.

The chip which would be used for this product will be the ATTiny85 which is a small 8-bit microcontroller, possessing enough flash memory for the games which would be run by it. There are 3 push buttons on this PCB board, helping to control the small games which would be run on the OLED display with I2C communication. A buzzer also finds itself there to produce a noise upon certain actions in the game. The PCB is powered by a 3V button cell battery, which proves to be enough for the OLED display and the low power ATTiny85 chip. A slide switch is used to switch the circuit ON or OFF, and an LED which turns green upon turning the switch ON. 

An Arduino UNO is used to program the games onto the ATTiny85 chip.

Only one game will be able to be stored on one chip, hence opening the possibility to play multiple games if multiple ATTiny85 chips were to be used, hypothetically speaking. For this, a DIP slot would be used to enable inserting of and exchanging of different ATTiny chips.

Overall, the PCB will offer a compact, portable and well functioning Gameboy to the user, onto which they can easily start and play on the go.
