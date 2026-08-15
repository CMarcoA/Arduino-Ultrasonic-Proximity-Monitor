# Arduino Proximity Sensing System

<p align="center">
  <img src="Arduino-SonarSensor.gif" 
  alt="Project Preview" width="700"/>
</p>

A small hardware/software project that uses an **Arduino** and an **ultrasonic sensor** to detect object distance in real time, then sends the sensor data to a **Processing** application for live visualization.

The project was built to explore how physical sensor input can be captured, transmitted, and turned into a simple interactive software interface.

## How It Works

1. The ultrasonic sensor measures the distance of nearby objects.
2. The Arduino reads and processes the sensor values.
3. Distance data is sent through **serial communication**.
4. A Processing application receives the data and visualizes the readings in real time.

This creates a simple end-to-end pipeline:

**Physical Sensor → Arduino → Serial Data → Processing Visualization**

## Features

* Real-time ultrasonic distance sensing
* Arduino-based hardware interfacing
* Live sensor data transmission
* Serial communication between hardware and software
* Processing-based visual feedback
* End-to-end integration of physical hardware with a desktop interface

## Technologies

**Arduino • Ultrasonic Sensor • Processing • Serial Communication • Embedded Hardware**

## What I Learned

This project gave me hands-on experience working beyond software alone. I learned how to connect and read physical sensors, handle real-time hardware data, communicate between an Arduino and another application, and translate sensor readings into useful visual feedback.

It also helped me better understand the relationship between **hardware inputs, embedded control, communication, and user-facing software**.

## Why I Built It

I wanted to build something tangible where the software directly responds to the physical environment. Instead of working only with simulated or stored data, this project uses live sensor readings and connects them to a visual interface in real time.
