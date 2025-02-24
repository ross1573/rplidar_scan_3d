# Indoor 3D Scanning based on two 2D LiDAR sensor and SLAM

### Requirments
* rplidar a series
~~~
Tested on Ubuntu 20.04LTS, ROS noetic, rplidar a3(a2)
~~~
-----

### Setup

1. Two line ros noetic install command
```shell
wget -c https://raw.githubusercontent.com/qboticslabs/ros_install_noetic/master/ros_install_noetic.sh && chmod +x ./ros_install_noetic.sh && ./ros_install_noetic.sh
```

2. Install pcl-ros for ros noetic
```shell
sudo apt install ros-noetic-pcl-ros
```

3. Build using caktin-make
```shell
catkin_make
```

-----

### Node, Topic diagram
<img src="./demo/diagram.jpg" width="430px" height="360px">

-----

### Result
* captured point cloud(full pcd file at [floot_half.pcd](https://github.com/ross1573/scan_3d/blob/master/demo/floor_half.pcd.zip))
<img src="./demo/floor_half_pcd.png" width="430px" height="270">

https://user-images.githubusercontent.com/44907014/183363951-281430e0-76fa-43bb-ba74-8b1b220393ef.mp4

(full capture video available at [demo_capture.mp4](https://github.com/ross1573/scan_3d/blob/master/demo/demo_capture.mp4))


-----
