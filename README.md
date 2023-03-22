# Quadruped Robot Control
## Description
Quadruped Robot Control is an Arduino-based program developed for a competition. It is designed to control a robot with four legs, using Three servos for each leg. The robot can walk, climb, rotate, and other, and it has ultrasonic sensors to detect obstacles.

## Hardware requirements
- Arduino Mega
- Four-legged robot with three servos for each leg
- Ultrasonic sensors
## Installation
1. Clone the repository or download the ZIP file.
2. Open the <b>'Quadruped Robot Control.ino'</b> file in the Arduino IDE.
3. Connect the Arduino Mega to your computer via USB.
4. Select "Arduino Mega" as the board type and choose the appropriate serial port.
5. Upload the code to the Arduino.
## Usage
1. Connect the ultrasonic sensors to the appropriate pins on the Arduino Mega.
2. Connect the servos to the appropriate pins on the Arduino Mega.
3. Connect the power supply to the servos and the Arduino Mega.
4. Turn on the power supply.
5. Press one of the three switches (<b>'sw1'</b>, <b>'sw2'</b>, or <b>'sw3'</b>) to select the operating mode.
6. The robot will perform the selected mode. The eight modes are:
- Mode 1: Walk
- Mode 2: climb_d
- Mode 3: climb_u
- Mode 4: climb_w
- Mode 5: roped
- Mode 6: ropeu
- Mode 7: rotatiol
- Mode 8: rotationr
## Customization
You can customize the delays for the rotation, climb, and walk by changing the values of the following variables:

- <b>'r'</b> and <b>'rt'</b>: Delay for rotation
- <b>'c'</b> and <b>'ct'</b>: Delay for climb
- <b>'w'</b> and <b>'wt'</b>: Delay for walk

You can also change the values of the servo positions in the following arrays:

- <b>'setting'</b>: Initial position of the servos
- <b>'standnew'</b>: Standing position of the servos
- <b>'climbu_1'</b> to <b>'climbu_7'</b>: Climbing positions of the servos
## License

This program is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
