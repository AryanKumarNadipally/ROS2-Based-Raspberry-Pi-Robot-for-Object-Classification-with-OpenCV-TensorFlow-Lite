# ROS2-Based Raspberry Pi Robot for Object Classification

This repository contains the code and documentation for a ROS2-based robotic system that utilizes a Raspberry Pi for real-time object classification. The project integrates OpenCV for image capture and TensorFlow Lite for object detection and classification.

## Project Overview

The goal of this project was to create a mobile robot capable of navigating an environment and identifying objects using a camera. The robot is controlled remotely using a joystick and communicates via WiFi using the ROS2 framework. The system demonstrates the practical application of machine learning algorithms in real-world robotics.

## Guided By

- Prof. Olin Hartin

## Team "ROSters"

- Aryan Kumar Nadipally
- Sai Shivani Lingampally
- Richard Gibbons
- Puthi Sravya
- Dhanush Hosuru Jayaramu

## Hardware Requirements

- Raspberry Pi 4 Model B
- 12V 5200mAh LiPo Battery
- Fuse and On/Off Switch
- 5V to 12V Buck Converters
- L298N Motor Driver
- 12V DC Motors
- Raspberry Pi Camera Module
- Xbox Joystick Controller
- HP Omen Laptop (Main Computer)

## Software Requirements

- Ubuntu 20.04 (both on the main computer and Raspberry Pi)
- ROS2 Foxy
- OpenCV Library
- TensorFlow Lite
- Visual Studio Code with SSH for remote work

## Directory Structure

```plaintext
.
├── src
│   ├── cmd_to_pwm_driver.py      # Motor control script
│   └── image_publisher.py        # Camera image capture script
├── launch
│   ├── RPi_bot.launch.py         # Launch file for the Raspberry Pi
│   └── surveillance_bot.launch.py  # Launch file for the main computer
├── docs
│   ├── Installation.md           # Installation instructions
│   └── UserManual.md             # User manual
├── models
│   └── ...                       # TensorFlow Lite model files
└── README.md
