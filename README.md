# simple_chassis_controller

## Installation

### Building from Source

#### Dependencies

- [Robot Operating System (ROS)](http://wiki.ros.org) (middleware for robotics),
- [rm_description](https://github.com/gdut-dynamic-x/rm_description)(module source)
- controller_interface
- forward_command_controller
- hardware_interface
- pluginlib

#### Building

To build from source, clone it from this repository into your catkin workspace and compile the package
using

	cd catkin_workspace/src
	git clone https://github.com/ZH970/simple_chassis_controller.git
	cd ../
	rosdep install --from-paths . --ignore-src
	catkin build

## Usage

Run the simulation and controller with:

	roslaunch simple_chassis_controller run_simulation_and_controller.launch

## Config files

Config file config

* **controllers.yaml**  Params of simple_chassis_controller and joint_state_controller.

## Launch files

* **run_simulation_and_controller.launch:** Hero chassis only simulation and simple chassis controller
.

[ROS]: http://www.ros.org
