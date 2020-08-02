# iq_gnc

![iq](docs/imgs/iq.JPG)

This package hosts a collection of software designed to help drone developers make their application come to life. The code in this repo is complimented by the [iq_tutorials](https://github.com/Intelligent-Quads/iq_tutorials) repo, which explains how to set up your dev enviorment as well as teaches basic drone programming fundamentals. 

---

## Guidance Navigation and Control Functions

### gnc_function.hpp

The intelligent quads gnc_functions are collection of high level functions to help make controlling your drone simple. You can find functions for interpreting state estimation, commanding waypoints, changing modes and more. The documention for using these functions is shown below. 

[gnc_functions documentation](https://github.com/Intelligent-Quads/iq_tutorials/blob/master/docs/GNC_functions_documentation.md)

---

## Example Code 

### avoidance_sol.cpp
Example obstacle avoidance program utalizing the potential field method.

### gnc_tutorial.cpp
Simple waypoint mission that commands a drone to fly a square pattern. 

### sr_sol.cpp 
Simple search and rescue program that will fly a seach pattern until yolo detects a person. This will trigger the drone to land to deliver the rescue supplies. 

### subscriber_sol.cpp
Example program showing how to use a ROS subscriber to take input into your drone's guidance node.



## Related Repos

[iq_tutorials](https://github.com/Intelligent-Quads/iq_tutorials) - Repo hosting associated tutorials for iq_gnc

[iq_sim](https://github.com/Intelligent-Quads/iq_sim) - Repo hosing the simulation wolds designed to help develop drone gnc missions



