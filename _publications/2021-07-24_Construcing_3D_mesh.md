---
title: "Constructing 3D mesh indoor room layouts from 2D equirectangular RGB 360 panorama images for the Unity game engine"
collection: publications
permalink: /publications/2021-07-24_Construcing_3D_mesh
excerpt: 'We use AI to construct 3D room layout from 2D images for Unity VR projects.'
date: 2021-07-24
paperurl: 'https://doi.org/10.1007/978-3-030-78645-8_19'
page_url: 'https://doi.org/10.1007/978-3-030-78645-8_19'
citation: 'Chan, J. C. P., Ng, A. K. T., & Lau, H. Y. K. (2021). Constructing 3D mesh indoor room layouts from 2D equirectangular RGB 360 panorama images for the Unity game engine. In C. Stephanidis, M. Antona, & S. Ntoa (Eds.), <i>Communications in computer and information science: Vol. 1421. HCI international 2021 - Posters</i> (pp. 148–155). Springer.'
---
We use AI to construct 3D room layout from 2D images for Unity VR projects.

Abstract:
To accelerate digital 3D environments creation, we propose a workflow utilizing neural network systems to create 3D indoor room layouts in the Unity game engine from 2D equirectangular RGB 360 panorama images. Our approach is inspired by HorizonNet, which generates textured room layouts in point clouds using Recurrent Neural Network (RNN). However, it is not desirable in VR since data points can be visible at close ranges, and thus, break user immersion. Alternatively, we used 3D meshes that are connected with small triangular faces, which stitch together with no gaps in between, simulating realistic solid surfaces. We succeeded in converting room layout representations from point cloud to 3D mesh, by extracting rooms’ metadata predicted by HorizonNet, and dynamically generating textured custom mesh in Unity. Mesh layouts can be directly applied into Unity VR applications. Users can take 360 images on their mobile phones and visualize room layouts in VR through our system. As our evaluations suggest, mesh layout representation improves frame rates and memory usage and does not affect the layout accuracy of the original approach, providing satisfactory room layout for VR development.
