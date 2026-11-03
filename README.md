# ar_interfaces

Custom ROS 2 messages and actions shared by the robot's software packages.

This package defines the communication formats used by different parts of the robot, including:

- **Movement actions** for odometry-, SICK sensor-, and yaw-based movement.
- **MoveTwist and RotateExec actions** for displacement and rotation requests.
- **Gripper messages** for sending mechanism commands and receiving status.

Other packages, especially the behaviour-tree and control-server packages, use these interfaces to communicate consistently.

Build it as part of the ROS 2 workspace with `colcon build`.
