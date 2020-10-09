---
layout: page
title: Autonomous Boat
---

## Project description

Small autonomous boat to monitor shallow streams of water and small/medium rivers. 

![Alt text](../images/projects/lutra.png?raw=true "Lutra Airboat")

| | | |
| --- | --- | --- |
| ![small boat](../images/icons/sail-boat.png "small boat") |  ![electronics](../images/icons/electronics.png "electronics") | ![sensors](../images/icons/sensor.png "sensors") |

### Goals

 - Goal 1: deliver a small boat with safe autonomous navigation;
 - Goal 2: deliver a boat control system integrated to planning frameworks;
 - Goal 3: deliver a system to control multiple boats;

### Milestones

 - Milestone 1: integrate more sensors to the Lutra boat to enable autonomous behaviors; status (%)
 - Milestone 2: improve localization for safe autonomous navigation nearby manmade structures (docks) and shores; status (%)
 - Milestone 3: detect obstacles (both underwater and over the water) for safe autonomous navigation nearby manmade structures and shores; status (%)
 - Milestone 4: integrate different navigation strategies (fast, safe, coverage navigation) under real life disturbances (drag, wind, waves) for safe autonomous navigation nearby manmade structures and shores; status (%)
 - Milestone 5: integrate the boat middlware to the AI and planning frameworks; status (%)
 - Milestone 6: control simultaneously multiple boats in formations; status (%)
 - Milestone 7: field test controling simultaneously multiple boats; status (%)

## People

### Coordinator

 - Alexandre Amory, PUCRS.

### Academic Collaborators

 - Felipe Meneguzzi, PUCRS
 - Rafael Bordini, PUCRS.
 - Isabel Manssour, PUCRS.

### Technical Staff

 - Guilherme Heck, advised by Alexandre Amory, role: boat testing, wireless communication, sensor integration.
 - Roger Granada, advised by Alexandre Amory, role: computer vision for the boats.
 - Vitor Jorge, advised by Alexandre Amory.

### Students

 - Renan Guedes Maidana, Master student on Computer Science/PUCRS, advised by Alexandre Amory, role: system localization, perception, integration to middleware.
 - Darlan Jurak, Master in Computer Science/PUCRS, advised by Alexandre Amory, role: obstacle avoidance and path planning.
 - Marcelo Paravisi, PhD in Computer Science/PUCRS, advised by Alexandre Amory, role: system simulation, path planning, integration to middleware.
 - Igor de Souza Azevedo, undergraduate student in Computer Engineering/PUCRS, advised by Alexandre Amory, role: wuater quality sensors and LORA network.
 - Mateus Eugenio Colet, Master student on Computer Science/PUCRS, advised by Isabel Manssour, role: image-based obstacle detection for boats.
 - Maurício Cecílio Magnaguagno, PhD student on Computer Science/PUCRS, advised by Felipe Meneguzzi, role: autonomous planning
 - Rafael Cauê Cardoso, PhD student on Computer Science/PUCRS, advised by Rafael Bordini, role:  multiagent system
 - Tulio Lima Basegio, PhD student on Computer Science/PUCRS, advised by Rafael Bordini, role:  multiagent system

## Papers

    @Article{s19051068,
    AUTHOR = {Paravisi, Marcelo and H. Santos, Davi and Jorge, Vitor and Heck, Guilherme and Gonçalves, Luiz Marcos and Alexandre M. Amory},
    TITLE = {Unmanned Surface Vehicle Simulator with Realistic Environmental Disturbances},
    JOURNAL = {Sensors},
    VOLUME = {19},
    YEAR = {2019},
    NUMBER = {5},
    ARTICLE-NUMBER = {1068},
    URL = {http://www.mdpi.com/1424-8220/19/5/1068},
    ISSN = {1424-8220},
    DOI = {10.3390/s19051068}
    }



    @Article{s19030702,
    AUTHOR = {Jorge, Vitor A. M. and Granada, Roger and Maidana, Renan G. and Jurak, Darlan A. and Heck, Guilherme and Negreiros, Alvaro P. F. and dos Santos, Davi H. and Gonçalves, Luiz M. G. and Alexandre M. Amory},
    TITLE = {A Survey on Unmanned Surface Vehicles for Disaster Robotics: Main Challenges and Directions},
    JOURNAL = {Sensors},
    VOLUME = {19},
    YEAR = {2019},
    NUMBER = {3},
    ARTICLE-NUMBER = {702},
    URL = {http://www.mdpi.com/1424-8220/19/3/702},
    ISSN = {1424-8220},
    DOI = {10.3390/s19030702}
    }


## Repositories

 - [USVs ROS-based code](https://github.com/disaster-robotics-proalertas/awa-sv): this repository has the entire code required in the boat`s computers;
 - [USV Sim repository](https://github.com/disaster-robotics-proalertas/usv_sim_lsa)

## Main Hardware Resources

 - [Lutra airboat by Platypus LLC](http://senseplatypus.com/lutra-airboat/). Two units acquired via PVE Project XXX, coordinated by Felipe Meneguzzi.
 - 2x Vision module with Zed Camera and Jetson board by NVIDIA
 - 3x Vision module with Raspbery Pi Zero and Raspicam
 - [Lowrance Elite 5-TI side-scanner](https://github.com/disaster-robotics-proalertas/ros_nmea_depth) for bathymetry surveys
 - 3x [water quality modules](https://github.com/disaster-robotics-proalertas/atlas_ros)
 - [Water sampler](https://github.com/disaster-robotics-proalertas/water_sampler_ros)
 - Maxbotix ultrasonic sensors
 

## Media 

videos and photos.

 - [Field testing photos](https://photos.app.goo.gl/ZhbJEg3256ofCSdE9)
 - [USV Sim demo](https://www.youtube.com/watch?v=u-JnylVnD9I&list=PLecI7jQbTC3zhiwq5m1YmNKtYsZMgFjkX). A Gazebo-based simulation with wind and water current.

![Alt text](../images/projects/water-sampler-diff-github.png?raw=true "Lutra prop plus water sampler")
![Alt text](../images/projects/team-both-boats.png?raw=true "Team and two boats in a field testing trip")
![Alt text](../images/projects/diluvio.png?raw=true "Boat in the Diluvio river")
![Alt text](../images/projects/testing-guaiba.png?raw=true "Boat in the Guaiba")


