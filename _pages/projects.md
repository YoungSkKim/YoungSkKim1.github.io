---
layout: archive
title: "Projects"
permalink: projects/
author_profile: true

---

<style type='text/css'> 
h2, h3, h4, h5, h6 {margin: 0;}
.br {display: block; margin-bottom: 0em; margin: 0;} 
</style>

{% include base_path %}

## Monocular 3D Object Detection on KITTI Dataset

#### To be updated

---------------------------------------

## Autonomous Driving Dataset Acquisition

**LiDAR, 2 radars, 6 cameras, GPS, IMU, CAN data**  
#### *In collaboration with: Sangmin Sim, Sihwan Hwang*  
![dataset](https://github.com/YoungSkKim/YoungSkKim.github.io/blob/master/images/projects/dataset.png?raw=true){:width="600px"}  
The dataset consists of 7,520 frames collected through more than 10 hours driving considering various time (day, night) and environments (downtown, suburb, motorway).
The dataset contains following sensors: 3D LiDAR (Ouster OS1-64), point-level radar (Continental ARS408), low-level radar (INRAS RadarBook2), camera (FLIR BlackFly), DGPS and IMU (Novatel Flexpak6).

---------------------------------------

## Camera LiDAR Calibration

**Intrinsic, extrinsic calibration using genetic algorithm**  
![cali](https://github.com/YoungSkKim/YoungSkKim.github.io/blob/master/images/projects/000025.jpg?raw=true){:width="600px"}  

---------------------------------------

## Traffic Light Detection 

**Learning-based detector + Rule-based classifier**  
![tr](https://github.com/YoungSkKim/YoungSkKim.github.io/blob/master/images/projects/trafficlight.png?raw=true){:width="600px"}  
1) Extract RoIs (traffic lights) using one-stage object detector  
2) Extract pixels of the lit blub on traffic light using histogram-based thresholding  
 2-1) Classify the color of bulb among the color templates using clustering algorithm  
 2-2) Classify the left-turn signal using simple rule-base kernel  
3) Remove false alarm by moving average filter  

---------------------------------------
