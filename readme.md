# README
## Tutorial:
### Bring up the robot:
`roslaunch ur5_gripper_bringup ur5_bringup.launch with_gripper:=true limited:=true robot_ip:=192.168.1.129`

### Launch moveit scence:
`roslaunch ur5_moveit_config moveit_rviz.launch config:=true`
`roslaunch ur5_gripper_moveit_config ur5_gripper_moveit_planning_execution.launch limited:=true`

