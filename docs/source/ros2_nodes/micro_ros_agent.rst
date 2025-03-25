###############
Micro ROS agent node
###############


Usage
=====

Micro ROS agent node acts as an intermediary between ESP32 and ROS2.

To launch only the micro ROS agent node use following terminal command:

.. code-block:: bash
    
   ros2 run micro_ros_agent micro_ros_agent serial --dev /dev/ttyUSB0


Troubleshooting
==============

In case of problems, restart the node.


Installation
============

To install needed ROS2 nodes, follow instructions to install micro_ROS_agent package properly.

Following steps are all to Ubuntu terminal:

1. source /opt/ros/humble/setup.bash
2. cd <to your workspace>
3. git clone https://github.com/micro-ROS/micro-ROS-Agent.git -b humble
4. cd ..
5. rosdep install --from-paths src --ignore-src -r –y
6. cd <to your workspace>
7. colcon build
8. ros2 run micro_ros_agent micro_ros_agent serial –dev /dev/ttyUSB0

