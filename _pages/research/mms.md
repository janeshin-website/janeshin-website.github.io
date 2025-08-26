---
layout: page
title: Minimal Multi-Modal Sensing for Task Completion in Uncertain Environments
permalink: /research/:slug/
image: '/images/research/mms.png' # representative figure
description: Robots are generally adapted with a rich sensor suite, but using all of them at all times is inefficient and power hungry. Can a minimal subset of required sensors be selected that maintains a maximal localization uncertainty?
---

## Overview <!-- Must include -->

Robots equipped with rich sensor suites can localize reliably in partially-observable environments, but powering every sensor continuously is wasteful and often infeasible. Belief-space planners address this by propagating pose-belief covariance through analytic models and switching sensors heuristically--a brittle, runtime-expensive approach. Data-driven approaches--including diffusion models--learn multi-modal trajectories from demonstrations, but presuppose an accurate, always-on state estimate.

## Research Goals <!-- Remove if not applicable -->

* Choose a minimal subset of sensors
* Create semantic maps for any available sensor
* Generate a sensor agnostic map representation
* Localize and Navigate with minimal sensing capabilities

## Related Publications <!-- Remove if not applicable -->

1. Puthumanaillam, G., Penumarti, A., Vora, M., Padrao, P., Fuentes, J., Bobadilla, L., Shin, J., & Ornik, M., "Belief-Conditioned One-Step Diffusion: Real-Time Trajectory Planning with Just-Enough Sensing," *Accepted to 9th Conference on Robot Learning (CoRL) as Oral Presentation*

## Research Team <!-- Remove if not applicable -->

UF Team: [Aditya Penumarti](people/aditya), [Jane Shin](people/jane)
External Collaborators: Gokul Puthumanaillam, Manav Vora, Paulo Padrao, Jose Fuentes, Leonardo Bobadilla, Melkior Ornik

## Acknowledgement

This work is completed in collaboration with University of Illinois - Urbana Champaign, Florida International University and Providence University.

<div style="display:grid;grid-auto-flow:column;grid-auto-columns:minmax(0,1fr);gap:32px;justify-items:center;align-items:center;max-width:900px;margin:0 auto;">
  <a href="https://illinois.edu" target="_blank" rel="noopener"><img src="/images/research/logos/uiuc.png" alt="UIUC" style="height:70px;max-width:180px;object-fit:contain;"></a>
  <a href="https://www.fiu.edu" target="_blank" rel="noopener"><img src="/images/research/logos/fiu.png" alt="FIU" style="height:70px;max-width:180px;object-fit:contain;"></a>
  <a href="https://www.providence.edu" target="_blank" rel="noopener"><img src="/images/research/logos/providence.jpg" alt="Providence College" style="height:70px;max-width:180px;object-fit:contain;"></a>
</div>

<!-- Include below if you have additional resources to add (e.g. interview videos) -->
***

<!-- ## Additional Resources

### Youtube Embed

<p><iframe src="https://www.youtube.com/embed/2b2gJu-g3qE" loading="lazy" frameborder="0" allowfullscreen></iframe></p>

### Vimeo Embed

<p><iframe src="https://player.vimeo.com/video/148003889?h=d36b8b4cbb" loading="lazy" width="640" height="360" frameborder="0" allowfullscreen></iframe></p> -->
