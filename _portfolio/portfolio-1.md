---
title: "Portfolio item number 1"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/500x300.png'>"
collection: portfolio
---



### <a name="journal"></a> 1. Geometric Decision-based Attack (GeoDA)

 GeoDA is  a black-box attack framework to generate adversarial example for image classifiers.  We propose a geometric
framework to generate adversarial examples in one of the
most challenging black-box settings where the adversary
can only generate a small number of queries, each of them
returning the top-1 label of the classifier. Our framework
is based on the observation that the decision boundary of
deep networks usually has a small mean curvature in the
vicinity of data samples. GeoDA got accepted to CVPR 2020. You can find the full paper [here](https://arxiv.org/abs/2003.06468).


<p align="center">
<iframe width="560" height="315" src="https://www.youtube.com/embed/Io-XGf59EFc" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

</p>






#### Linearizing the decision boundary
Given a boundary point, the decision boundary at the vicinity of a data point can be locally
approximated by a hyperplane passing through the boundary point. The goal is pretty much to estimate the normal vector to the boundary.


<p align="center"><img src="https://user-images.githubusercontent.com/36679506/81717788-fd830600-9448-11ea-9dff-d443f956662b.gif" /></p>


 

#### A few examples on the performance of the GeoDA for different norms



<p align="center"><img src="https://user-images.githubusercontent.com/36679506/75689719-aa821b00-5c6f-11ea-9b6b-b78ff3ed871b.jpg" /></p>



#### More examples with magnified perturbations for better visibility

<p align="center"><img src="https://user-images.githubusercontent.com/36679506/81288488-bf45ab00-9032-11ea-8ba3-f7b22384f34c.png" /></p>



#### Code

The Pytorch implementation of GeoDA can be found [here](https://github.com/thisisalirah/GeoDA).

----
----



### <a name="journal"></a> 2. Interference avoidance trajectory design for UAVs
Taking advantage of the inherent mobility feature of the
UAVs an adaptive interference avoidance scheme is developed.
Using the proposed scheme, the UAVs can effectively
reconfigure their positions to avoid the interference and
improve the data flow from the source(s) to the destination(s).
The weighted Cheeger constant for 3D scenarios is
introduced as an effective metric to improve the UAVs
network connectivity. This work got accepted to INFOCOM 2019, and the full paper can be found [here](https://ieeexplore.ieee.org/abstract/document/8737472).

Simple demos of the proposed trajectory design are shown in the following animated figures. In the figures for trajectory of the UAVs, the circles show the final locations of the UAVs, while the beginning of the lines show the initial locations of the UAV relays.



Single interferer          |  Multiple interferer (top view)         | Multiple interferer (3D view)
:-------------------------:|:-------------------------:|:-------------------------:
![1jammer-3dview](https://user-images.githubusercontent.com/36679506/78077557-90268480-7376-11ea-9d85-3ede02389ba0.gif) |  ![3jammers-topview](https://user-images.githubusercontent.com/36679506/78078145-9ec16b80-7377-11ea-8ed0-48ccf626b9a3.gif)| ![Scenario 2- 3d view](https://user-images.githubusercontent.com/36679506/78078392-168f9600-7378-11ea-919d-698a0eb6fae3.gif)

 ----
