# Indoor Robot Workspace
For my xàm xí tutorial on how to build an indoor robot from scratch (and trash)

## How to download?
- Type in terminal
` git clone https://github.com/tranqkhue/indoor_robot_ws.git --recursive`\
**DO NOT** forget `recursive` as there are many submodules in this workspace 
- Then `cd` in to the workspace and `catkin_make` ;)

## How to run simulation?
Type in terminal 
```
export TURTLEBOT3_MODEL=waffle 
roslaunch turtlebot3_gazebo turtlebot3_house.launch
```
