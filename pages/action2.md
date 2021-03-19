---
title: Project-Action 2
description: VR Model & Simulation
background: /assets/img/trans_action3_tests1.jpg
permalink: /action2/
---

{: .alert .alert-info}
VR Model & Simulation :

The objective of this second action is to use the data provided in action 1 in order to 1) set up a VR simulation environment and 2) develop scenarios in the simulation to obtain maximum results. 
For the first axis, a car simulation has been set up by integrating and adapting a Unity asset, the ["Road & Traffic System"](http://wireddevelopments.com/trafficsystem/). A complete circuit was set up so that the cars could continue to circulate around the roundabout. In addition, on this circuit several specific zones have been created. There are areas where cars can change color and switch the headlights on or off (with a certain probability of having faulty headlights for one or both headlights). These zones allow the cars encountered in the roundabout to look different and not always encounter the same ones. 
Finally, pedestrian crossing zones have also been set up where cars stop in case pedestrians cross (with a certain probability leaving the possibility that some cars do not stop at the pedestrian crossing). 

![Project partners](https://raw.githubusercontent.com/numediart/Transimmersium/main/assets/img/trans_action2.jpg)
_["Road & Traffic System"](http://wireddevelopments.com/trafficsystem/) Unity asset screenshot._

For the second axis, in pedestrian crossing areas it is possible to detect a pedestrian/car collision (accident). Moreover, it is possible to predict the number of cars, and different probabilities on the characteristics of the cars but also of certain weather conditions. The pedestrian will have three different possible starting points. It is possible to simulate different weather conditions (day, night, sunset, fog, rain) and also different medical situations (deaf, myopic, one-eyed). For each scenario it is possible to give : 
* The starting point of the pedestrian (among the 3 possible ones)
* The time of day (day, sunset, night and even a specific time)
* The weather (clear, fog with its coefficient of fog, rain)
* Medical condition (healthy, deaf, myopic, right blind, left blind)

During this action, the two roundabouts, Belgian and French, were implemented in the same way. 

{: .alert .alert-info}
Proofs - Unity interface screenshots & video :

![Project partners](https://raw.githubusercontent.com/numediart/Transimmersium/main/assets/img/trans_action3_interface.jpg)
_Screenshots of the Unity interface : starting point, weather, day time, visibility, medical conditions. In addition there are the day time hours, the fog parameters and the probabilities for car lights (used only in night scenarios)_

![Project partners](https://raw.githubusercontent.com/numediart/Transimmersium/main/assets/img/trans_action3_tests1.jpg)
_Screenshots from the VR headset for  conditions : Night/Clear/Deaf (left), Night/Rain/Myopia (center), Night/Fog/Healthy (right)._

![Project partners](https://raw.githubusercontent.com/numediart/Transimmersium/main/assets/img/trans_action3_tests2.jpg)
_Screenshots from the VR headset for  conditions : Day/Clear/Healthy (left), Day/Rain/No right eye (center), Day/Fog/No left eye (right)._

![Project partners](https://raw.githubusercontent.com/numediart/Transimmersium/main/assets/img/trans_action3_tests3.jpg)
_Screenshots from the VR headset for  conditions : Twilight/Fog/Deaf (left), Twilight/Clear/Myopia (center), Twilight/Rain/Healthy (right)._

<iframe width="560" height="315" src="https://www.youtube.com/embed/MvlZir2HDqg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
_Example of video with the interface and the view of the user when making a tour of the roundabout_

---

![Project partners](https://raw.githubusercontent.com/numediart/Transimmersium/main/assets/img/trans_partners.jpg)
_Transimmersium micro-project is funded by Interreg France, Wallonie, Vlaanderen._

---