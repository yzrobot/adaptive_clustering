# Adaptive Clustering (GPU version) #

A lightweight and accurate point cloud clustering method (check out the [devel](https://github.com/yzrobot/adaptive_clustering/tree/devel) branch for further enrichment).

[![YouTube Video](https://img.youtube.com/vi/rmPn7mWssto/0.jpg)](https://www.youtube.com/watch?v=rmPn7mWssto)

## Configuring your PC to use your Nvidia GPU with PCL ##

[https://pcl.readthedocs.io/projects/tutorials/en/master/gpu_install.html#gpu-install](https://pcl.readthedocs.io/projects/tutorials/en/master/gpu_install.html#gpu-install)

## How to build ##
```
$ cd ~/catkin_ws/src/
$ git clone -b gpu https://github.com/yzrobot/adaptive_clustering.git
$ cd ~/catkin_ws
$ catkin_make
```

## Test environment ##
```
TITAN Xp
CUDA 10.2
PCL 1.12
Eigen 3.3.7
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
