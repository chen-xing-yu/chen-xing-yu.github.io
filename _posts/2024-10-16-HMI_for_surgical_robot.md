---
layout: post
title: Intuitive Human-Machine Interface for Surgical Robots
subtitle: Let surgeon feel more real
#cover-img: /assets/img/path.png
thumbnail-img: /assets/img/VISR.png
gh-repo: daattali/beautiful-jekyll
tags: [surgical robot]
comments: true
mathjax: true
author: Xing-Yu Chen
---


The robotic system includes a force box used for measuring the
tactile force that interventionalists exerted with their fingers. This force is regarded as the
interventionalists’ operative force on the guidewire or catheter in regular surgery. The force box includes a 32-prism, tiny flexible strip sensors, PCBs, and batteries. A flexible
sensor is folded and wound around the force box surface, and its data is logged as a
32-channel data multiplexed over an Analog Multiplexer (Texas Instruments). Thus, the interventionalists also operate the master device by manipulating the
flexible sensor with their finger. The force data is processed in a microcontroller STM32
 and transmitted over a Bluetooth module to the slave console in real time. The force box also reflects
information about the flexible tool’s firmness as it is held with a clamping mechanism in
the slave manipulator. The guidewire is clamped tightly when the surgeon presses hard on
the force box and vice versa.

<br/><img src='/assets/img/forcebox.png'>
<center>The structure of the force box, which can measure the tactile force exerted by the surgeon's fingers. The force value will be used as parts of multi-modal information to optimize the control algorithm. (A) PCB layout of force box; (B) Force box includes a 32-prism,  tiny flexible strip sensors.</center>
<br/> 


To study the usage of robotic-assisted vascular interventions by surgeons and aid them in acquiring 
skills more efficiently, I designed a smart glove. This glove is capable of capturing and fusing information from multiple modalities, including the bending of the surgeon's fingers, the forces exerted while manipulating the vascular surgical robot, electromyographic (EMG) signals, posture angles and accelerations (IMU), as well as spatial position and orientation collected using electromagnetic sensors.

<br/><img src='/assets/img/glove.png'>
<center>Intelligent glove for robotic catheterization skill learning.</center>
<br/> 




### Related Pubulications: 

{: .box-note}
**Paper:** Chen, Xing-Yu, et al. Design and Evaluation of a Learning-based Vascular Interventional Surgery Robot. [Fibers, 10.12 (2022): 106](https://doi.org/10.3390/fib10120106)

{: .box-warning}
**CN Patent:** A Tactile-Feedback Device and Method for Surgical Robots. [CN115137483A](https://www.researchgate.net/publication/370801433_CN_Patent_yizhongshoushujiqirendezhuduanliganzhifankuicaozongzhuangzhijifangfa)

 {: .box-warning}
**CN Patent:** A Bidirectional Guidewire Force Measurement Method for Vascular Interventional Surgical Robot. [CN114948258A](https://www.researchgate.net/publication/370801270_CN_Patent_yizhongshuangxiangdianchushijierujiqirencongduandaosilijiancezhuangzhijifangfa)




[//]: # (This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML. )
