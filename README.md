# Robot-operating-system-installation-and-configuration
Welcome to the Robotics-Arm- wiki!
# Ros and Ubuntu installation 
## 1. downloading VirtualBox 
1.01: the link for downloading VirtualBox --> https://www.virtualbox.org/wiki/Downloads
## 2. Ubuntu installation 
2.01: the link for installing ubuntu 16.04: https://ubuntu.com/tutorials/install-ubuntu-server-1604#1-overview 
<why 16.04 ---> because it easy to use the simulation and more and more features in the 16.04 version>
2.02: uploading ubuntu in the VirtualBox and start the OS! 
## 3. installing the Ros and Gazebo 
3.01: open the terminal 
3.02: by using the text provided by Smart methods ---> (https://s-m.com.sa/ros.txt), going step by step in the terminal and install the Ros and Gazebo using this command codes that provided below.
<why installing  Ros kinetic? it is a matter of personal opinion, I think kinetic is way easier than the other model in handling.  
## 4. Lunching Ros and Gazebo 
4.01: open the terminal
4.02: write --> roslaunch robot_arm_pkg check_motors.launch in the terminal--> to launch Ros 
4.03: open new terminal 
4.04: write --> roslaunch robot_arm_pkg check_motors_gazebo.launch in the terminal--> to launch gazebo 
4.05: open new terminal
4.06: write --> cd catkin_ws/src/arduino_robot_arm/robot_arm_pkg/scripts in the terminal
4.07: write --> inside the 4.06 path --> sudo chmod +x joint_states_to_gazebo.py
4.08: open new terminal 
4.09: write --> rosrun robot_arm_pkg joint_states_to_gazebo.py

