## Writeup

**Path Planning Project**

The goals / steps of this project are the following:

* The car is able to drive at least 4.32 miles without incident.
* The car drives according to the speed limit.
* Max Acceleration and Jerk are not Exceeded.
* Car does not have collisions.
* The car stays in its lane, except for the time between changing lanes.
* The car is able to change lanes


[//]: # (Image References)

[image1]: ./writeup/car.png "car"

--------------
![alt text][image1]

------------------
## Main program module:

### 1. Prediction 
about [line 128 to line 179](./src/main.cpp)

There is a logic of changing the lanes and a strategy of  speed control. Meanwhile, the predicted safe distance here is 30 meters.

### 2. Trajectory 
about [line 186 to line 289](./src/main.cpp)

Generate corresponding trajectories according to the predicted information. Meanwhile, each lane is 4 m wide and the car should only ever be in one of the 3 lanes on the right-hand side. 


