# robot_ws
INSTRUCTION:

we need to: ROS2 FOXY
1. git clone into your workspace/src
2. create workscpace: 1)colcone  build--symlimk-install, 2)source install/setup.bash  (cd /workspace)
3. install ros2 packages: sudo apt install ros-foxy-ros2-control ros-foxy-ros2-controllers ros-foxy-gazebo-ros2-control
4. run gazebo mod: ros2 launch articubot_one launch_sim.launch.py
5. run contrloerr: ros2 run controller_manager spawner.py velocity_controller
6. run pkg for cmd->velocity_controller/command: ros2 run src_gazebo_controller src_gazebo_controller
7. run keyboard: ros2 run teleop_twist_keyboard teleop_twist_keyboard 


     
