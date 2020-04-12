# Robotics-Software-Engineer

<b>Project 1</b> - Build My World</br>
	Build a world in Gazebo and learn to make plugins to use your script to print to terminal "Welcome to Daniel's World!".</br>

<b>Project 2</b> - Go Chase it </br>
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
Running ball chaser robot - in an another terminal  
```
$ cd catkin_ws
$ source devel/setup.bash
$ roslaunch ball_chaser ball_chaser.launch
```
