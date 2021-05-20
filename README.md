# Turtlebot_remap

## RBX1 Robot

**1. Create a workspace**

First, the following command must be write to create the *catkin_ws* workspace and a *src* folder inside:
> $ mkdir -p ~/catkin_ws/src

- Next, the following lines will enter the workspace and compile it, so new packages can be installed inside:
> $ cd catkin_ws
> $ catkin_make

**2. Install RBX1 Repository**

To install it directly on the operating system, this command must be executed from a terminal:
> $ sudo apt-get install ros-kinetic-rbx1

Note: This repository is used for  kinetic distribution, for another ROS distribution, check for the right version.

**3. Execute Launch**

.launch files are used to execute some nodes and configurations with a single line of code and usingle only one terminal:

> $ roscore

RBX1 package contains soma .launch files, the specific one will be used is fake_turtlebot.launch, wich can be found on catkin_ws/src/rbx1_bringup/launch and can be executed by this way:

> $ roslaunch rbx1_bringup fake_turtlebot.launch
