# Automatic-Street-Light-System-Using-LDR-Arduino-UNO

## Project Overview

This project is an Automatic Street Light System built using Arduino UNO and an LDR (Light Dependent Resistor) sensor. The system automatically turns ON an LED during darkness and turns it OFF when light is detected.

## Components Used

* Arduino UNO
* LDR Sensor
* LED
* 220Ω Resistor
* 10kΩ Resistor
* Breadboard
* Jumper Wires

## Circuit Connections

### LDR Sensor

* One side → 5V
* Other side → A0
* 10kΩ resistor connected between A0 and GND

### LED

* Long leg (+) → Pin 10
* Short leg (-) → GND

## Working Principle

The LDR sensor detects the intensity of light in the surroundings. When the environment becomes dark, the sensor value increases and Arduino turns ON the LED automatically. When light is present, the LED turns OFF.

## Code Functionality

* Reads analog values from the LDR sensor using pin A0
* Displays sensor values in Serial Monitor
* Checks threshold condition
* Turns LED ON when LDR value is greater than 500
* Turns LED OFF when LDR value is below 500

## Applications

* Automatic street lighting systems
* Smart home lighting
* Energy saving systems
* Light-sensitive automation projects

## Output

* LED turns ON in darkness
* LED turns OFF in bright light

## Software Used

* Tinkercad Circuits
* Arduino IDE

## Conclusion

This project demonstrates basic sensor interfacing and automation using Arduino UNO and LDR sensor. It helps in understanding real-time embedded systems and energy-efficient lighting systems.
