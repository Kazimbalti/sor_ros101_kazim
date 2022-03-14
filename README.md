# sor_ros101_kazim
ROS: Zero to ROS course  

# This is the repository about ROS: Zero to ROS course on Udamy.
https://www.udemy.com/course/school-of-ros-zero-to-ros/

# This is the first assignment 01 (Cylinder weight) of Zero to ROS course
To run this repository first clone this repository 
1. git clone https://github.com/Kazimbalti/sor_ros101_kazim/
2. catkin_ws/src 
3. cd catkin_ws
4. catkin_make

# Open 5 terminals
## In first terminal
1. roslaunch ros_tutorial cylinder.launch

## second terminal
1. rostopic list
2. rostopic info /radius_sqaurred
3. rostopic info /weight
4. rosrun ros_tutorial cylinder_input.py

## 3rd ternial
1. rostopic echo /cylinder

## 4th terminal 
1. rostopic echo /weight

## 5th terminal
1. rosrun rqt_graph rqt_graph
2. rosrun rqt_topic rqt_topic
3. rqt

