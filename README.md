# odrive_ros
ROS driver for the ODrive motor drive for differential drive robots.

This repository features an updated ODrive ROS driver including a twist velocity estimation for differential drive robots.
Furthermore the supply voltage and safety related information is being published. It works with the current (January 2021) ODrive embedded software.

```
rosrun odrive_ros odrive_basic_node.py
```
