---
# layout: default
title: Nur Alif Ilyasa Project Showcase
site.title: anuan
---

This is Nur Alif Ilyasa's Project showcase of:

# Python Based Humanoid Robot Soccer Software
## Background
The development of the new humanoid robot soccer software stemmed from several issues in the previous iteration:
1. The prior software exhibited a disorganized structure, diminishing code readability.
2. It was coded in C++, leading to slow compilation times and hindering software development. The language's strict syntax posed a challenge for new team members.
3. Numerous components relied on outdated libraries, and the motion framework used became incompatible with newer versions of actuators.
4. Lack of integration with ROS (Robotic Operation System) resulting in complicated software structure management.

## The New Software
The revamped software was constructed based on the Robotis OP3 software, featuring the latest robot model employing newer Robotis actuators. This software adopted a ROS-based structure, utilizing core modules such as the walking motion module and action module from Robotis OP3. Our project involved creating higher-level Python modules to control these base modules, leveraging Python's enhanced readability. Several features were implemented, including:

1. Remote control and monitoring via Websocket between the robot and a web interface.
2. Simplified walking configuration through the web interface.
3. Live video feeds from the robot's vision using WebRTC.
4. The web interface, designed with Bootstrap 4, enhances user experience.
5. Modularity facilitated by ROS.
6. Utilization of Python for enhanced flexibility.
7. The resulting architecture of the new robot is outlined below.
8. Easy integration for machine learning models.

### Robot software structure:
![Alt text](/assets/robotarch.png)

### Source code:
[Github Repository](https://github.com/NurAlif/agen3/tree/master)

### A demo for goal alignment, robot collision avoidance, and ball tracking task
<iframe width="560" height="315" src="https://www.youtube.com/embed/r_5oJZQcusY?si=0NBWVDoXfzsfzbJs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### A robot perform in a match at Indonesian Robotics Contest 2023
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sRURU1mo58?si=s7n6K3jUcOt6D3J3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

