<!-- ---
permalink: /
title: "About"
excerpt: "Yerlan Amanbek — numerical methods, scientific computing, and physics-informed machine learning."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am an **Assistant Professor** in the **School of Computing and Artificial Intelligence (SCAI)** at **Nazarbayev University**, Astana, Kazakhstan.

I develop and analyze numerical methods for partial differential equations, with applications to **flow and transport in porous media**. My research combines numerical analysis, scientific computing, and physics-informed machine learning to study complex physical systems.

[Publications]({{ '/publications/' | relative_url }}){: .btn .btn--primary}
[Curriculum Vitae]({{ '/cv/' | relative_url }}){: .btn}
[Students]({{ '/students/' | relative_url }}){: .btn}

## Research interests

My work connects mathematical theory with computational modeling and experimental validation. Applications include subsurface energy systems, CO₂ storage, groundwater remediation, and coupled fluid–particle processes.

- **Numerical methods and analysis:** finite element and mixed finite element methods, multiscale modeling, adaptive numerical homogenization, domain decomposition, and a priori and a posteriori error estimation.

- **Porous media and multiphase flow:** numerical simulation of flow and transport in heterogeneous formations, reservoir modeling, polymer flooding, and geological CO₂ storage.

- **Scientific machine learning:** physics-informed neural networks for two-phase flow and variable-diffusion problems, together with machine learning approaches to fracture network modeling.

- **Coupled simulation and computational applications:** computational fluid dynamics–discrete element method (CFD–DEM) modeling of sand production and fracture processes, as well as finite element and isogeometric methods for financial models.

## Research in focus

### Flow and transport in heterogeneous porous media

Variations in subsurface properties can strongly affect fluid movement and transport. I study numerical methods that capture these effects across spatial and temporal scales, with an emphasis on accuracy and computational efficiency.

<figure>
  <img
    src="{{ '/images/animations/SPE10_L37_simulation.gif' | relative_url }}"
    alt="Animation of a numerical tracer transport simulation using the heterogeneous SPE10 reservoir benchmark."
    loading="lazy"
    style="display: block; max-width: 100%; height: auto; margin: 0 auto;">
  <figcaption>
    Numerical tracer transport simulation using the SPE10 reservoir benchmark.
  </figcaption>
</figure>

### Error estimation and adaptive methods

Understanding numerical error is essential for reliable simulation. My work includes a priori analysis and a posteriori error estimation for mixed finite element approximations, including the Enhanced Velocity Mixed Finite Element Method (EVMFEM).

<figure>
  <img
    src="{{ '/images/animations/posteriori_upper_bound_velocity.gif' | relative_url }}"
    alt="Animation illustrating a posteriori error estimates for velocity in flow through heterogeneous porous media."
    loading="lazy"
    style="display: block; max-width: 100%; height: auto; margin: 0 auto;">
  <figcaption>
    A posteriori error estimates for velocity in flow through heterogeneous porous media.
  </figcaption>
</figure>

## Selected publications

- **Physics-informed neural networks for two-phase flow**  
  A study of a two-phase flow model with variable diffusion and experimental validation.  
  *Results in Engineering* · [Read the paper](https://doi.org/10.1016/j.rineng.2025.105439)

- **CFD–DEM modeling of fluid-driven fracture**  
  Coupled modeling of fracture induced by temperature-dependent polymer injection.  
  *Particuology* · [Read the paper](https://doi.org/10.1016/j.partic.2025.08.002)

- **Isogeometric analysis for financial derivatives**  
  Numerical methods for nonlinear models of convertible bonds and options.  
  *Computational Economics* · [Read the paper](https://doi.org/10.1007/s10614-025-11235-1)

[View all publications →]({{ '/publications/' | relative_url }})

## Academic background

I received my **Ph.D. in Computational Science, Engineering and Mathematics (CSEM)** from **The University of Texas at Austin** in 2018. I conducted my doctoral research at the [Center for Subsurface Modeling](https://csm.oden.utexas.edu/), under the supervision of [Professor Mary F. Wheeler](https://users.oden.utexas.edu/~mfw/), within the institute now known as the [Oden Institute for Computational Engineering and Sciences](https://www.oden.utexas.edu/).

In 2017, I was selected to participate in the **Research Experience in Carbon Sequestration (RECS)** program. Visits to industrial and geological sites strengthened my understanding of the practical challenges of carbon capture, utilization, and storage.

## Teaching and supervision

My teaching interests include numerical methods, scientific computing, differential equations, and finite element methods.

[Teaching]({{ '/teaching/' | relative_url }}) · [Students and supervision]({{ '/students/' | relative_url }})
-->

 ---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am currently an Assistant Professor at the School of Computing and Artificial Intelligence (SCAI), Nazarbayev University, Astana, Kazakhstan.

I received a Ph.D. in Computational Science, Engineering and Mathematics (CSEM) at 
the [Oden Institute for Computational Engineering and Sciences (ICES)](https://www.oden.utexas.edu/){:target="_blank"}  in the University of Texas at Austin, 
where I was at the [Center for Subsurface Modeling](https://csm.oden.utexas.edu/){:target="_blank"} and I was supervised by [Professor Mary Wheeler](https://users.oden.utexas.edu/~mfw/){:target="_blank"}.

<figure>
  <img src="/images/animations/SPE10_L37_simulation.gif" alt="">
  <figcaption> Numerical reservoir tracer simulation for SPE10 datasets</figcaption>
</figure>

My research interest brings together interdisciplinary areas of mathematics, physics, engineering and
computational science. In particularly, my research focuses on the numerical analysis of partial differential
systems that arise in subsurface phenomena using mathematical modeling and scientific computation.
My main interests are finite element methods, numerical analysis including a priori and a posteriori error
analysis, scientific computing, computational transport phenomena and numerical reservoir simulations.
My Ph.D. work has given me an opportunity to study these problems theoretically and numerically by
taking into account experimental laboratory data work.


<figure>
  <p align="center">
  <div class="image_resize">
  <img src="/images/animations/posteriori_upper_bound_velocity.gif"  alt="">
  <figcaption> A posteriori error estimates for velocity in flow through heterogeneous porous media</figcaption>
  </div>
  </p>
</figure>

Research
=====
Subsurface reservoir flow and transport modeling is important in many subsurface applications
such as Enhanced Oil Recovery (EOR), CO2 sequestration, groundwater remediation as well as contaminant
plume migration in heterogeneous porous media. I am working on these projects:

1. Developing a new adaptive numerical homogenization method to handle multiscale nature of flow and
	transport problems of heterogeneous subsurface
2. A priori analysis for slightly compressible flow using Enhanced Velocity Mixed Finite Element Method
	(EVMFEM).
3. A posteriori error analysis for incompressible flow problems using EVMFEM
4. Time domain decomposition methods for flow and transport in heterogeneous porous media problems
	
In addition, I was selected to attend Research Experience Carbon Sequestration program 2017
and this program gave me opportunity to explore the important stages of Carbon Capture, Utilization
and Storage (CCUS). Field trips including industrial and geological sites were valuable for better
understanding CCUS complexities as well as helped to expand my practical interpretation skills.
