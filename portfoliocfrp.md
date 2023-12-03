---
# layout: default
title: Nur Alif Ilyasa Project Showcase
site.title: anuan
---

This is Nur Alif Ilyasa's Project showcase of:

# Humanoid Robot Soccer Body Frame Development using CFRP

## Background
The new humanoid robot soccer software was initially being build based on the problem of the following:
1. The previous software structure are jumbled reducing readability of the code.
2. It uses C++ which sometime requires slow compiling, slowing down the development of the software. The use of C++ also being an obstacle for new member of the team to work on the software since it has rigorous syntax. 
3. Many component are outdated and dependent on old libraries. The motion framework used is no longger supporting newer version Actuators.
4. Does not use ROS (Robotic Operation System) to manage the structure of the software making it more difficult to manage the structure of the software.

## The New Software
The new software was built based on Robotis OP3 software which is the latest model of robot that utilizes newer Robotis actuators. The software is structured using ROS. The base modules like walking motion module and action module from Robotis OP3 are reserved. What we did in this project is creating a higher level of module in Python to control those base modules. As python are much more human readable, we did implement several features on the robot. There are also plenty choices for frameworks for comunication, integration with machine learning, and for visual processing. As the result we did present features to the new software as follows:
1. Remote control and monitoring using Websocket between robot and the web interface.
2. Easy walking configuration from the web interface. 
3. Live video feeds from the robot vision using WebRTC.
4. The web interface was built using bootstrap 4.
5. Uses ROS which enables modularity.
6. Uses Python.

As the result bellow are the overview of the new robot architechture.

##

