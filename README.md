# Ruby_v1
This repo will hold the development and testing of the new Ruby design. Each component will be developed here and tested extensively.

## Getting Started

Ruby Robot is an Educational Robot designed and manufactured by Education.ai company and used by RoboBrain Academy as a teaching aid. The robot is already developed on the stm32f10x for v0. This repo is working on the developemnt and evolution of the Ruby robot to v1. Ruby Robot is used for teaching kids at the ages 5-12 years old concepts of coding in an interactive physical way with proper syllabus designed by high quality professionals in education and professors of top universities. For more details about Ruby Robot and the syallbus used use (https://robobrain.academy/)

Ruby Robot v1 will include the following features:
```
   1- Robot Control using RFID cards
   2- Better Speed Control of the Ruby Robot
   3- Music Interaction for coding activities
   4- Touch Screen to visualize and Edit code for the Ruby
   5- Line Following Capability
   6- Basic Vision Capabilities (Colour Detetcion, Face Detection)
   7- Coloured RGB LED interacting with ongoing educational activity
   8- Obstacle Avoidance from the Ruby front
   9- Upload kid's activity to our Cloud service for parent, and teacher follow-up and observation
  10- Analysis of the kid's activity using high quality machine learning algorithms to detect weaknesses and strengths of each student and apply adequate care accordingly. 
```

The components used are:
```
   1- Raspberry Pi zero
   2- 2 x DC Motors
   3- DC Motors Driver
   4- 2 x DC Motors Encoders
   5- RFID Reader
   6- Touch Screen
   7- Pi Camera
   8- 8 x Light Sensor
   9- RGB LED
  10- Sound Module
  11- Ultrasonic Sensor
```

### Prerequisites

Please ensure to have the raspberry pi up and running with Raspbian OS along with all the other equipments needed to power Raspberry pi e.g. mouse, keyboard, power source, etc... 
To instal Raspbain on your Pi please follow the instructions illustrated here (https://www.raspberrypi.org/documentation/setup/) and here (https://www.raspberrypi.org/documentation/installation/installing-images/README.md)

Each Module has a separate folder describint its specifications, usage and wiring needed for Ruby code. Follow Each Module README file for wiring and other info. 

Other Prerequisites: (Coming Soon)
```
  1- 
  2- 
```

### Wiring

Our wiring is based on the GPIO draw outs found in (https://www.raspberrypi.org/documentation/usage/gpio/README.md). The sound module is connected to adapter from Pi HDMI to 3.5 mm audio jack.3

| GPIO Number | Pi Pin Number| Module Connected | Module Pin Connected |
|    :---:    |    :---:     |------------------|----------------------|
|  2 |  3 | Light Sensor | Not Decided yet |
|  3 |  5 | Light Sensor | Not Decided yet |
|  4 |  7 | DC Motors Driver | Not Decided yet |
|  5 | 29 | Light Sensor | Not Decided yet |
|  6 | 31 | Light Sensor | Not Decided yet |
|  7 | 26 | Light Sensor | Not Decided yet |
|  8 | 24 | RFID Reader | Not Decided yet |
|  9 | 21 | RFID Reader | Not Decided yet |
| 10 | 19 | RFID Reader | Not Decided yet |
| 11 | 23 | RFID Reader | Not Decided yet |
| 12 | 32 | RGB LED | Not Decided yet |
| 13 | 33 | RGB LED | Not Decided yet |
| 14 |  8 | Touch Screen | Not Decided yet |
| 15 | 10 | Touch Screen | Not Decided yet |
| 16 | 36 | RGB LED | Not Decided yet |
| 17 | 11 | DC Motors Driver | Not Decided yet |
| 18 | 12 | Light Sensor | Not Decided yet |
| 19 | 35 | Light Sensor | Not Decided yet |
| 20 | 38 | Light Sensor | Not Decided yet |
| 21 | 40 | Ultrasonic Sensor | Not Decided yet |
| 22 | 15 | DC Motors Driver | Not Decided yet |
| 23 | 16 | DC Motors Encoders | Not Decided yet |
| 24 | 18 | DC Motors Encoders | Not Decided yet |
| 25 | 22 | RFID Reader | Not Decided yet |
| 26 | 37 | Ultrasonic Sensor | Not Decided yet |
| 27 | 13 | DC Motors Driver | Not Decided yet |
| I2C | 27 | DC Motors Encoders | Not Decided yet |
| I2C | 28 | DC Motors Encoders | Not Decided yet |

### Installing

To Run the code on your Ruby please follow the guidelines mentioned in Prerequisites section and the Wiring guidlines in Wiring Section. Then Clone this repo into your Raspberry Pi used on the Ruby.

Step by step explanation will be added soon. (Coming Soon)

A little demo will be issued once the Whole Development stack is finalized.

## Running the tests

Tests will be carried out on each module individually and then collectively. Ensuring the communication, robustness and stability of our robot system.

### Each module test

DC Motor Tests
```
python src/tests/PinsDefined.py
```

The tests will be added by time. (Coming Soon)

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Additional notes about how to deploy this on a live system. (Coming Soon)

## Contributing
Details on contributing and issuing pull requests. (Coming Soon)

## Authors

* **Abdelrahman Barghouth (Education.ai)** - *Initial work*

