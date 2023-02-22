# PROJECT:  Autonomus Navigation on the Road by Lane Detection and Deep Learning
## Submitted by: Mayuresh Bhosale

### Problem Statement:
In this project, I had to implement the concepts of Autonomous navigation of a vehicle on the road by using Deep Learning models, Lane identification and Image processing using cameras. The task was to navigate RC vehicle to follow the lanes by lane detection and stanley control and implement deep learning model to detect stop sign and school sign to stop and slow down.

### Implementation

**Autonomus Navigation Approach**
![](https://github.com/mayureshb7/Autonomus-Naviation-On-the-Road/blob/main/Approach.png)


- Camera Calibration and Parameters Setup: The very first step is to calibrate the camera and it was done by using MATLAB camera calibration application. Other parameters such as Exposure, Focal length, resolution and camera height on the RC car was set
- Lane Extraction: Edge detection, Region of Interest, Hough transformation
- Stanley Controller: Departure angle and departure distance
- Road sign detection using deep learning

Please read `AuE8240_Final_Project_Report_Mayuresh_Bhosale.pdf` for more details.

**Image showing RC car hardware Setup for ADAS**
![](https://github.com/mayureshb7/Autonomus-Naviation-On-the-Road/blob/main/Hardware%20Setup.png)

**Image showing Canny versus Sobel Filter Comparision**
![](https://github.com/mayureshb7/Autonomus-Naviation-On-the-Road/blob/main/CannyvSobel.png)

**Table showing Final Image Processing Implementation**
![](https://github.com/mayureshb7/Autonomus-Naviation-On-the-Road/blob/main/Final%20Image%20Processing.png)

**Image showing final tracking result of the test**
![](https://github.com/mayureshb7/Autonomus-Naviation-On-the-Road/blob/main/Final%20Tracking%20and%20Analysis.png)


**Video of the Autonomous Navigation**
https://youtu.be/_nqouZzIk54

**Video of the Autonomous Navigation First Point Of View**
https://youtu.be/iufVzGBmwCA
