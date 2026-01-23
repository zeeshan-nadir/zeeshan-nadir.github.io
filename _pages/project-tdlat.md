---
title: "A MODEL BASED ITERATIVE RECONSTRUCTION APPROACH TO TUNABLE DIODE LASER ABSORPTION TOMOGRAPHY"
permalink: /projects/tdlat/
layout: single
classes: wide
author_profile: false
---




## Overview
My dissertation develops a **model-based iterative reconstruction (MBIR)** framework for Tunable Diode Laser Absorption Tomography (TDLAT), a non-intrusive technique for imaging 2D fields of gas concentration and temperature from sparse optical absorption measurements.
 I formulate a **physics-aware nonlinear forward model** that accurately captures the light absorption process through a gaseous medium, addressing the ill-posed and highly nonlinear nature of the TDLAT inverse problem.
 To regularize this ill-posed problem, I propose a trainable non-Gaussian prior model based on a **Gaussian mixture distribution** that accommodates complex flow structures.
 I integrate this prior into a **maximum a posteriori (MAP) estimation** framework and derive an efficient multigrid optimization algorithm to accelerate convergence.
 To improve robustness when training data is limited, I introduce a novel hybrid prior that blends **data-driven and Markov random field models**, mitigating overfitting.
 I also establish a **hypothesis-testing** based validation metric to detect inaccuracies in the posterior distribution in the absence of ground truth, enhancing confidence in reconstructions.
 Extensive simulation and experimental results demonstrate superior reconstruction quality over conventional TDLAT methods.
 This work advances TDLAT imaging toward practical, high-resolution sensing of complex gaseous flows.
 The framework provides a foundation for future real-time and adaptive tomography systems.
 Ultimately, my contributions span **novel modeling, optimization, statistical regularization, and model validation techniques** for solving challenging inverse problems in optical tomography. 

<a href="https://media.proquest.com/media/hms/ORIG/2/xZodI?_s=wDQEqAzJI9KeqT1uXbXOWYk8p8c%3D">[Thesis]</a>





<br><br>
<a href="javascript:history.back()">← Back</a>