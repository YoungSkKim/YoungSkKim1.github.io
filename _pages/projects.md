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

### Monocular 3D Object Detection on KITTI Dataset
#### To be updated
---------------------------------------

### Autonomous Driving Dataset Acquisition
#### To be updated
---------------------------------------

### Camera LiDAR Calibration

**Camera intrinsic, Camera-LiDAR extrinsic calibration**  
![cali](https://github.com/YoungSkKim/YoungSkKim.github.io/blob/master/images/projects/000025.jpg?raw=true){:height="320px"}  
Calibration using genetic algorithm

---------------------------------------

### Traffic Light Detection 
<br/>
**Learning-based traffic light detector + Rule-based light bulb classifier**  
![tr](https://github.com/YoungSkKim/YoungSkKim.github.io/blob/master/images/projects/traffic light detection.png?raw=true){:height="320px"}  
1) Extract RoIs (traffic lights) using one-stage object detector  
2) Extract pixels of the lit blub on traffic light using histogram-based thresholding  
 2-1) Classify the color of bulb among the color templates using clustering algorithm  
 2-2) Classify the left-turn signal using simple rule-base kernel  
3) Remove false alarm by moving average filter  

---------------------------------------
