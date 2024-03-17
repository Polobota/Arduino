**Arduino Joystick Control for Two Servomotors**

### Description:
This Arduino sketch enables control of two servomotors using a joystick input. The X-axis of the joystick controls one servo motor, while the Y-axis controls the other servo motor. The servo positions are mapped based on the analog input values from the joystick, ranging from 0 to 180 degrees.

### Components Required:
- Arduino board (e.g., Uno)
- Joystick module
- Two servo motors
- Jumper wires

### Setup Instructions:
1. Connect the joystick module to the Arduino:
   - Connect the X-axis pin of the joystick to analog pin 0 (A0) of the Arduino.
   - Connect the Y-axis pin of the joystick to analog pin 1 (A1) of the Arduino.
   - Connect the VCC and GND pins of the joystick to the 5V and GND pins of the Arduino, respectively.

2. Connect the servo motors to the Arduino:
   - Attach one servo motor to digital pin 3 and the other servo motor to digital pin 4 of the Arduino.

3. Upload the provided Arduino sketch to the board.

4. Move the joystick along its X and Y axes to control the corresponding servo motors. The servo positions will adjust accordingly based on the joystick input values.

### Usage:
- This setup can be used for various applications requiring remote control of servo motors, such as robotic arms, camera gimbals, or pan-tilt mechanisms.
- Ensure the servo motors have sufficient power and are mounted securely to prevent unintended movements.

### License:
- This project is provided under the [MIT License](https://opensource.org/licenses/MIT). See the LICENSE file for details.

### Contributing:
- Contributions to enhance functionality, optimize code, or improve documentation are welcome. Fork the repository, make your changes, and submit a pull request.

### Feedback and Support:
- For questions, feedback, or support, please open an issue on GitHub or contact [David.havelka969@gmail.com).
