---
title: "Optical image analysis for graphene layer detection: Enhanced green channel methodology"
collection: publications
category: manuscripts
permalink: /publication/2024-09-optical
excerpt: "<ul>
                <li>Enhanced green channel thresholding for effective segmentation of graphene layers in optical images with variable lighting.</li>
                <li>The thresholding can be fine-tuned and adjusted according to the lighting condition.</li>
                <li>It can detect the subtle variation in contrast at the layer edges.</li>
                <li>Image analysis shows a universal pattern in the green channel pixel median value.</li>
                <li>Intersection over union metric (IoU) yielded 94 %, and 89 % accuracy for monolayer and bilayer respectively.</li>
          </ul>"
date: 2024-09
venue: 'Computational Materials Science'
paperurl: 'https://doi.org/10.1016/j.commatsci.2024.113198'
---
### Abstract
Graphene, a material of increasing research interest, requires accurate layer identification due to its sensitivity to layer count. Existing methods for graphene layer number identification are either time-consuming or of low accuracy, with high-accuracy methods often requiring expensive processes. This paper aims to address this challenge by proposing a cost-effective and efficient approach. Specifically, the current work highlights only the green channel—one of the three primary color channels (red, green, blue) that make up an optical image—from images of exfoliated graphene flakes for layer count identification. A linear regression is performed between pixel position and substrate green channel value, and this effect is subtracted from the entire optical image to mitigate background effects. By storing the range of green channel values for each type of flake (monolayer, bilayer, or tri-layer) based on a few images, we establish thresholds for identifying different types of layers in a particular setup. Additionally, our methodology allows for flexible threshold tuning using a single reference image, enabling adjustment to changes in detection setup such as illumination level, magnification, or microscope used. Demonstrating high accuracy and flexibility, this methodology presents a suitable technique for graphene layer number identification without the need for large datasets or expensive instruments.
  
<img src="/images/graphical-abstracts/optical-2024-09.jpg" width="600px" height="400px">
