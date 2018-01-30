# Extended Kalman Filter
This project is the sixth project of the Self Driving Car Nanodegree (First of the term-2). The project emphasises upon building Extended Kalman Filter which feeds on LIDAR and RADAR data.
## Aim : 
To build a Kalman Filter to estimate the state of moving object of interest with noisy lidar and radar measurements. Passing the project requires obtaining RMSE values that are lower that the tolerance outlined in the project rubric. 

The project was created with the Udacity [Starter Code](https://github.com/udacity/CarND-Extended-Kalman-Filter-Project).

## Simulator 

This project involves the Term 2 Simulator which can be downloaded [here](https://github.com/udacity/self-driving-car-sim/releases)

## Content of this repo
- `src` a directory with the project code:
  - `main.cpp` - reads in data, calls a function to run the Kalman filter, calls a function to calculate RMSE
  - `FusionEKF.cpp` - initializes the filter, calls the predict function, calls the update function
  - `kalman_filter.cpp`- defines the predict function, the update function for lidar, and the update function for radar
  - `tools.cpp` - a function to calculate RMSE and the Jacobian matrix
- `data`  

## Result
![input 1 results](Screenshot(58).png) 
X = 0.09 
Y = 0.08 
VX = 0.45 
VY = 0.43


## How to run the code
Clone this repo and perform 
```
mkdir build && cd build
cmake .. && make
./ExtendedK 

```


