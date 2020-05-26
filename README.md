# Udacity-Robotics-TurtleBotGazebo


Packages to install:
sudo apt install ros-melodic-kobuki-msgs 
sudo apt install ros-melodic-image-geometry
sudo apt install ros-melodic-depth-image-proc
sudo apt install ros-melodic-joy
sudo apt install ros-melodic-depthimage-to-laserscan
sudo apt install ros-melodic-yocs-cmd-vel-mux





launch tutrlebot gazebo:
roslaunch turtlebot_gazebo turtlebot_world.launch

roslaunch .../launch_ekf.launch

roslaunch odom_to_trajectory create_trajectory.launch 

roslaunch turtlebot_teleop keyboard_teleop.launch



Extra package:
robot_pose_ekf
https://github.com/dudasdavid/odom_to_trajectory

launch in willow garage:
roslaunch turtlebot_gazebo turtlebot_world.launch world_file:=worlds/willowgarage.world
