---
title: "Application of physics-informed neural networks for two-phase flow model with variable diffusion and experimental validation"
collection: publications
permalink: /publication/2025-05-30-paper-App-PINN-2phase-var-diff
excerpt: "<img src='/images/publications/Appl_PINN_2phase_var_dif.png' style='float:left;width:210px;height:120px;object-fit:contain;margin-right:5px;margin-bottom:5px;'>"
date: 2025-05-30
venue: 'Results in Engineering'
paperurl: 'https://doi.org/10.1016/j.rineng.2025.105439'
citation: 'Kalesh, D., Merembayev, T., Omirbekov, S., & Amanbek, Y. (2025). Application of physics-informed neural networks for two-phase flow model with variable diffusion and experimental validation. Results in Engineering, 26, 105439.'
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
  <img src="/images/publications/polynomial_epsilon_upd.png"  alt="">
  <figcaption> PINN solution with variable diffusion </figcaption>
  </div>
  </p>
</figure>

