---
title: "Application of physics-informed neural networks for two-phase flow model with variable diffusion and experimental validation"
collection: publications
permalink: /publication/2025-05-30-paper-App-PINN-2phase-var-diff
excerpt: "<img src='/images/publications/bond_sand_production_polymer.jpg' style='float:left;width:293px;height:120px;'>"
date: 2025-05-30
venue: 'Results in Engineering'
paperurl: 'https://doi.org/10.1016/j.rineng.2025.105439'
citation: 'Kazidenov, D., Omirbekov, S., Zhanabayeva, M., & Amanbek, Y. (2025). Experimental and numerical study of the effect of polymer flooding on sand production in poorly consolidated porous media. Geoenergy Science and Engineering, 213746.'
---

"Recent advancements in deep learning have significantly improved solving complex computational physics
problems. This paper presents Physics-Informed Neural Networks (PINNs) with a spatially-dependent diffusion
function to model two-phase flow in porous media, explicitly addressing the Buckley-Leverett problem. The
study analyzes the PINNs using different approaches, including diffusion term and modification flux function to
convex hull, employing both Multi-Layer Perceptron (MLP) and Attention-based neural network architectures.
In addition, we investigate the application of the PINNs for laboratory experimental data by assessing the
performance of PINNs in capturing the saturation front dynamics. Our results indicate that while the attentionbased model achieves slightly higher accuracy, it is significantly time-consuming. In contrast, the MLP is the more
efficient in terms of training time with a speedup in the range of 7 − 13. A sensitivity analysis on the constant
diffusion coefficient shows that PINNs can approximately capture the pattern of the saturation front. We have
found that adapting the spatial-dependent diffusion function provided better accuracy with the experimental data
compared to using a constant diffusion coefficient."
 
 
 <figure>
  <p align="center">
  <div class="image_resize">
  <img src="/images/animations/Sand_production_polymer.gif"  alt="">
  <figcaption> Fracture initiation by injecting XG polymer.</figcaption>
  </div>
  </p>
</figure>

