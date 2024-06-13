# robot_ur3e_web

## install Foxglove
```
sudo apt-get update; sudo apt-get install ros-humble-foxglove-bridge
```

## launch the Foxglove's bridge 
```
cd ~/ros2_ws/ ;colcon build --packages-select robot_ur3e_web;source install/setup.bash; ros2 launch robot_ur3e_web robot_ur3e_web.launch
```
check the 'ip' of the virtual machine
```
rosbridge_address
```

## log in Foxglove and load this panel's setup
```
foxglove.json
```
you should appreaciate these panels
![webpage](<webpage.jpg>)