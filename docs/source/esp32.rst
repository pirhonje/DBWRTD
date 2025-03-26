###############
ESP32
###############


Usage
=====

Two ESP32's mission is to convert pedal and steering commands into actual movement of the actuators.
One ESP32 pushes gas and braking pedal with electric linear actuator and another ESP32 controls the steering wheel.
Both ESP32 works with micro_ros. Installation instructions below. 


Troubleshooting
==============

In case of problems, remove ESP32 from Jetson Orion Nano and attach it again.


Installation
============

To install needed ESP32 micro_ros follow following steps:

1. Install Arduino IDE
2. Go to file/properties/ and paste following link to "Additional Boards Manager URL:s": https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
3. Install esp32 core by Espressif Systems from arduino ide tools/board manager
4. Choose esp32 dev module board from tools/board manager
5. Install micro_ros_arduino library to Arduino IDE by following steps
6. Go to following github and download the code to ZIP file:	https://github.com/micro-ROS/micro_ros_arduino/tree/humble
7. Arduino ide press sketch/library manager/ and click from .ZIP file and choose the downloaded ZIP file

Now you have micro_ros library on your esp32
More detailed instustions on following youtube video: https://www.youtube.com/watch?v=qtVFsgTG3AA


ESP32 codes installation instruction: https://github.com/pelottavapontso/Optimus-Drive