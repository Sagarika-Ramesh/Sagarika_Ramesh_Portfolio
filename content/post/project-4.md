---
date: 2022-03-12T11:14:48-04:00
description: "A model that constructs a 3D scene"
featured_image: "/images/proj4.png"
title: "Database Assisted Object-Retrieval 3D Room Reconstruction"
---
* Developed a model that takes a 2D image as input and generates a 3D scene that contains corresponding 3D
furniture objects.
* Used Mask-RCNN to extract 2D instances. 
* Attention-driven fine-grained visual classifier is used to predict 3D
model database id that best matches furniture objects and the 3D objects are retrieved. 
* Obtained an accuracy of 95%

{{< figure src="/images/proj4-1.png" >}} 
{{< figure src="/images/proj4-2.png" >}}
{{< figure src="/images/proj4-3.png" >}}

[Link to GitHub Repository](https://github.com/Sagarika-Ramesh/Database-Assisted-Object-Retrieval-3D-Room-Reconstruction)