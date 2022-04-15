# Adaptive Clustering (GPU version): A lightweight and accurate point cloud clustering method #

[![YouTube Video](https://img.youtube.com/vi/rmPn7mWssto/0.jpg)](https://www.youtube.com/watch?v=rmPn7mWssto)

## How to build ##
```sh
cd ~/catkin_ws/src/
git clone -b agx https://github.com/yzrobot/adaptive_clustering.git
cd ~/catkin_ws
catkin_make
```

## Test environment ##
```
Jetson Xavier AGX
Jetpack 4.4.1
CUDA 10.2
PCL 1.8
Eigen 3
```

## Citation ##
If you are considering using this code, please reference the following:
```
@article{yz19auro,
   author = {Zhi Yan and Tom Duckett and Nicola Bellotto},
   title = {Online learning for 3D LiDAR-based human detection: Experimental analysis of point cloud clustering and classification methods},
   journal = {Autonomous Robots},
   year = {2019}
}
```
