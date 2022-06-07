# EE346-lab6
Codes of EE346 Mobile Robot Navigation and Control Lab6.

Use "git clone https://github.com/tf1423079696/EE346-lab6.git" to download the codes and all supporting files.

The "camerav2_320x240.yaml" is the camera information and parameters obtained by calibration.

The "lane_following_please.py" is the codes for line following.

To run it, first run "turtlebot_bringup" on Turtlebot3, then open its dictionary in terminal and run "python lane_following_please.py". Remember to set it as executable file.

The "navigation_demo.py" is the codes for automatic nacvigation, and "map_new.pgm" is corresponding map.

To run it, first run "turtlebot_bringup" on Turtlebot3, then run "turtlebot_navigation" on PC and set the map parameter as "map_new.yaml". After that, open the file's dictionary in terminal and run "python navigation_demo.py".

The "lane_following_reset.py" is to stop the robot.
