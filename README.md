# Adaptive Clustering: A lightweight and accurate point cloud clustering method #

[![Build Status](https://travis-ci.org/yzrobot/adaptive_clustering.svg?branch=master)](https://travis-ci.org/yzrobot/adaptive_clustering)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/61a01a79a7ac41fd9deded9050ef6030)](https://www.codacy.com/app/yzrobot/adaptive_clustering?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=yzrobot/adaptive_clustering&amp;utm_campaign=Badge_Grade)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-green.svg)](https://opensource.org/licenses/BSD-3-Clause)

[![YouTube Video](https://img.youtube.com/vi/rmPn7mWssto/0.jpg)](https://www.youtube.com/watch?v=rmPn7mWssto)

## Changelog ##

\[Apr 14, 2022\]: Two new branches, [gpu](https://github.com/yzrobot/adaptive_clustering/tree/gpu) and [agx](https://github.com/yzrobot/adaptive_clustering/tree/agx), have been created to test the GPU-based version:
   - [gpu](https://github.com/yzrobot/adaptive_clustering/tree/gpu) is based on [PCL-GPU](https://pcl.readthedocs.io/projects/tutorials/en/master/#gpu) and has been tested with an NVIDIA TITAN Xp.
   - [agx](https://github.com/yzrobot/adaptive_clustering/tree/agx) is based on [CUDA-PCL](https://github.com/NVIDIA-AI-IOT/cuda-pcl) and has been tested with an NVIDIA Jetson AGX Xavier.

\[Feb 25, 2019\]: A new branch, [devel](https://github.com/yzrobot/adaptive_clustering/tree/devel), has been created to improve the accuracy of clustering (currently at the expense of real-time performance), including:
   - Merge clusters split by nested regions.
   - Merge clusters on the z-axis.

## How to build ##
```
$ cd ~/catkin_ws/src/
$ git clone https://github.com/yzrobot/adaptive_clustering.git
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
