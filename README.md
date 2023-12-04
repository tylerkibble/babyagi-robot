# BabyAGI ROSMASTER X3 PLUS Controller

This repository contains a ROS package that allows you to control the ROSMASTER X3 PLUS robot using BabyAGI.

## Features

- Interfaces with BabyAGI to process data from the robot.
- Controls the robot's movement using the processed data.
- Can be used with Jetson NANO 4GB/Xavier NX/TX2 NX/Raspberry Pi 4B.

## Prerequisites

- A ROS environment set up on your Jetson NANO 4GB/Xavier NX/TX2 NX/Raspberry Pi 4B.
- The BabyAGI package installed in your ROS environment.

## Installation

1. Clone this repository into your ROS workspace:

bash cd ~/catkin_ws/src git clone https://github.com/YourUsername/BabyAGI_ROSMASTER_X3_PLUS_Controller.git


2. Build your workspace:

bash cd ~/catkin_ws catkin_make


3. Source your workspace:

bash source ~/catkin_ws/devel/setup.bash


## Usage

1. Run the ROS node:

bash rosrun babyagi_controller babyagi_controller.py


## Contributing

We welcome contributions to this project. Please feel free to submit a pull request or open an issue if you encounter any problems.

## License

This project is licensed under the MIT License.
