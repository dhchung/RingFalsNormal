# Ring FALS Normal Estimator

## Related Works

1. [LOG-LIO](https://github.com/tiev-tongji/RingFalsNormal): A LiDAR-inertial Odometry with Efficient Local Geometric Information Estimation


## How to use

```angular2html
mkdir -p ws_ring_fals/src
cd ws_ring_fals/src
git clone https://github.com/tiev-tongji/RingFalsNormal
```
set _**OpenCV_DIR**_ in the CMakeLists.txt to your local path, and please compile the  _**opencv-contrib**_ module in advance.

```angular2html
cd .. & catkin_make

source devel/setup.bash
roslaunch ring_fals normal_m2dgr.launch 
```

So far, we have only provided luanch files for M2DGR and NTU VIRAL, a more detailed readme is coming soon!

