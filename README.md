# Arduino Line Following Car

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![LPU](https://img.shields.io/badge/LPU-Lovely%20Professional%20University-blue)
![Arduino](https://img.shields.io/badge/Arduino-UNO-red)

A line following car built using an Uno Arduino, motor driver, and infrared sensor. The car is programmed to follow a black line on a white surface and adjust its movement using the sensor input.

### Working

The line-following car project works by using infrared sensors to detect the black line on a white surface. The sensors are placed underneath the car and are used to determine the position of the line relative to the car. The car is equipped with four motors, which are controlled by an Arduino board using the AFMotor library. The car is programmed to move forward when both sensors detect the line, turn left when only the left sensor detects the line, turn right when only the right sensor detects the line, and stop when neither sensor detects the line.

## Team Members
- Smriti Shukla
- Samyak Jain
- Vishal Sharma
- Sudhansu Khuntia

## Getting Started

### Prerequisites
- [Uno Arduino](https://robu.in/product/arduino-uno-r3-ch340g-atmega328p-devlopment-board/?gclid=CjwKCAjw6vyiBhB_EiwAQJRoppxCikF0lLMAPydPBW6sVyj_RQs-nk91zvwMX27XzsKl14r8TmvkNBoCZTkQAvD_BwE)
- [Motor driver](https://robocraze.com/products/l293d-motor-driver-shield-for-arduino?currency=INR&variant=40192528154777&https://robocraze.com/?utm_source=googleads&utm_medium=ppc&campaignid=20042620305&adgroupid=&keyword=&device=c&gad=1&gclid=CjwKCAjw6vyiBhB_EiwAQJRopj_Zpf4suSbOPXqpzy-MtHqK6Mjx-QfVkGNZ8AM_EFkg6VgvHjSfrBoC1SsQAvD_BwE)
- [2 Infrared sensors](https://roboway.in/shop/ir-sensor-module/?utm_source=Google+Shopping&utm_medium=cpc&utm_campaign=shopping+ads&srsltid=AR57-fBR8obalGmwbNqMsAm3Nj2Qtmnq7t0gbmd-OhH8KrGvgy2caO9BmQc)
- [2 Gear motors with wheels](https://robocraze.com/products/2-set-smart-car-robot-chassis-wheel?currency=INR&variant=40193475510425&https://robocraze.com/?utm_source=googleads&utm_medium=ppc&campaignid=20042620305&adgroupid=&keyword=&device=c&gad=1&gclid=CjwKCAjw6vyiBhB_EiwAQJRophVFJwt77Q6oyD-JuBOvtXLEX-o3AaRwwOVa-6e428-60YmbB_Fr6RoC2-0QAvD_BwE)
- [Arduino IDE](https://www.arduino.cc/en/software)
- [AFMotor library](https://downloads.arduino.cc/libraries/github.com/adafruit/Adafruit_Motor_Shield_library-1.0.1.zip)

## Circuit Diagram
![Circuit Diagram](https://github.com/Hershit-shukla/Line-Following-Car/blob/main/CircuitDiagram.PNG)

### Installation
1. Install the [AFMotor library](https://downloads.arduino.cc/libraries/github.com/adafruit/Adafruit_Motor_Shield_library-1.0.1.zip). Go to Sketch > Include Library > Add .ZIP Library > Select AF Motor ZIP file.
2. Connect the motor driver and infrared sensor to the Uno board.
3. Upload the code to the Uno board using the Arduino IDE.
4. Power the circuit using a 9V battery.
5. Place the line following car on a white surface with a black line.
6. The car will start moving along the line.

## Usage
- To control the line following car, upload the code to the Uno board using the Arduino IDE.
- Power the circuit using a 9V battery.
- Place the line following car on a white surface with a black line.
- The car will start moving along the line.

## Contributing
Contributions are always welcome! If you have any ideas or suggestions, feel free to open an issue or submit a pull request.

## License
Distributed under the MIT License. See LICENSE for more information.

## Acknowledgements
- [AFMotor Library](https://learn.adafruit.com/adafruit-motor-shield/library-reference)
- [Arduino IDE](https://www.arduino.cc/en/software)
- [Lovely Professional University](https://www.lpu.in/)
