# anther-ros-robot-with-SLAM-approach-
## task4
- Frist step:run this code in the termina:<br/>
<br/> `sudo apt-get install ros-melodic-hector-trajectory-server ros-melodic-slam-gmapping ros-melodic-navigation`
-Second step: run this code in the terminal:
```
cd ~/catkin_ws/src

git clone https://github.com/mrymalsubhi/warehouse_simulation_toolkit

cd ..

catkin_make

source ~/catkin_ws/devel/setup.bash
```
-  Third step:launch ROS by running this code:<br/>
<br/>  ` roslaunch warehouse_simulation warehouse_simulation.launch `
-
![home1](https://user-images.githubusercontent.com/85634146/130117528-a45f26c4-d666-4831-8c10-cae06cc2b0d1.jpeg)
- 
![home2](https://user-images.githubusercontent.com/85634146/130117541-52c35337-ef1e-423d-b40e-cd7cb98ee282.jpeg)
- Final step: save the map:<br/>
<br/>  `rosrun map_server map_saver -f ~/map  `

