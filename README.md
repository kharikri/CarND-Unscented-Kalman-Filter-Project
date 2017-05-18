# Sensor Fusion with Unscented Kalman Filters
Self-Driving Car Engineer Nanodegree Program

This is the second project in the second term of the Self Driving Car Nanodegree course offered by Udacity.

In this project we fuse the Lidar and Radar measurements to estimate the position of objects on the road such as pedestrains, bicycles, other cars, etc. This project uses Unscented Kalman Filters for prediction and update. Here we assume the vehicle is moving with a constant velocity and can also turn.

I implemented this project in C++.

The following gives details on how to run the code:
---

## Dependencies

* cmake >= v3.5
* make >= v4.1
* gcc/g++ >= v5.4

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. -G "Unix Makefiles" && make`
4. Run it: `./UnscentedKF path/to/input.txt path/to/output.txt`. 

