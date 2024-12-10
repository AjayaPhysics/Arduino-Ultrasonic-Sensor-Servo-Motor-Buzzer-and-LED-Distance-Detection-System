# Arduino-Ultrasonic-Sensor-Servo-Motor-Buzzer-and-LED-Distance-Detection-System
This project uses an HC-SR04 ultrasonic sensor to measure the distance of an object. If an object is detected within a specific range (e.g., 10 cm), the SG90 servo motor rotates to 90 degrees, the piezo buzzer beeps, and an LED lights up. This project is suitable for beginners learning how to use sensors and actuators with Arduino.
Features:
Distance Measurement: Detects objects within a specified range.
Visual and Audio Alerts: LED lights up and buzzer sounds when an object is detected.
Motion Control: Servo motor rotates based on distance thresholds.
Components and Connections:
Component	Arduino Pin	Connection Description
HC-SR04 Ultrasonic Sensor		
- VCC	5V	Power for the sensor.
- GND	GND	Ground connection.
- Trig	9	Sends the ultrasonic pulse.
- Echo	8	Receives the reflected pulse.
SG90 Servo Motor		
- VCC (Red Wire)	5V	Power for the servo.
- GND (Brown Wire)	GND	Ground connection.
- PWM (Orange Wire)	3	Signal pin to control the servo angle.
Piezo Buzzer		
- Positive Terminal	4	Pin to emit sound.
- Negative Terminal	GND	Ground connection.
LED		
- Long Leg (Anode)	5 (via 220-ohm resistor)	LED positive connection, current-limited through a resistor.
- Short Leg (Cathode)	GND	LED negative connection.
| **Component**         | **Arduino Pin**    | **Connection Description**                                    |
|------------------------|--------------------|--------------------------------------------------------------|
| **HC-SR04 Ultrasonic Sensor** |                |                                                              |
| - VCC                  | 5V                 | Power for the sensor.                                        |
| - GND                  | GND                | Ground connection.                                           |
| - Trig                 | 9                  | Sends the ultrasonic pulse.                                  |
| - Echo                 | 8                  | Receives the reflected pulse.                                |
| **SG90 Servo Motor**   |                    |                                                              |
| - VCC (Red Wire)       | 5V                 | Power for the servo.                                         |
| - GND (Brown Wire)     | GND                | Ground connection.                                           |
| - PWM (Orange Wire)    | 3                  | Signal pin to control the servo angle.                       |
| **Piezo Buzzer**       |                    |                                                              |
| - Positive Terminal    | 4                  | Pin to emit sound.                                           |
| - Negative Terminal    | GND                | Ground connection.                                           |
| **LED**                |                    |                                                              |
| - Long Leg (Anode)     | 5 (via 220-ohm resistor) | LED positive connection, current-limited through a resistor. |
| - Short Leg (Cathode)  | GND                | LED negative connection.                                     |
