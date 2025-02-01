Getting the rover in Gazebo:
colcon build 
source install/setup.bash
ros2 launch my_robot_description display.launch.py

Controlling the rover:
ros2 run teleop_twist_keyboard teleop_twist_keyboard

