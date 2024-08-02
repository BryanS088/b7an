WRO Competition 2024 future engineers Description This repository contains the code and documentation for a car robot built using parts sourced from Amazon and an Arduino kit. The project is developed for the World Robot Olympiad (WRO) competition, aiming to showcase the integration of electromechanical components controlled by Arduino modules.

Modules and Components

Arduino UNO The Arduino UNO serves as the main controller for the car robot. It interacts with various sensors and actuators to execute the robot's functionalities.

Motor Driver Module The motor driver module interfaces between the Arduino UNO and the motors. It regulates the power supplied to the motors based on the signals received from the Arduino, enabling precise control of movement.

Ultrasonic Sensor Module An ultrasonic sensor module is used for obstacle detection. It emits ultrasonic waves and measures the time taken for the waves to bounce back, determining the distance to obstacles in the robot's path.

Line Following Sensor Array The line following sensor array consists of infrared (IR) sensors that detect the contrast between the robot's surface and the line it is meant to follow. It provides feedback to the Arduino UNO for maintaining the robot's path.

Bluetooth Module A Bluetooth module enables wireless communication between the robot and external devices such as smartphones or laptops. It allows for remote control and data monitoring during the competition.

Building/Compiling/Uploading Process Hardware Setup Assemble the Car Robot: Follow the assembly instructions provided with the Arduino kit and additional components.

Connect Modules:

Connect the motor driver module to the motors and power supply. Attach the ultrasonic sensor and line following sensor array to appropriate digital and analog pins on the Arduino UNO. Integrate the Bluetooth module with the UART pins on the Arduino UNO. Software Setup Install Arduino IDE:

Download and install the Arduino IDE from arduino.cc. Download Repository:

Clone or download this repository to your local machine. Open Project in Arduino IDE:

Launch the Arduino IDE. Navigate to File > Open and select the .ino file from this repository. Upload Code to Arduino:

Connect the Arduino UNO to your computer using a USB cable. Select the correct board and port in the Arduino IDE (Tools > Board and Tools > Port). Click the "Upload" button in the Arduino IDE to compile and upload the code to the Arduino UNO. Verify Operation:

Once uploaded, disconnect the Arduino UNO from the computer. Power the robot using a suitable power source. Test the functionality of the robot, including motor control, obstacle detection, and line following using the provided interfaces (Bluetooth or autonomous mode). Contributors List names and roles of team members who contributed to this project. License Specify the license under which this code is distributed (e.g., MIT License). Acknowledgments Acknowledge any individuals or resources that contributed to your project's success.

