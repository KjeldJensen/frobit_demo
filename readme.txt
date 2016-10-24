This readme file contains various notes on the frobit_demo application.

First version: 2014-08-14 by Kjeld Jensen <kjeld@frobomind.org>
Updated: 2016-10-24 by Kjeld Jensen <kjeld@frobomind.org>

Run bin/frobit_sim_wpt_nav to view a simulation of autonomous waypoint
navigation based on odometry pose estimation.

Run bin/frobit_run_wpt_nav to run the autonomous waypoint navigation on
a Frobit robot.

Run bin/frobit_sim_wpt_nav_feedback to view a simulation of autonomous
waypoint navigation using a FroboMind implemented model of the Frobit
(frobit_sim component). The model provides detailed controller feedback
which is presented in the simulation.

The waypoint navigation is fully implemented. When running the scripts the
file waypoints.txt in the frobit_demo/waypoints directory is copied
to the ROS working directory and the waypoint list is navigated when
switching to autonomous mode .


KEYBOARD CONTROL
The frobit_demo provides simple controls based on keyboard input from the
user. A "user guide" is printed in the ROS console when running the demo.

