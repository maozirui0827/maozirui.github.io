---
title: "A conservative and consistent Lagrangian gradient smoothing method for simulating free surface flows in hydrodynamics"
collection: publications
permalink: /publications/L-GSM_fluid_2019
date: 2019-7-12
venue: 'Computational Particle Mechanics'
---
[pdf (draft)](https://www.researchgate.net/profile/Zirui_Mao/publication/334436444_A_conservative_and_consistent_Lagrangian_gradient_smoothing_method_for_simulating_free_surface_flows_in_hydrodynamics/links/5d2c84b7458515c11c31b3d6/A-conservative-and-consistent-Lagrangian-gradient-smoothing-method-for-simulating-free-surface-flows-in-hydrodynamics.pdf)

# How to cite 
Mao, Z., Liu, G.R., Dong, X. et al. A conservative and consistent Lagrangian gradient smoothing method for simulating free surface flows in hydrodynamics. Comp. Part. Mech. 6, 781–801 (2019). https://doi.org/10.1007/s40571-019-00262-z [link]('https://link.springer.com/article/10.1007/s40571-019-00262-z')

# Abstract
A novel particle method, Lagrangian gradient smoothing method (L-GSM), has been proposed in our earlier work to avoid the tensile instability problem inherently existed in SPH, through replacing the SPH gradient operator with a robust GSM gradient operator. However, the nominal area of each L-GSM particle determined by the relative location of particles is always inconsistent with the real representative area of it in simulation, especially in large-deformation problems. This is why the earlier L-GSM model has to be limited to the solid-like flow simulations where the deformation is not very serious. In this work, a conservative and consistent Lagrangian gradient smoothing method (CCL-GSM) is developed for handling large-deformation problems in hydrodynamics with an arbitrarily changing free surface profile. This is achieved by deriving a conservative and consistent form for the discretized Navier–Stokes governing equations in L-GSM, which even holds in the neighbor-updating or ‘remeshing’ process. Special techniques are also devised for free surface treatment, which is important to restore the conservation and consistency manner of CCL-GSM simulation on free surface boundary. The effectiveness of the proposed CCL-GSM framework is evaluated with a number of benchmarking examples, including dam break, wall impacts of breaking dam, water discharge and water splash. It shows that the CCL-GSM model can handle the incompressible flows with complicated free surfaces effectively and easily. The results comparison with experiments and SPH solutions demonstrates that the CCL-GSM can give a desirable result for all these examples.

# Keyword
Conservative and consistent Lagrangian Gradient Smoothing Method, L-GSM, SPH, free surface flows, incompressible flows, hydrodynamics
