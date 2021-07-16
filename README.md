# The following commands help we to create map by use Trutlebot3 :
## 1- Launch Gazebo by :
$ export TURTLEBOT3_MODEL=waffle_pi 
$ roslaunch turtlebot3_gazebo turtlebot3_world.launch
## 2- Launch SLAM by :
$ export TURTLEBOT3_MODEL=waffle_pi 
$ roslaunch turtlebot3_slam turtlebot3_slam.launch slam_methods:=gmapping
## 3- Remotely Control TurtleBot3 by :
$ roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
## 4- Save the Map by :
$ rosrun map_server map_saver -f ~/map

