Project Description

This project is a smart mini robot that uses Raspberry Pi and Arduino for obstacle detection, distance measurement, and manual control via Bluetooth. The robot detects obstacles in its surroundings using ultrasonic sensors and safely changes direction to continue moving. Additionally, it can be manually controlled via a smartphone using a Bluetooth module.

Hardware Used

Raspberry Pi (For motor control and Bluetooth connection)

Arduino Mega (To process sensor data and provide additional features)

HC-SR04 Ultrasonic Sensor (For obstacle detection and distance measurement)

L298N Motor Driver Module (For motor control)

DC Motors (For movement)

HC-05 Bluetooth Module (For smartphone connection)

12V Battery (As a power source)

Servo Motor (For special direction mechanisms)

Key Features

Obstacle Detection: Detects obstacles using ultrasonic sensors and measures distances.

Smart Direction Change: Avoids obstacles by steering in the most appropriate direction.

Manual and Autonomous Mode: Can be operated manually or in automatic mode.

Bluetooth Control: Allows controlling the robot's movements via a smartphone.

Servo Motor Usage: Provides a guiding mechanism for better movement.

Raspberry Pi Integration: Handles motor control and data processing via Raspberry Pi.

Setup and Execution

Connect the Hardware: Assemble all components as listed above.

Upload the Arduino Code: Upload the sketch_dec25a.ino file to the Arduino Mega.

Run Python Code on Raspberry Pi: Execute the motor-control.py file to control the motors.

Establish Bluetooth Connection: Pair with a smartphone via Bluetooth and test manual control.

Test Servo Motor: Ensure the servo motor's guiding mechanism functions correctly.

Code Explanation

sketch_dec25a.ino: Reads sensor data on Arduino Mega, calculates distances, and controls the servo motor.

motor-control.py: Handles motor operation and processes Bluetooth commands via Raspberry Pi.

Comparison

This project shares similarities with the "Arduino Obstacle Avoidance Robot Project" but offers the following additional advantages:

Allows manual control via Bluetooth.

Features an intelligent decision-making mechanism for direction change when an obstacle is detected.

Uses Raspberry Pi for motor control and data processing.

Provides precise navigation using a servo motor.


[![Python](https://img.shields.io/badge/python-3.12-000?style=for-the-badge&logo=python&logoColor=white&color=3776AB)](https://www.java.com/en/)
[![Arduino UNO](https://img.shields.io/badge/Arduino%20UNO-C70D2C?style=for-the-badge&logo=arduino&color=00878F)](https://www.arduino.cc/)
[![Raspberry Pi 4B](https://img.shields.io/badge/Raspberry%20Pi%204B-C70D2C?style=for-the-badge&logo=raspberrypi&color=A22846)](https://www.raspberrypi.com/)



Contributing

To contribute to this project, you can submit a pull request or open an issue.

License

This project is released under the MIT License.

