Arduino Waste Bin Status Monitor with Robotic Arm
### Description:
This Arduino sketch monitors the status of waste bins using ultrasonic distance sensors and controls a robotic arm to empty the bins when they are full. The sketch continuously checks the distance from the bins using ultrasonic sensors and activates the robotic arm to empty the bins when the distance falls below a specified threshold.


### Components Required:
- Arduino board (e.g., Uno)
- Ultrasonic distance sensors (HC-SR04)
- Servo motor
- Jumper wires

### Setup Instructions:
1. Connect the ultrasonic distance sensors to the Arduino:
   - Connect the trigger pin of the first sensor (Bin_1) to digital pin 10 and the echo pin to digital pin 11.
   - Connect the trigger pin of the second sensor (Bin_2) to digital pin 6 and the echo pin to digital pin 5.

2. Connect the servo motor for the robotic arm to digital pin 3 of the Arduino.

3. Define the depth of the waste bin (`bin_depth`) in the code. This value represents the maximum depth of waste in the bin before it needs to be emptied.

4. Upload the provided Arduino sketch to the board.

5. The sketch will continuously monitor the distance from the waste bins and activate the robotic arm to empty the bins when they are full.

### Usage:
- Ensure the ultrasonic sensors have a clear line of sight to accurately measure the distance to the waste bins.
- Adjust the threshold distance in the code (`<= 10`) to suit the depth of the waste bins and the desired level for emptying.
- Customize the delay durations as needed for the robotic arm movement and sensor readings.

### License:
- This project is provided under the [MIT License](https://opensource.org/licenses/MIT). See the LICENSE file for details.

### Contributing:
- Contributions to enhance functionality, optimize code, or improve documentation are welcome. Fork the repository, make your changes, and submit a pull request.

### Feedback and Support:
- For questions, feedback, or support, please open an issue on GitHub or contact (David.havelka969@gmail.com).
