# Autonomous-Wheeled-Mobile-Robot

## Overview
This repository contains a **ROS 2 Humble** package named `mobile_robot_description`. It provides a **URDF model** (in **xacro** format) of an autonomous wheeled mobile robot, along with a launch file to visualize the model in **RViz2**. While developed for **ROS 2 Humble**, it can work with other ROS 2 distributions (e.g., **Jazzy**) with minimal modifications.

## Features
- **Robot Description:** Defines the structure of the robot using URDF and xacro.
- **Visualization:** Includes a launch file for **RViz2** to display the model.
- **ROS 2 Compatibility:** Designed for **Humble**, but adaptable to **Jazzy** and other ROS 2 versions.

## Installation
### Prerequisites
- **ROS 2 Humble** (or another compatible ROS 2 distribution)
- `ros2 launch` and `xacro` installed

### Clone the Repository
```sh
mkdir -p mobile_robot_ws/src
cd ~/mobile_robot_ws/src
git clone https://github.com/newtonjeri/Autonomous-Wheeled-Mobile-Robot.git
```

### Cuild the package
```sh
cd ~/mobile_robot_ws/
colcon build
source install/setup.bash
```

## Usage
### Launch the URDF Model in RViz2
```sh
ros2 launch mobile_robot_description mobile_robot_display.launch.py
```
This will open **RViz2** with the robot model loaded.

## License
This project is licensed under the **MIT License**, allowing unrestricted use, including for **commercial and research purposes**.

## Contributions
Contributions are welcome! Feel free to submit pull requests or open issues.

## Contact
For inquiries or suggestions, reach out via GitHub Issues.

