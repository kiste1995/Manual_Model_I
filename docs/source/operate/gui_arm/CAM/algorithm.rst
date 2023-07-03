Algorithm
===========================

Fingerprint Recognition Position Adjustment Algorithm Using CAM

----------------------------------------------------------------

**Center Coordinate Recognition**

- diff_x : Front/back distance value between the center of the screen and the center of the fingerprint reader
- diff_y : Top/bottom distance value between the center of the screen and the center of the fingerprint reader

.. thumbnail:: /_images/start_gui/algo.png

----------------------------------------------------------------

**Offset Coordinate Calculation**

- offset_x : Front/rear distance value between the center of the screen and the center of the fingerprint recognition sensor
- offset_y : Upper/lower distance value between the center of the screen and the center of the fingerprint recognition sensor

.. thumbnail:: /_images/start_gui/algo2.png
|

- Rot_theta : rotation angle value of the coordinates of the center of the fingerprint reader from the center of the screen

.. thumbnail:: /_images/start_gui/algo3.png

----------------------------------------------------------------

**Set Offset Value**

- offset_x : Modify forward/backward offset value of the camera-based positioning algorithm
- offset_y : Modify up/down offset value of camera-based positioning algorithm

.. thumbnail:: /_images/start_gui/algo4.png

----------------------------------------------------------------

**Algorithm**

1. Move the robot arm to a specific position to apply the recognition algorithm

.. 

2. Camera image capture

.. 

3. Change camera color information, convert to gray image

.. 

4. Apply various filters and image outline extraction algorithms to extract the rectangle outside the fingerprint reader

.. 

5. Extracting the outline of the fingerprint reader and acquiring the center coordinates

.. 

6. Offset x, y coordinate setting

.. 

7. Calculate the difference between the center coordinates of the camera and the current center coordinates of the fingerprint reader

.. 

8. Calculate the difference value (x, y axis) by applying offset coordinates to this difference value

.. 

9. First, move the robot forward/backward so that the x-axis difference value is less than a specific value (10, adjustable)

.. 

10. Calculate the difference value in real time and stop moving when it falls below a certain value

.. 

11. In a similar way to the above, move up/down so that the y-axis difference value is less than a specific value (using a robot arm)

.. 

12. Calculate the difference value in real time and stop moving when it falls below a certain value

.. 

13. Move the robot arm to the fingerprint reader proximity position

.. 

14. Calculation of camera center coordinates and rotation angle value of fingerprint reader center

.. 

15. Rotate the end of the robot arm in the opposite direction of the rotation angle using the robot arm

.. 

16. Proceed to the next step after completing the fingerprint reader position adjustment algorithm