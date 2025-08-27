# Light-Following/Avoiding-Robot
## Overview

This project was developed as part of my Embedded Systems course at university.
The robot was designed with multiple embedded functionalities in mind such as light-following, light-avoidance, Bluetooth control, LED indicators, and automatic power-off. It provided the perfect opportunity to practise and work on my hardware building skills as well as my programming software skills. 

![Light-Following Robot](https://github.com/rara1803/Light-Following-Robot/blob/9a71d2245ecf99b5bff46053b47c1884f2b2faaf/final%20result%20robot.jpeg)
## Features

1. Light-Following Mode:  
The robot continuously scans for the brightest light source using its LDR sensors.

2. Light-Avoidance Mode:  
By pressing the control button, the robot flips its behavior: instead of chasing light, it actively avoids it. To make the active mode clear, two LED lights were added: green when following light, red when avoiding it.

3. Inactivity Detection & Auto Shutdown:  
If by the time 40 seconds passed and no light wad detected, the robot transitions into a shutdown state. However before powering down, it sounds off a short buzzer alert, helping save battery while signaling the user.

4. Bluetooth-Based Manual Control:  
The robot can also be operated manually through a Bluetooth connection (HC-06 module). With the help of a simple terminal app on a smartphone, single-character commands can be sent to control its movement:

F → Forward

B → Backward

L → Left

R → Right

S → Stop

D → Dance mode (a programmed sequence of moves with lights as a fun addition) 

## Components Used:
##### —  Arduino Uno
##### —  Chasis and 4 wheels
##### — 4 DC Motors
##### — Breadboard
##### — JumperWires
##### — L298N Motor Driver
##### — Button
##### — Buzzer
##### — Hc-06 Bluetooth Module
##### — Green and Red LEDs
##### — Battery Holder
##### — 12V Batteries
##### — LDR Module
