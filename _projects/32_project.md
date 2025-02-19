---
layout: page
title: ARCNC
description: Virtual planning, control, and machining for a modular-based automated factory operation in an augmented reality environment
img: assets/img/ARCNC_main.jpg
importance: 33
category: work
youtubeId: 2pYTsD5i1Is
--- 

{% include youtubePlayer.html id=page.youtubeId %}

This study presents a modular-based implementation of augmented reality to provide an immersive experience in learning or teaching the planning phase, control system, and machining parameters of a fully automated work cell. The architecture of the system consists of three code modules that can operate independently or combined to create a complete system that is able to guide engineers from the layout planning phase to the prototyping of the final product. The layout planning module determines the best possible arrangement in a layout for the placement of various machines, in this case a conveyor belt for transportation, a robot arm for pick-and-place operations, and a computer numerical control milling machine to generate the final prototype. The robotic arm module simulates the pick-and-place operation offline from the conveyor belt to a computer numerical control (CNC) machine utilising collision detection and inverse kinematics. Finally, the CNC module performs virtual machining based on the Uniform Space Decomposition method and axis aligned bounding box collision detection. The conducted case study revealed that given the situation, a semi-circle shaped arrangement is desirable, whereas the pick-and-place system and the final generated G-code produced the highest deviation of 3.83mm and 5.8mm respectively.

Paper link <a href='https://yunsuenpai.com/assets/pdf/virtualplanning.pdf'>here</a>.