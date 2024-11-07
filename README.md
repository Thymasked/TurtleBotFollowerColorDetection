# SnC 2024 Turtlebot following person repository

![Alt text](images/image_1.png) 
<img src="images/CPS035-01.webp" alt="Alt Text" width="300" height="200">

### Group members
- Daniel Nguyen
- Chad Mackinlay
- Yves Gayagay

### Brief
This is the git repository for the Turtlebot following someone that has a high-visiblity vest or visibility vest itself. It runs on ROS1 (melodic) and is connected to a turtlebot3 by UTS through a pre-made network.

### Functionality
The turtlebot will detect a certain colour in its camera where it will then try to centre its midplane towards the point that it has detected the colour. This is done by sending the appropriate twist command so that the turtlebot robot will eventually align itself towards the point of interest. The robot will constantly keep moving forward as of now (no gap detection yet) whilst its angular speed will move towards the POI. 

### Install

- [0] make sure you have the following pre-requisite
**turltebot (melodic)** :  https://emanual.robotis.com/docs/en/platform/turtlebot3/quick-start/#pc-setup
**git**                 :  https://git-scm.com/downloads/linux
**ROS1 (melodic)**      :  https://wiki.ros.org/melodic

- [1] go to your catkin_ws/src/ directory and clone the repo there
```
cd ~/catkin_ws/src
git clone https://github.com/Thymasked/TurtleBot3_HumanFollower.git
```

- [2] dev build your new package in your workspace
```
cd ~/catkin_ws
catkin_make
```

- [3] source your new package into the workspace
```
cd ~/catkin_ws
source devel/setup.bash
```

### Contact
if you have any questions or enquiries of this you can refer to our contact list:
- Daniel Nguyen   : daniel.nguyen-2@student.uts.edu.au
- Chad Mackinlay  : chad.d.mackinlay@student.uts.edu.au
- Yves Gayagay    : yves.b.gayagay@stduent.uts.edu.au
