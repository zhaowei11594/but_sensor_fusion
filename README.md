# but_sensor_fusion


##Package description:

-This package fuses data from the environment which is obtained  by a Hokuyo laser and a RGB-D camera.

-The package is tested with an UTM-30LX  and an Asus Live Xtion Pro RGB-D camera. 

-The fused readings can be depicted under RVIZ in "Global Options/FixedFrame/laser", whrere the fused data readings topic is "\laser_xtion_sensor" 

-Nodes package description
  --filter_hokuyo filters the sonar readings to a specified min and max range.
  --laser_rgbd_pc2 converts the data readings to pc and pc2.
  --laser_rgbd_registration makes sensor data readings alignment .
  --laser_rgbd_fusion fuses both sensor data readings.



##Instalation instructions:

-cd ~/ros/catkin_ws/src

-git clone https://github.com/robofit/but_sensor_fusion.git

-cd ../

-catkin_make


##run simulation:

-roslaunch lunch laser_rgbd.launch









