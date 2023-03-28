# MAPIR

The *MAchine Perception and Intelligent Robotics* group is a research group in the University of Málaga (*UMA*). We are an active research group with an interest in many topics related to autonomous robotics, including navigation, vision, olfaction, *etc*.

This organization page contains the repositories for many methods and algorithms we have published so far, as well as the tools and configuration files we require for internal use. you can browse all existing repositories, or use the links below to find things by topics:

## **WORK IN PROGRESS**
This list is still being updated!

## MAIN Workspaces
An attemp to organize our ROS pkgs according to their functionality. We offer four main worksapces/repositories, namely "hw_drivers", "management", "utils" and "missions_pkg". However, it must be noticed that many of our contributions are hosted in particular repositories because they are result of a research paper and therefore independent of this organization. To ease this caos, we show next the organization of each of those four main repositories, including links to other independent pkgs that can be considered part of them, but that are hosted independently in their own repositories.

- [hw_drivers](https://github.com/MAPIRlab) A set of ROS pkgs that implement drivers to interact with sensors, actuators and mobile platforms.
- [management](https://github.com/MAPIRlab) A set of ROS pkgs to manage/control/coordinate/execute highl level tasks of the robot.
- [missions_pkg](https://github.com/MAPIRlab) This is a single ROS pkg, with launch and configuration files likes maps and rviz files. Overall, it can be seen as the main launch file that will call/include the launch files of each pkg to be run (drivers, applications, etc.)
- [utils](https://github.com/MAPIRlab) ROS pkg implementing utilities for the robot like TTS, SST, topological mapping or odometry estimation. This is a highly heterogeneous repository, so we will try to keep it organized in a folder tree structure, so it can be easy "IGNORED" by ROS when we are not interested in some applications.

### Configured workspaces
- [ROS sources for TFGs (robot)](https://github.com/MAPIRlab/tfg_ros_src)
- [ROS sources for TFGs (simulation)](https://github.com/MAPIRlab/tfg_ros_simulation)
- [Main ROS workspace](https://github.com/MAPIRlab/main)



### Odometry
- [SRF](https://github.com/MAPIRlab/srf_laser_odometry)
- [RF2O](https://github.com/MAPIRlab/rf2o_laser_odometry)

### Navigation
- [Nav Assistant](https://github.com/MAPIRlab/navigation-assistant)

### Mapping
- [Sigma-FP](https://github.com/MAPIRlab/Sigma-FP)

### Vision and Semantics
- [LTC Mapping](https://github.com/MAPIRlab/LTC-Mapping) 
- [People detection](https://github.com/MAPIRlab/people_detection)

### Olfaction
- [Gaden](https://github.com/MAPIRlab/gaden)
- [GadenTools](https://github.com/MAPIRlab/GadenTools)
- [Olfaction msgs](https://github.com/MAPIRlab/olfaction_msgs)
- [Motas](https://github.com/MAPIRlab/Motas)
- [Gaden-Unity](https://github.com/MAPIRlab/GADEN_Unity)
  
  #### Gas Distribution Mapping
  - [GMRF-wind](https://github.com/MAPIRlab/GMRF-wind)
  - [GMRF-gas](https://github.com/MAPIRlab/gmrf_gas_mapping)
  - [GDM scripts](https://github.com/MAPIRlab/gdm)
  - [Information-driven GDM](https://github.com/MAPIRlab/igdm)
  
  #### Gas Source Localization
  - [GSL](https://github.com/MAPIRlab/Gas-Source-Localization)
  

### ROS Drivers
- [Olfaction drivers](https://github.com/MAPIRlab/hw_drivers_olfaction)

### Other tools
- [ROS2ARIA](https://github.com/MAPIRlab/ros2aria)
- [Alexa-ROS](https://github.com/MAPIRlab/Alexa-ROS)
- [UPGMPP-ROS](https://github.com/MAPIRlab/upgmpp_wrapper)
- [RL-ROBOT](https://github.com/MAPIRlab/rlrobot)
