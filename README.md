## VSLAM and Simulation Project

This project aims to simulate a simple wheeled robot with a Lidar sensor to run a SLAM algorithm for navigation. The project template was created from Josh Newans template repo and some of the work was guided by his youtube series [Articulated Robotics](https://www.youtube.com/@ArticulatedRobotics).

# Robot Description
A URDF file is used to describe the 3D visual properties and the collision and inertial properties of the robot. This file is later used by simulation software to render the robot.

# Gazebo Simulation
The robot is simulated using the gazebo-ros bridge which allows information about the robot's state to be passed back and forth between ros and gazebo. Since gazebo is aware of the robot state, the robot can be manipulated in real time using another ros tool.

![alt text](https://github.com/juliandevv/farover/blob/main/caps/Screenshot%20from%202025-08-14%2010-41-46.png)

# Rviz Simulation
While gazebo is useful for more realistic simulations, rviz is a tool for viewing different aspects of the robot such as transforms. Transforms allow you to visualize the pose of different parts of the robot.

![alt text](https://github.com/juliandevv/farover/blob/main/caps/Screenshot%20from%202025-08-14%2010-47-45.png)

# The Future
This project is currently incomplete, in the future sensors such as Lidar and stereo cameras will be simulated to create an environment for experimenting with SLAM methods.
