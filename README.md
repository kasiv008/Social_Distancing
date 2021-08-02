# Social_Distancing
Social Distancing violation alerting system.

The Official code for Social Distancing and Mask Monitoring system developed by [MOONLAB](https://sites.google.com/view/m00nlab/home).

## Overview

Due to Covid-19 pandemic, strict measures including Social-Distancing and Face mask is implemented in public places and work places. To ensure the same we at MOONLAB have developed an AI based violation alerting systems to detect the violation of COVID-19 protocols and the same was tested and implemented at the Indian Institute of Science Education and Research Bhopal. The system uses Jetson nano as computing unit hence making it a portable one. The images captured are converted into a Bird-eye view and uses pretrained Yolov3 for person detection.

## Requirements:\
    Jetson Nano/TX2/NX or Rpi 4\
    Python 3.5<\
    IMX 219 or system compatible camera\
    Buzzer/Speakers\
    Linux 18/20.
  
![](https://github.com/kasiv008/Social_Distancing/blob/main/290.jpg?raw=true) ![](https://github.com/kasiv008/Social_Distancing/blob/main/20210103_181411.jpg?raw=true)
    
Download the Models [here](https://drive.google.com/drive/folders/1vASRhOe8j_COXHPyMdBPNqz3okN5HEC1?usp=sharing) and change accordingly in main.py. The standard implementation is on YOLOV3.
## Initialize
Run main.py to initialize.




