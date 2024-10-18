---
layout: post
title: Robotic Bronchoscopy with Variable-Stiffness Catheter 
subtitle: New method for lung cancer biopsy
cover-img: /assets/img/robot.jpg
thumbnail-img: /assets/img/therobot.png
tags: [surgical robot]
comments: true
mathjax: true
author: Xing-Yu Chen 
---

{: .box-success} 
This work presents a teleoperated robotic bronchoscopy system, featuring a controllable variable-stiffness catheter that enhances stability and flexibility during transbronchial biopsies. The 7 DoF robotic system allows for translation, rotation, and bending of the bronchoscope; delivery and bending of the catheter; delivery and control of biopsy tools; as well as stiffness adjustment of the catheter, which adapts to the dynamic pulmonary environment to provide stable support during tissue sampling. 

## Robotic Bronchoscopy System with Variable-Stiffness Catheter for Pulmonary Lesion Biopsy




### System Overview

The system comprises a teleoperated surgical robot specifically designed for trans-respiratory diagnosis, incorporating a three-stage design scheme that includes a bronchoscope, novel variable-stiffness catheters, and biopsy forceps. The robot is mounted on a 5 DoF passive robotic arm to achieve the appropriate angle of intervention. Surgeons use tablets as the remote control system to teleoperate the three endoscopic instruments, inserting them through the patient’s trachea and utilizing them for precise movements. Employing a multi-operator strategy, the robot is controlled through a scheduling arrangement and weight distribution, allowing mentor surgeons and trainee surgeons to observe the same surgical site and collaboratively control the surgical instruments simultaneously. Compared to the surgeon
console of the Da Vinci surgical robot, Force Dimension’s haptic devices, and other custom-made master control units, this HMI allows for quick integration of new features, making it convenient for prototyping. However, it lacks physical feedback and cannot provide similar force feedback information, which may increase the risk of operational hazards. Prolonged use of the touchscreen may also cause fatigue in the fingers or hands
of the surgeon. Additionally, there are security concerns in wireless environments. Future improvement will transfer the control algorithm to a more ergonomic surgeon console.

![Crepe](https://chen-xing-yu.github.io/assets/img/therobot2.png){: .mx-auto.d-block :}




| Endoscopic Intruments | Parameters | Size   |
|:----------------------|:--- |:-------|
| Bronchoscope                  | Outside Diameter    | 5.2 mm |
| Bronchoscope                   | Inside Diameter | 2.6 mm |
| Variable-Stiffness Catheter                 | Outside Diameter  | 2.4 mm |
| Variable-Stiffness Catheter                   | Inside Diameter | 1.2 mm |
| Biopsy Forceps|Diameter|1.0 mm |




### Multimodal Navigation System
Bronchoscopic images provide the most intuitive visual
information, reflecting the internal condition of the lungs
in real-time. However, due to their first-person perspective,
these images do not reveal the bronchoscope’s position within
the lungs. To address this limitation, the robot employs a
multimodal navigation system, which includes bronchoscopic
videos, electromagnetic (EM) sensors, and C-Arm fluoroscopy.

A 6-DoF EM sensor with position accuracy of 0.48 mm
and orientation accuracy of 0.30° from Northern Digital Inc.
is attached to the tip of bronchoscope to enable real-time
navigation and tracking of the surgical instruments. This
sensor provides information about the spatial position and
orientation (roll, pitch, and yaw) of the bronchoscope. A field
generator placed beside or under the patient generates an EM
field of known geometry. As the EM sensor moves within this
field, its spatial position and orientation are measured. The
open-source software 3D Slicer is used to visualize the spatial
position and orientation of the bronchoscope within lungs, as
shown in Fig. 3.
Hounsfield Unit (HU) values for many metals and alloys
are higher than those of the human body [26] [27], making
fluoroscopic X-ray particularly suitable for positioning the
biopsy forceps and variable-stiffness catheter with low melting
point alloy, especially during the clamping action in biopsy
procedures. In the C-Arm medical imaging system, the Xray
generator and detector are positioned on a C-shaped arm,
directly opposite and centrally aligned with each other. The
C-Arm fluoroscopy system is capable of controlled rotation,
allowing for imaging from various angles and positions.
D. 

![Crepe](https://chen-xing-yu.github.io/assets/img/navi.png){: .mx-auto.d-block :}

### Three-stage robotic bronchoscopy procedure

A novel three-stage robotic bronchoscopy procedure proposed
in Fig. 4 involves the control of the bronchoscope,
variable-stiffness catheter, and biopsy instruments. The surgery
includes three types of operations: individual device control,
dynamic adjustment, and biopsy procedure. In the first step,
surgeons use tablets to navigate the bronchoscope robot to the
target position, involving motions such as delivery, rotation,
and tip bending. In the second step, the variable-stiffness
catheter is heated and maintained at a safe temperature of 53°C
to decrease its stiffness. Subsequently, the softened catheter
is inserted through the bronchoscope’s working channel. Its
dynamic stiffness can be adjusted based on factors such as
heartbeat and respiration. Compared to the bronchoscope,
the variable-stiffness catheter can be inserted into narrower
bronchi and offers more flexible control with the driving
tendon. Once the softened catheter reaches the precise location
of the targeted lesion, the current to the heating resistance wire
is disconnected. This discontinuation of heat allows the low
melting point alloy to cool naturally, restoring the catheter’s
stiffness.

![Crepe](https://chen-xing-yu.github.io/assets/img/pairing.png){: .mx-auto.d-block :}