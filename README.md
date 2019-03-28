# kuka_lab_setup
A repository for a workspace connecting the kuka_experimental and 
robotic_2finger_gripper workspaces for a unified urdf and .launch-file.

To test the URDF

```
roslaunch kuka_lab_setup test_kukalabsetup.launch
```

Nesessary packages are:

kuka_experimental
https://github.com/ros-industrial/kuka_experimental.git

robotiq
https://github.com/beta-robots/robotiq.git

In addition, run
kuka_lab_setup.rosinstall
