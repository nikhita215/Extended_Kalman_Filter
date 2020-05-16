## Extended_Kalman_Filter

This repository contains the necessary code in C++ to track a bicycle's position and velocity that travels around the ego vehicle. The EKF algorithm uses the data that the sensors(RADAR, LIDAR) mounted on the car receive to estimate its position within required accuracy.

The required algorithm and classes used to process the data("FusionEKF.cpp", "kalman_filter.cpp") can be found in the src folder.

"EKF_in_action" is a video file that shows the output of the code in a simulator. Lidar measurements are red circles, radar measurements are blue circles with an arrow pointing in the direction of the observed angle, and estimation markers are green triangles.
