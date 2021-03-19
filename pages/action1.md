---
title: Project-Action 1
description: 3D Data acquisition
background: /assets/img/trans_action3_tests1.jpg
permalink: /action1/
---


{: .alert .alert-info}
3D Data acquisition & processing :

The objective of this first action is to provide the 3D models of the reference sites which will then be integrated into the immersive simulations developed within the framework of the project. The first step was to select a site in each country. The selection was made according to the "accidentogenic" nature of the sites (informed by the police on Mons side and by the road services on Douai side) and their similarity. A further constraint was that these sites had to be "conflict zones" between users of the road network, i.e. in the case of our study a place where vehicles and vulnerable users, in this case pedestrians, meet. 

![Project partners](https://raw.githubusercontent.com/numediart/Transimmersium/main/assets/img/trans_Action1_scan2.jpg)
_View on the point cloud acquired with the 3D scanner on the Douai (France) roundabout._

The final choice was thus made for the "roundabout at the heart" (GPS coordinates 50.461513755987795, 4.0158517917947) for MONS and the roundabout on Place l'Hérillier (GPS coordinates 50.363013, 3.078429) for DOUAI. The starting point for the models is the capture of a "point cloud" representing the geometry of the site. The device used for this purpose is a high-resolution B.I.M. (Building Information Modeling) scanner with a range of 70 m, made by FARO. Given the size of the sites chosen, several acquisitions at different locations (known as "stations") are necessary to create each of the required point clouds, as the scanner's range is too limited. Moreover, acquiring the cloud from several stations increases the resolution and accuracy of the final cloud. 

![Project partners](https://raw.githubusercontent.com/numediart/Transimmersium/main/assets/img/trans_action1.jpg)
_Process of the 3D data acuiqition and import into the Unity software (which can be used on the VR headset)._

For both the Mons and Douai sites, the operations carried out followed the same protocol:  
* Preparation of the acquisitions from close maps from googlemaps representing the area over approximately 80 m by 80 m. These enable the various stations to be placed so that they can cover the entire site while presenting sufficient "overlaps" to facilitate the aggregation of the data acquired at the various points into a global cloud associated with the site. The measurement at each station takes 6 to 8 minutes, depending on the resolution required (the points are measured with an average uncertainty of only a few millimetres). 
* All the data collected at each station must then be assembled into a single cloud. This "recording" phase is carried out using FARO's SCENE software. This aggregation process uses the GPS data attached to each acquisition on the one hand, as well as the common parts (overlaps) of some of them on the other hand. When necessary, this process can be assisted by manually indicating to the programme visual cues appearing in different acquisitions (panels, walls, elements of urban furniture, etc.). At the end of this second phase, we obtain a point cloud representative of the site, comprising several tens of millions of 3D points with their associated colours. This can already be used in the context of virtual reality (VR) simulation, but it is a rather cumbersome representation to handle. Wherever possible, it is preferred to generate surfaces (at least for typical subparts of the point cloud, such as the central sculptures at the two sites) offering a more realistic final rendering in a compact and efficient form to be manipulated by VR software. 
* This final stage of surface generation (or "meshing") was carried out using the open-source "meshlab" software. This meshing operation comprises two steps, firstly the association of the cloud points by triangles forming the "facets" of the surface, and secondly the calculation of the associated "texture". The calculation of the surface elements ("triangles") begins by determining the normals associated with the facets. Many algorithms are available to determine the triangles. Here we have used "ball pivoting" which gives good results but sometimes generates "holes" in the resulting surface. As mentioned above, the texture associated with the surface is calculated by transferring the colour attributes of the facet points to the facets. The post-processing of each of the point clouds is an operation that takes from a few days to a week. It should be noted that the acquisitions were made on 10 January 2020 for the Mons site and on 16 December 2020 for the Douai site.

{: .alert .alert-info}
Proofs - videos of Mons and Douai roundabouts :

<iframe width="560" height="315" src="https://www.youtube.com/embed/Rt71vzozXPI" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
_Point cloud acquisition - Douai roundabout_

The above video shows the result of the 3D acquisition of the data on the Douai (France) site with several sites for the 3D scanner. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/euBft04QYMw" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
_Meshing of the Mons roundabout_

The second video shows the result for the Mons roundabout (Belgium) after cloud processing and applying meshes. 

---

![Project partners](https://raw.githubusercontent.com/numediart/Transimmersium/main/assets/img/trans_partners.jpg)
_Transimmersium micro-project is funded by Interreg France, Wallonie, Vlaanderen._

---