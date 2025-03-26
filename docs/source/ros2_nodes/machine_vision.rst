###############
Machine vision node
###############


Usage
=====

Machine visio node outputs camera video to display, detects objects and calculates objects distances to the middle of the screen.

To launch only the Machine vision node use following terminal command:

.. code-block:: bash
    
   ros2 run my_saab machine_vision

Published topics
===============

.. list-table:: 
    :widths: 50 50
    :header-rows: 1

    * - Topic
      - Description
    * - ``/object_detect_distance``
      - Distance of the object

Troubleshooting
==============

In case of problems, restart the node.


Installation
============

Installation instruction: https://github.com/pelottavapontso/Optimus-Drive

