Other function description
===========================================

Before we get into it, let me explain what will help you understand the behind the scenes once you know it.

--------------------------------------------------------------------------------------------

.. thumbnail:: /_images/start_gui/heading.png
    :width: 300
    :height: 100

- IMU : Rotation angle value output from inertial sensor
- Angle : Output the angle value of robot heading using robot coordinates and inertial sensor data
|

----------------------------------------------------------------------------------------------

.. thumbnail:: /_images/start_gui/mapfile.png
    :width: 300
    :height: 100

- Map File : Designate the file name of the map to be saved, save location is <.ros> in the home
- WP File : Edit route point storage file name
- Cycle : number of scheduling repetitions
|

----------------------------------------------------------------------------------------------

.. thumbnail:: /_images/start_gui/status.png

- MR Status : Output of the current operating status of the robot
- FR : front safety laser detection area selection number
- RR : rear safety laser detection area selection number
- F-WF : Front safety area detection operation status
- R-WF : Rear safety area detection operation status
- Pump : Pump operation status
- Sol : Solenoid valve operation status
- UVCE : Operating state of the ultraviolet lamp at the end of the robot
- UVCB : Operating state of the UV lamp at the bottom of the robot
- SCRUB : scrubber operation status
- GL : Green laser operation status
- RL : Red laser operation status
|

----------------------------------------------------------------------------------------------

.. thumbnail:: /_images/start_gui/status2.png
    :width: 300
    :height: 100

- Charg. : Automatic charger parking status output
- Navi : Indicates robot autonomous driving status (Blue, Green, Red)
- Estop: emergency stop state (Red)
|

----------------------------------------------------------------------------------------------

.. thumbnail:: /_images/start_gui/message.png
    :width: 300
    :height: 100

- Message Box : Outputs various messages related to robot operation, driving, and control
|

----------------------------------------------------------------------------------------------

.. thumbnail:: /_images/start_gui/log.png
    :width: 500
    :height: 500

- Log file storage location : /home/zetabank/catkin_ws/src/robot_control_gui/log