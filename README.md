# Adaptive Clustering (GPU version) #

[![Build Status](https://travis-ci.org/yzrobot/adaptive_clustering.svg?branch=master)](https://travis-ci.org/yzrobot/adaptive_clustering)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/61a01a79a7ac41fd9deded9050ef6030)](https://www.codacy.com/app/yzrobot/adaptive_clustering?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=yzrobot/adaptive_clustering&amp;utm_campaign=Badge_Grade)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-green.svg)](https://opensource.org/licenses/BSD-3-Clause)

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
