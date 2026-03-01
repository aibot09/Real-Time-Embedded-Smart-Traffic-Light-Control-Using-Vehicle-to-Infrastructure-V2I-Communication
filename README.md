 Project Overview :

This project implements a real-time embedded smart traffic light control system using Vehicle-to-Infrastructure (V2I) communication between two ESP32 microcontrollers. The system simulates intelligent traffic management where a vehicle dynamically responds to traffic signal states.

 System Architecture :

The system consists of:

Infrastructure Unit (Master ESP32)

Controls Red, Yellow, and Green traffic signals

Detects vehicle presence using an IR sensor

Transmits real-time signal data to the vehicle

Vehicle Unit (Slave ESP32)

Receives traffic signal data wirelessly

Controls motor speed using PWM

Stops at Red

Slows down at Yellow

Moves at full speed at Green

Stops responding after crossing the intersection

Technologies Used :

ESP32 Microcontrollers

Embedded C / Arduino Framework

PWM Motor Control

IR Sensor for vehicle detection

Bluetooth-based V2I Communication

Li-ion Battery Power System

 Features :

Real-time signal-to-vehicle communication

Intelligent speed adjustment

Traffic-zone-based activation

Energy-efficient embedded design

Simulation of smart city traffic systems

 Objective :

To design and implement a scalable embedded system that demonstrates the practical working of Vehicle-to-Infrastructure (V2I) communication for intelligent traffic control applications.
