# parrot ardrone for Ros Melodic and Gazebo 9 update

This repository extends upon the limited functionalities and support of the older version of parrot ardrone repository that could be found [here](https://bitbucket.org/theconstructcore/parrot_ardrone/src/master/). This version and older versions suffered a discontinuity when ROS melodic was launched since it uses Gazebo 9 in which some dependencies and libraries were deprecated and replaced with others. One recurrent example was the depreciation of Gazebo math.hh library. 

That being said, I updated all the .cpp files that depended on Gazebo math.hh to be using [Ignition math](https://ignitionrobotics.org/api/math/4.0/index.html) instead.  Also, since this repo was originally built upon Gazebo 7 I had to update the scripts and .cpp filet to the new Gazebo API currently supported by [ROS Melodic](http://wiki.ros.org/melodic) and Gazebo 9. 

Tutorials on how to use this project:

- **[Wireless glove controller for parrot drones](https://github.com/MohamedKasem99/3D-drone-control-in-gazebo)**
- **[How to Launch the Parrot Drone Simulation Locally](https://www.theconstructsim.com/how-to-launch-drone-simulation-locally/)**

## Expected results



![image](README.assets/drunken_drone-2018-02-08_07.19.53.gif)