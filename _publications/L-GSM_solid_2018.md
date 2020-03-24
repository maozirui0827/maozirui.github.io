---
title: "A Lagrangian gradient smoothing method for solid‐flow problems using simplicial mesh"
collection: publications
permalink: /publications/L-GSM_solid_2018
date: 2018-2-3
venue: 'International Journal for Numerical Methods in Engineering'
---
[pdf (draft)](https://www.researchgate.net/publication/319265950_A_Lagrangian_gradient_smoothing_method_L-GSM_for_solid-flow_problems_using_simplicial_mesh)

# How to cite 
Mao, Z, Liu, GR. A Lagrangian gradient smoothing method for solid‐flow problems using simplicial mesh. Int J Numer Methods Eng. 2018; 113: 858– 890. https://doi.org/10.1002/nme.5639. [[link]]'https://onlinelibrary.wiley.com/doi/abs/10.1002/nme.5639'

# Abstract
A novel Lagrangian gradient smoothing method (L‐GSM) is developed to solve “solid‐flow” (flow media with material strength) problems governed by Lagrangian form of Navier‐Stokes equations. It is a particle‐like method, similar to the smoothed particle hydrodynamics (SPH) method but without the so‐called tensile instability that exists in the SPH since its birth. The L‐GSM uses gradient smoothing technique to approximate the gradient of the field variables, based on the standard GSM that was found working well with Euler grids for general fluids. The Delaunay triangulation algorithm is adopted to update the connectivity of the particles, so that supporting neighboring particles can be determined for accurate gradient approximations. Special techniques are also devised for treatments of 3 types of boundaries: no‐slip solid boundary, free‐surface boundary, and periodical boundary. An advanced GSM operation for better consistency condition is then developed. Tensile stability condition of L‐GSM is investigated through the von Neumann stability analysis as well as numerical tests. The proposed L‐GSM is validated by using benchmarking examples of incompressible flows, including the Couette flow, Poiseuille flow, and 2D shear‐driven cavity. It is then applied to solve a practical problem of solid flows: the natural failure process of soil and the resultant soil flows. The numerical results are compared with theoretical solutions, experimental data, and other numerical results by SPH and FDM to evaluate further L‐GSM performance. It shows that the L‐GSM scheme can give a very accurate result for all these examples. Both the theoretical analysis and the numerical testing results demonstrate that the proposed L‐GSM approach restores first‐order accuracy unconditionally and does not suffer from the tensile instability. It is also shown that the L‐GSM is much more computational efficient compared with SPH, especially when a large number of particles are employed in simulation.

# Keyword
Free surface flow, GSM, Lagrangian Gradient Smoothing Method, mesh-free method, solid flow, SPH
