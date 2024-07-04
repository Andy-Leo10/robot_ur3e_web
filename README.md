# robot_ur3e_web

```
git clone https://github.com/Andy-Leo10/robot_ur3e_web.git
```

- [robot\_ur3e\_web](#robot_ur3e_web)
  - [install Foxglove](#install-foxglove)
  - [launch the Foxglove's bridge](#launch-the-foxgloves-bridge)
  - [log in Foxglove and load this panel's setup](#log-in-foxglove-and-load-this-panels-setup)

---

<details>
<summary><b>Setup</b></summary>

## install Foxglove
```
sudo apt-get update; sudo apt-get install ros-humble-foxglove-bridge
```

</details>

---

<details>
<summary><b>LAUNCH BRIDGE</b></summary>

## launch the Foxglove's bridge 
```
cd ~/ros2_ws/ ;colcon build --packages-select robot_ur3e_web;source install/setup.bash; ros2 launch robot_ur3e_web robot_ur3e_web.launch
```
check the 'ip' of the virtual machine
```
rosbridge_address
```

</details>

---

<details open>
<summary><b>Expected result</b></summary>

## log in Foxglove and load this panel's setup
```
foxglove.json
```
you should get these panels
![webpage](<assets/webpage.jpg>)

</details>

---
