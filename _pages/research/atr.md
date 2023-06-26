---
layout: page
title: Underwater Robot Planning with Imaging Sonar
permalink: /research/:slug/
image: '/images/research/UESonarSim.png' # representative figure
description: We aim to develop an autonomous underwater system that can be aware of information and uncertainty.
---

## Overview <!-- Must include -->
Unlike camera images, SONAR images are very noisy and vary greatly depending on the viewing angle of an object, because the highlight and shadow pattern in the obtained images is changed based on the angle of the reflected surface. These properties of SONAR imagery require the robots to obtain observations from multiple views to achieve satisfactory classification performance, leading to a time-consuming mission. To tackle this problem, an information-driven sensor path-planning algorithm has been proposed so that the underwater robot can minimize the operation time while achieving a satisfactory classification performance by only obtaining informative observation. In order to overcome the nature of data-poor environment and unexpected various seabed conditions, a photo-realistic game engine has been developed to implement various environments, such as sand ripples and muds. We aim to utilize this simulation tool to overcome challenges in autonomous target recognition within an unexpected underwater environment.

## Research Questions <!-- Remove if not applicable -->
* How can we optimize the UUV's path to minimize the travel time and achieve satisfactory confidence level?
* How can we overcome the nature of data-poor environment?
* How can a UUV with imaging sonar sensors operate with various seabed conditions?

## Related Publications <!-- Remove if not applicable -->
1. J. Shin, S. Chang, M. J. Bays, J. Weaver, T. A. Wettergren and S. Ferrari, "Synthetic Sonar Image Simulation with Various Seabed Conditions for Automatic Target Recognition," *OCEANS 2022, Hampton Roads*, Hampton Roads, VA, USA, 2022, pp. 1-8, doi: 10.1109/OCEANS47191.2022.9977275.
1. J. Shin, S. Chang, J. Weaver, J. C. Isaacs, B. Fu and S. Ferrari, “Informative Multiview Planning for Underwater Sensors,” in *IEEE Journal of Oceanic Engineering*, vol. 47, no. 3, pp. 780-798, July 2022, doi: 10.1109/JOE.2021.3119150
1. S. Chang, J. Isaacs, B. Fu, J. Shin, P. Zhu, and S. Ferrari, “Confidence level estimation inmulti-target classification problems,” *Proc. SPIE*, vol. 10628, 2018, Art. no. 1062818.

## Research Team in APRILab
[Jane Shin](/people/jane), [Nikhil Iyer](/people/nikhil), [Sunmo Koo](people/sunmo)

<!-- ## Acknowledgement
This work is supported by XXX through grant XXX. I think I should put logos here as well. -->

<!-- Include below if you have additional resources to add (e.g. interview videos) -->
<!-- ***

## Additional Resources

### Youtube Embed
<p><iframe src="https://www.youtube.com/embed/2b2gJu-g3qE" loading="lazy" frameborder="0" allowfullscreen></iframe></p>

### Vimeo Embed

<p><iframe src="https://player.vimeo.com/video/148003889?h=d36b8b4cbb" loading="lazy" width="640" height="360" frameborder="0" allowfullscreen></iframe></p> -->