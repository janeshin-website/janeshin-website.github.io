---
layout: page
title: Information Fusion for Automatic Target Acquisition using Heterogeneous Sensors
permalink: /research/:slug/
image: '/images/research/ATA.png' # representative figure
description: How can we update our information when different sensors give conflicting information?
---

## Overview <!-- Must include -->
A team of mobile robotic agents can outperform single-agent system by equipping heterogeneous sensors to gather information in various aspects. For example, equipping an IR imaging sensor in addition to an RGB camera sensor can increase sensing robustness and performance as IR can provide features related to temperature when RGB may fail due to unexpected light conditions, and vice versa. However, some information extracted from multiple sensors can conflict depending on the environmental conditions and each sensor's physical properties. In some practical settings, only decision-level fusion is available to implement real-time fusion. In these scenraios, we can receive a series of decisions (extracted information) about a target. Our goal is to fuse these decisions from different sensing sources, which may conflict, to identify the target class.

## Research Questions <!-- Remove if not applicable -->
* How can we fuse conflicting information from multiple sources without any additional information?
  * It is assumed that other informaiton (e.g., occlusion or agent's pose) is not available.
* How can we address temporal information in this fusion?
* How can we choose the best next sensor to obtain additional information?

<!-- ## Related Publications
1. Cite publication with IEEE reference style. Then list the links to paper, slides, videos, codes per each item
1. Cite publication with IEEE reference style. Then list the links to paper, slides, videos, codes per each item -->

## Research Team
Zijing Huang, Jane Shin with other collaborators (Kyle Volle, Prashant Ganesh, Mike Moore)

## Acknowledgement <!-- Remove if not applicable -->
This work is partially supported by Air Force Research Lab through FA8651-22-F-1052.

<!-- Include below if you have additional resources to add (e.g. interview videos) -->
***