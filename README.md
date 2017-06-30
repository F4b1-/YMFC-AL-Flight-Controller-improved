# YMFC-AL-Flight-Controller-improved
The code extends the work of Joop Brokking (http://www.brokking.net/ymfc-al_main.html). This repository contains the flight controller of the arduino based self-leveling drone.

Upgrades
------

After building the quadrocopter I have added some minor upgrades:

4-digit display
------

There’s a 4 digit display now for showing the current flight time (or the seconds passed since connecting the battery that is). I am using this library that works for a wide variety of 4 segment displays since a lot of them are based on the TM1637 chip.
The display is only active when the motors are turned off to save precious computation time when the drone is up in the air. Besides, getting close enough to the flying quadrocopter so you could see the digits on the display isn’t something I would recommend anyway:wink:

Buzzer
------
I also addedd a buzzer to indicate that calibration is finished and the motors are ready to be started. It also starts beeping when the battery voltage drops below a certain threshold.

Head over to https://fabiangand.com/categories/drone/ for more.
