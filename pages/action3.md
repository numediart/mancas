---
title: Project-Action 3
description: VR Model & Simulation
background: /assets/img/trans_action3_tests1.jpg
permalink: /action3/
---


{: .alert .alert-info}
VR Model & Simulation :

During this third action, the recovery of various data from the VR HTC Vive Pro Eye headset was implemented. From the software interface, it is possible to recover all the information and save it in XML files. These files contain information about the person taking the test, their position, the direction of their head, the direction and position of their eyes, the position of cars at pedestrian crossings, etc.... For each person, we get as many XML files as tests performed (here nine tests per person). 
A test scenario was developed jointly for the tests in Belgium and France in order to standardize the measurements and keep the test duration under 20 minutes :
* In a first step, the eye-tracking is calibrated in relation to the user's head and by following a moving point with the eyes. This calibration is very quick and easy to implement. 
* In a second step, the user uses the HTC Vive joystick to move around the roundabout. He is instructed to go around the roundabout as quickly as possible, preferably avoiding accidents. His journey starts in one of the three possible starting positions. If a person does not feel well during the test, they can rest and then start again with a recalibration of the eyes. 

![Project partners](https://raw.githubusercontent.com/numediart/Transimmersium/main/assets/img/trans_action3_pipeline.jpg)
_Experiments : scenarios and practical organization._

For each of the nine configurations tested, a majority of people went around the roundabouts counter-clockwise and a minority clockwise. Myopia was the most disabling medical situation regardless of the weather conditions or time of day.   
Testing was made more complex than expected due to the COVID-19 epidemic. In addition to the need to disinfect all the equipment between two users, it was much more difficult to recruit people for the tests, most of whom work remotely. However, we carried out about ten tests in Mons and the same number in Douai. Documents related to data confidentiality have been signed by the users and will be attached to the results. 
We have set up a data processing that was not foreseen in the project with scripts that allow data extraction (car accident, pedestrian trajectory...), 
gaze direction, head direction, ...) and display them and check the quality of these data. These tests have shown that, apart from some people who wear glasses inside the VR helmet, the results are consistent and can be used for further analysis. 
In this sense, following action 3, a proof of concept (POC) was obtained showing that the entire pipeline of data acquisition, data processing, simulator set-up and eye-tracking data acquisition is feasible. Thanks to this tool it is now possible to analyse these data in order to set up strategies for optimizing the infrastructure in the present road case but which could also be applied in the simulation of dangerous situations, training and learning situations or serious games or games. 

{: .alert .alert-info}
Proofs - Unity video and first results :

![Project partners](https://raw.githubusercontent.com/numediart/Transimmersium/main/assets/img/trans_action3_trajectory.jpg)
_Example of data output : user path from positions history (gray line), pedestrian corssing (green), potential accidents (cars versus people position). Head and eye directions are also available to check where the user is looking to understand why this accident occured._

<iframe width="560" height="315" src="https://www.youtube.com/embed/MvlZir2HDqg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
_Example of video with the interface and the view of the user when making a tour of the roundabout_


---

![Project partners](https://raw.githubusercontent.com/numediart/Transimmersium/main/assets/img/trans_partners.jpg)
_Transimmersium micro-project is funded by Interreg France, Wallonie, Vlaanderen._

---