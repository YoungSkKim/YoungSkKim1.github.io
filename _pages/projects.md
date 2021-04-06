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

## Monocular image-based 3D Object Detection  
**Boost monocular 3D object detector with auxiliary depth prediction task**  
*(ranked 1st among published monocular methods on KITTI BEV detection benchmark as of 2021 March)*  
![ICCV](https://github.com/YoungSkKim/YoungSkKim.github.io/blob/master/images/projects/CenterNet-Boost-plot.png?raw=true){:width="800px"}  

**Bird's-eye-view (BEV) object detection via Inversep Perspective Mapping (IPM) image**  
![IV](https://github.com/YoungSkKim/YoungSkKim.github.io/blob/master/images/projects/IV-concept.jpg?raw=true){:width="600px"}  

<br/>
<hr style="border:1px solid gray">
<br/>

## Sensor fusion-based 3D Object Detection  
**Low-level Range-Azimuth radar heatmap and monocular image fusion**  
![ACCV](https://github.com/YoungSkKim/YoungSkKim.github.io/blob/master/images/projects/ACCV-plot2.png?raw=true){:width="400px"}  

**Robust radar point cloud and monocular image fusion using gating mechanism**  
![IROS](https://github.com/YoungSkKim/YoungSkKim.github.io/blob/master/images/projects/IROS-plot.png?raw=true){:width="600px"}  

<br/>
<hr style="border:1px solid gray">
<br/>

## Autonomous Driving Dataset Acquisition

![dataset](https://github.com/YoungSkKim/YoungSkKim.github.io/blob/master/images/projects/VDC-Dataset.png?raw=true){:width="800px"}  
The dataset consists of 7,520 frames and 86,078 annotations collected through more than 10 hours driving considering various time (day, night) and environments (urban, suburb, motorway). The dataset contains following sensors: 3D LiDAR (Ouster OS1-64), point-level radar (Continental ARS408), low-level radar (INRAS RadarBook2), camera (FLIR BlackFly), DGPS with IMU (Novatel Flexpak6). 
### *In collaboration with: Sangmin Sim (Low-level radar, data collection), Sihwan Hwang (data collection)*  

<br/>
<hr style="border:1px solid gray">
<br/>

## Traffic Light Detection 

**Learning-based detector + Rule-based classifier**  
![tr](https://github.com/YoungSkKim/YoungSkKim.github.io/blob/master/images/projects/trafficlight.png?raw=true){:width="600px"}  
1) Extract RoIs (traffic lights) using one-stage object detector  
2) Extract pixels of the lit blub on traffic light using histogram-based thresholding on HSV color space  
 2-1) Classify the color of bulb among the color templates using clustering algorithm  
 2-2) Classify the left-turn signal using rule-base kernel if the light is green4  
3) Remove false alarm by moving average filter  

<br/>
<hr style="border:1px solid gray">
<br/>

## Sensor Calibration

![cali](https://github.com/YoungSkKim/YoungSkKim.github.io/blob/master/images/projects/000025.jpg?raw=true){:width="500px"}  
**Camera intrinsic calibration** using MATLAB ToolBox  
**Camera-LiDAR extrinsic calibration** using genetic algorithm based optimization  
