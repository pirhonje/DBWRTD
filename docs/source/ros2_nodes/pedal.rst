###############
Pedal node
###############


Usage
=====

Pedal node converts controller commands of the Joy node to pedal commands of ESP32.

To launch only the Pedal node use following terminal command:

.. code-block:: bash
    
   ros2 run my_saab pedal

Published topics
===============

.. list-table:: 
    :widths: 50 50
    :header-rows: 1

    * - Topic
      - Description
    * - ``/micro_ros_agent_pedal``
      - Pedal command

Troubleshooting
==============

In case of problems, restart the node.


installation
============

To install needed ROS2 nodes, follow instructions as