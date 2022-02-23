
# Gazebo Workshop

This is a package used for the demo purpose in gazebo workshop been conducted.




## Installing teleop_twist_keyboard
After setting up a workspace, follow these commands to install teleop_twist_keyboard package

```bash
  sudo apt-get install ros-melodic-teleop-twist-keyboard
```

## Creating a Package

After creating a catkin workspace follow these commands to create a package

```bash
  cd catkin_ws/src
```
```bash
  catkin_create_pkg workshop_demo urdf
```
This will create a package with a CMakeLists.txt and package.xml in it. Then,
```bash
  cd ..
```
```bash
  catkin_make
```
```bash
  source ./devel/setup.bash
```
This completes creating and setting up of a package.

## Launching the Simulation
After creating a .launch file for simulation follow this command to launch our gazebo simulation.

```bash
  roslaunch workshop_demo robo.launch
```
To run the teleop_twist_keyboard package and to control the movement of robot use the below command
```bash
  rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```


## Additional Links

- [URDF online visualization website](https://mymodelrobot.appspot.com/5629499534213120)
- [Few gazebo models](https://github.com/osrf/gazebo_models)
- [Few pre-built gazebo worlds](https://drive.google.com/drive/folders/1kYbvD297EFjZHpP17M7sGKmLdQPEn7se)

