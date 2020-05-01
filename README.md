# Robotics-Software-Engineer

<b>Project 1 - Build My World</b></br>
	Built a world in Gazebo and learn to make plugins to use your script to print to terminal "Welcome to Daniel's World!".</br>

<b>Project 2 - Go Chase it</b></br>
In this project the robot chases the white ball when it is in view. 

Launching myworld from Gazebo
```
$ gazebo path/to/the/file/myworld.world
```  
Launching Gazebo ros
```
$ source devel/setup.bash
$ roslaunch my_robot world.launch
```
Running ball chaser robot in an another terminal  
```
$ cd catkin_ws
$ source devel/setup.bash
$ roslaunch ball_chaser ball_chaser.launch
```
<b>Project 3 - Where Am I</b></br>
In this project it focuses on Adaptive Monte Carlo Localization (AMCL) for localizing the robot in the pgm map.  Using particle cloud you can see where the robot is inside the map.

To run it use the following commands in the terminal</br>
```
$ cd to/your/package/here/
$ source devel/setup.bash
$ roslaunch my_robot world.launch
```
In the second terminal</br>
```
$ cd to/your/package/here/
$ source devel/setup.bash
$ roslaunch my_robot amcl.launch
```
To control the robot inside Rviz open another terminal</br>
```
$ cd to/your/package/here/
$ source devel/setup.bash
$ rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```
