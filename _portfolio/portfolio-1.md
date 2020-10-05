---
title: "GeoDA: a Desicion-based Adverarial Attack"
excerpt: "GeoDA is a black-box attack framework to generate adversarial example for image classifiers. We propose a geometric framework to generate adversarial examples in one of the most challenging black-box settings where the adversary can only generate a small number of queries, each of them returning the top-1 label of the classifier. 
<br/><img align="center" src='https://user-images.githubusercontent.com/36679506/81717788-fd830600-9448-11ea-9dff-d443f956662b.gif'>"
collection: portfolio
---

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


## Linearizing the decision boundary
Given a boundary point, the decision boundary at the vicinity of a data point can be locally
approximated by a hyperplane passing through the boundary point. The goal is pretty much to estimate the normal vector to the boundary.


<p align="center"><img src="https://user-images.githubusercontent.com/36679506/81717788-fd830600-9448-11ea-9dff-d443f956662b.gif" /></p>

## A few examples on the performance of the GeoDA for different norms



<p align="center"><img src="https://user-images.githubusercontent.com/36679506/75689719-aa821b00-5c6f-11ea-9b6b-b78ff3ed871b.jpg" /></p>



## More examples with magnified perturbations for better visibility

<p align="center"><img src="https://user-images.githubusercontent.com/36679506/81288488-bf45ab00-9032-11ea-8ba3-f7b22384f34c.png" /></p>



## Code

The Pytorch implementation of GeoDA can be found [here](https://github.com/thisisalirah/GeoDA).

----
