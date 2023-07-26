# Arduino Tilt Sensor Motor Control Project

This is an Arduino project that uses a tilt sensor and a motor to create a simple tilt-based control system. The project is designed to help beginners get started with Arduino and electronics.

## Materials

To complete this project, you will need:

- Arduino Uno board
- Breadboard
- Tilt sensor
- Motor (any DC motor)
- Motor driver (L293D)
- Jumper wires
- USB cable (for programming the Arduino)

## Wiring

The wiring diagram for the project is as follows:

```
Tilt Sensor:
- Connect one end of the tilt sensor to 5V on the Arduino
- Connect the other end of the tilt sensor to GND on the Arduino
- Connect the middle pin of the tilt sensor to digital pin 2 on the Arduino

Motor:
- Connect the positive lead of the motor to the positive terminal of the motor driver
- Connect the negative lead of the motor to the negative terminal of the motor driver
- Connect pins 1 and 9 of the motor driver to 5V on the Arduino
- Connect pins 4 and 5 of the motor driver to GND on the Arduino
- Connect pins 2 and 7 of the motor driver to digital pins 3 and 4 on the Arduino

```

## Code

The code for the project is written in the Arduino IDE. It reads the digital input from the tilt sensor and controls the motor using the motor driver. When the tilt sensor detects any tilt, the motor is turned on and moves in a specific direction.

## Usage

To use the project, simply upload the code to your Arduino Uno board and connect the circuit as described above. When you tilt the sensor, the motor will move in the specified direction.

## Credits

This project was inspired by [this tutorial on Tilt Sensors ↗](https://create.arduino.cc/projecthub/Anas20/tilt-sensor-f1921f) from Arduino Project Hub.
