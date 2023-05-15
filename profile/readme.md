# MAPIR

The *MAchine Perception and Intelligent Robotics* group is a research group in the University of Málaga (*UMA*). We are an active research group with an interest in many topics related to autonomous robotics, including navigation, vision, olfaction, *etc*.

This organization page contains the repositories for many methods and algorithms we have published so far, as well as the tools and configuration files we require for internal use. You can browse all existing repositories, or use the links below to find things by topics:

## **WORK IN PROGRESS**
This list is still being updated!

## Main repositories
We offer four main repositories: "hw_drivers", "management",  "missions_pkg", and "utils". 

However, it must be noted that many of our contributions are hosted in particular repositories because they are result of a research paper and therefore independent of this organization. To ease this chaos, we show next the organization of each of those four main repositories, marking with [PR] those pkgs included as submodules and hosted independently in their own repositories.

 ## [hw_drivers](https://github.com/MAPIRlab/hw_drivers)
 A set of ROS pkgs implementing drivers to interact with sensors, actuators and mobile platforms.
     
 ## [management](https://github.com/MAPIRlab/management) 
 A set of ROS pkgs to manage/control/coordinate/execute highl level tasks of the robot.
  
 ## [missions](https://github.com/MAPIRlab/missions) 
 This is a single ROS pkg, with launch and configuration files likes maps and rviz files. Overall, it can be seen as the main launch file that will call/include the launch files of each pkg to be run (drivers, applications, etc.)

 ## [utils](https://github.com/MAPIRlab/utils) 
 Set of ROS pkgs implementing utilities for the robot like TTS, SST, topological mapping or odometry estimation. This is a highly heterogeneous repository, so users are encouraged to use COLCON_IGNORE to disable compilation of packages they do not need, exploiting the folder structure.

  - Communications
    - mqtt_bridge
    - Battery Manager
    - Robot status publisher
  - Odometry
    - [PR] [SRF](https://github.com/MAPIRlab/srf_laser_odometry)
    - [PR] [RF2O](https://github.com/MAPIRlab/rf2o_laser_odometry)
  - Mapping
    - [PR] [Sigma-FP](https://github.com/MAPIRlab/Sigma-FP)
    - [PR] [LTC Mapping](https://github.com/MAPIRlab/LTC-Mapping) 
  - Navigation
    - [Nav Assistant](https://github.com/MAPIRlab/navigation-assistant)
  - HRI
    - Web-HRI
    - [PR] [People detection](https://github.com/MAPIRlab/people_detection)
  - Coppelia
    - Coppelia-ros-pkg
    - Sim-ROS2-interface 


## Olfaction
A list of our contributions to the chemical sensing with mobile robots. This is not a repo itself, as all the components are hosted in their private repositories.
  #### Simulation Tools
  - [Gaden](https://github.com/MAPIRlab/gaden)
  - [GadenTools](https://github.com/MAPIRlab/GadenTools)
  - [Olfaction msgs](https://github.com/MAPIRlab/olfaction_msgs)
  - [Gaden-Unity](https://github.com/MAPIRlab/GADEN_Unity)
  
  #### Gas Distribution Mapping
  - [GMRF-wind](https://github.com/MAPIRlab/GMRF-wind)
  - [GMRF-gas](https://github.com/MAPIRlab/gmrf_gas_mapping)
  - [GDM scripts](https://github.com/MAPIRlab/gdm)
  - [Information-driven GDM](https://github.com/MAPIRlab/igdm)
  
  #### Gas Source Localization
  - [GSL](https://github.com/MAPIRlab/Gas-Source-Localization)
  

## Other tools/Apps
- [Alexa-ROS](https://github.com/MAPIRlab/Alexa-ROS)
- [UPGMPP-ROS](https://github.com/MAPIRlab/upgmpp_wrapper)
- [RL-ROBOT](https://github.com/MAPIRlab/rlrobot)



## Configured workspaces (Deprecated - See the [utils](https://github.com/MAPIRlab/utils) repository instead)
- [ROS sources for TFGs (robot)](https://github.com/MAPIRlab/tfg_ros_src)
- [ROS sources for TFGs (simulation)](https://github.com/MAPIRlab/tfg_ros_simulation)
- [Main ROS workspace](https://github.com/MAPIRlab/main)
