###############
Optimus drive launch
###############


Control Scheme
===============

.. image:: images/ps4_controller_layout.PNG
    :width: 1000


Buttons must be pressed one at a time or nothing happens!


.. list-table:: 
    :widths: 30 30 40
    :header-rows: 1
    :class: longtable

    * - Action
      - Button
      - Notes

    * - Shutdown
      - Share + Options
      - Press simultaneously until the Jetson Orion Nano \nshutdown

    * - Brake
      - L2
      - The amount of trigger pulled corresponds to the \nbrake pushed

    * - Brake trim
      - L1
      - Allows adjustment of the starting position of the \nbrake actuator

    * - Gas
      - R2
      - The amount of trigger pulled corresponds to the \ngas pushed

    * - Gas trim
      - R1
      - Allows adjustment of the starting position of the \ngas actuator

    * - Pedal trim reset
      - L1 + R1
      - Press simultaneously until the both linear \nactuatorshave returned to zero position

    * - Electrical handbrake
      - O
      - Press the brake pedal until the electric parking \nbrake is released. When the electric parking brake is activated, the other buttons do nothing.

    * - Release electric handbrake
      - X
      - Releases electric handbrake

    * - Steering
      - L Joystick
      - Turning the joystick to the left moves the steering \nwheel to the left and turning the joystick to the rigth moves the steering wheel to rigth

    * - Steering trim
      - Triangle
      - Pressing Triangle sets this point as the new center \nof the steering wheel


Launchin the Optimus drive
=========================


The car must be started before starting the Jetson Orion Nano!
Once the car is started, turn on the power to the actuator case using its switch. 
Do not connect the controller yet!
Wait 90 seconds and then connect the controller.
Now the Optimus drive is operational.

Always shutdown the Jetson Orion Nano with the controller! Never cut the power off from Jetson Orion Nano while its running!




