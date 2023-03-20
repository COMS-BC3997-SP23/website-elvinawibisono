---
title: Week 6
category: Weekly Progress
---

After being able to connect to the Wifi and SSH, I can start setting up and installing the necessary softwares for Raspberry Pi Zero 2W and Camera Module V2. For example, I will be needing OpenCV and TensorFlow for my project thus I will be installing it in Raspberry Pi. I also start setting up the hardware of the Camera. We ran into a problem setting up the camera. 

The problems of Camera Module V2: 
- Not being able to be detected 
    - Fixed: connecting the camera with the pins correctly 
- Camera is able to take a picture with raspistill, however this library is no longer used and should 
use the new libcamera library instead. 
    - Was able to take a picture with raspistill. 
- Camera libcamera-interface = 0
    -Fixed: by changing the config.txt file specifically for the camera part to be able 
    to detect Camera Module V2 
    - Was able to take picture using the libcamera 
      <center><a href="https://ibb.co/NsVxt33"><img src="https://i.ibb.co/Xb2Xj44/group2.jpg" alt="group2" border="0"></a><br /><a target='_blank' href='https://imgbb.com/'>image hosting</a><br /></center>

  

