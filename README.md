Welcome to the IoT Garbage Segregator and Bin Level Detector project! This repository contains the design, code, and simulation details for an intelligent waste management system. The project uses Arduino, a servo motor, an LCD display, and an ultrasonic sensor to automatically segregate waste and monitor the fill level of garbage bins in real-time.
Project Overview:
Objective:
The primary objective of this project is to design and simulate a smart garbage management system that can automatically segregate waste into various categories and monitor the fill level of garbage bins.
Materials:
Arduino Uno (or compatible board)
Servo Motor
LCD Display (16x2)
Ultrasonic Sensor (HC-SR04)
Jumper wires
Components:
Arduino Uno: The main microcontroller unit responsible for processing sensor data and controlling the servo motor and LCD display.
Servo Motor: Used to actuate the segregation mechanism to separate garbage into different categories.
LCD Display: Provides visual feedback such as system status and bin fill level.
Ultrasonic Sensor: Measures the distance to detect the fill level of the bins.
Working:
The system measures the distance from the ultrasonic sensor to the garbage and determines the fill level of the bin. Based on this distance, the servo motor actuates to segregate the waste into different categories, and the LCD display provides real-time feedback on the bin's fill level.
