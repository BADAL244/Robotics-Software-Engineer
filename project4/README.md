
# Map-My-World

Project 4 Map My World you create a 2d occupancy grid and 3d Octomap from the simulated enviroment using RTAB-map package and the robot from the previous projects.


Initialize the world first
```
cd path/to/your/folder
source devel/setup.bash
roslaunch <yourprojectfolder> world.launch
```
Next to control the robot in the enviroment open another terminal
```
cd path/to/your/folder
source devel/setup.bash
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```
Finally open another terminal
```
cd path/to/your/folder
source devel/setup.bash
roslaunch <yourpackagehere> mapping.launch
```
