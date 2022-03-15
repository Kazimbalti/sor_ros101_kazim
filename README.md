# sor_ros101_kazim
ROS: Zero to ROS course  

## This is the repository about ROS: Zero to ROS course on Udamy.
https://www.udemy.com/course/school-of-ros-zero-to-ros/

## This is the first assignment 01 (Cylinder weight) of Zero to ROS course
#### Here is the attached video of this assignment 01 (Cylinder weight calculation).
https://www.youtube.com/watch?v=kj2rGqjR42g&t=63s

To run this repository first create a catkin workspace
1. mkdir -p ~/catkin-ws/src
2. cd ~/catkin_ws/src
3. catkin_init_workspace
4. cd ~/catkin_ws
5. catkin_make 


## To clone this repository 
2. cd catkin_ws/src
2. git clone https://github.com/Kazimbalti/sor_ros101_kazim/
3. cd catkin_ws
4. catkin_make

## Open 5 terminals
### In first terminal
1. roslaunch ros_tutorial cylinder.launch

### second terminal
1. rostopic list
2. rostopic info /radius_sqaurred
3. rostopic info /weight
4. rosrun ros_tutorial cylinder_input.py

### 3rd ternial
1. rostopic echo /cylinder

### 4th terminal 
1. rostopic echo /weight

### 5th terminal
1. rosrun rqt_graph rqt_graph
2. rosrun rqt_topic rqt_topic
3. rqt

