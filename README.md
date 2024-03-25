# Flame Detection System

## Description
This project is aimed at developing a real-time flame detection system using an 8051 microcontroller. The system detects fires when they are still small, offering early detection capabilities at a low cost. It utilizes flame sensors to detect the presence of smoke or high temperatures, triggering an alarm through the microcontroller.

## Hardware Requirements
- 8051 Microcontroller
- Flame Sensor
- LCD Display
- Resistors
- Capacitors
- Power Supply

## Software Requirements
- Keil µVision IDE

## Instructions
1. Connect the flame sensor to Pin P1.0 of the 8051 microcontroller.
2. Connect the LCD display to Port 3 of the microcontroller.
3. Ensure proper power supply to the system.
4. Compile and flash the provided code using Keil µVision IDE.
5. Upon detecting a flame, the LCD will display "Flame Detected".

## Code Overview
- The code initializes the LCD display and continuously monitors the flame sensor.
- If a flame is detected, it displays "Flame Detected" on the LCD.
- The `lcd_init()` function initializes the LCD.
- The `cmd()` and `dat()` functions send commands and data to the LCD respectively.
- The `lcd_string()` function displays a string on the LCD.
- The `delay()` function introduces a delay for proper LCD operation.

## Project Objectives
- Detect fires at an early stage.
- Develop a cost-effective real-time fire detection system.
- Improve accuracy and response time compared to conventional fire detectors.

## Note
Ensure proper connections and power supply for reliable operation of the system.


