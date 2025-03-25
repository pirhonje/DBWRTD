###############
Auto control node
###############


Usage
=====

Auto control node converts distance of the detected objects of the Machine vision node to steering commands of ESP32.

To launch only the Auto control node use following terminal command:

.. code-block:: bash
    
   ros2 run my_saab auto_control

Published topics
===============

.. list-table:: 
    :widths: 50 50
    :header-rows: 1

    * - Topic
      - Description
    * - ``/micro_ros_agent_steering``
      - Steering command

Troubleshooting
==============

In case of problems, restart the node.


