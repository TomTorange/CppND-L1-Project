#CppND-L1-Project

This project is the first step in final project for the Concurrency Part of the Udacity C++ Nanodegree. This is a concurrent traffic simulation and the purpose is to simulate traffic in a city grid with vehicles, streets and intersections. Vehicles drive around randomly and change direction at each intersectoin. Each object in the city grid will run independently in its own thread.

The task is to understand the code base and complete where needed to get this first running version of traffic simulation.

## Code Overview

<img src="data/Screenshot from 2021-08-25 12-24-28.png" > <img src="data/Screenshot from 2021-08-25 12-25-24.png" /> 

##Project Tasks

* Task L1.1 : In the base class TrafficObject, set up a thread barrier in its destructor that ensures that all the thread objects in the member vector _threads are joined.
* Task L1.2 : In the Vehicle class, start a thread with the member function drive and the object this as the launch parameters. Also, add the created thread into the _thread vector of the parent class.
* Task L1.3 : Vary the number of simulated vehicles in main and use the top function on the terminal or the task manager of your system to observe the number of threads used by the simulation.


## Dependencies

* cmake>=2.8
* make >= 4.1 (Linux, Mac), 3.81 (Windows) 
* OpenCV >= 4.1
* gcc/g++ >= 5.4

## Build Instructions

1. Clone this repository
2. Make a build directory: mkdir build && cd build
3. Compile: cmake .. && make
4. Execute: ./traffic_simulation.


