###############
Steering node
###############


Usage
=====

Steering node converts controller commands of the Joy node to steering commands of ESP32.

To launch only the Steering node use following terminal command:

.. code-block:: bash
    
   ros2 run my_saab steering

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


