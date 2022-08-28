# TP2_ROS_Esther_Adrien
## Installation
TURTLESIM BY Esther Adrien



Make a git clone of the repository.
```sh
git clone https://github.com/Adrien2305/TP2_ROS_Esther_Adrien.git
```
### Part 1
In order to run the turtlesim_node, turtle_teleop_key and rqt graph, we have to use the following command:

```sh
roscore
1. rosrun turtlesim turtlesim_node
2. rosrun turtlesim turtle_teleop_key
3. rqt_graph
```
### Part 2
```sh
1. catkin_create_pkg move_turtle rospy cpp std_msgs geometry_msgs sensor_msgs
2. roscore
3. rosrun move_turtle move.py
```
### Part 3
```sh
1. roscore
2. rosrun move_turtle turtle_circle.py 2 2 0.2
```
### Part 4
```sh
1. roscore
2. rosservice call /spawn 2 2 0.2 'newturtle'
3. rqt_graph
4. roslaunch move_turtle turtle.launch
```
