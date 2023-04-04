---
layout: home2
permalink: /projects/
title: Research interest
tags: [tools]
modified: 6-3-2018
comments: false


---
	<br>
# High-Perpformance Computing for Higher-order schemes
----
The compact finite difference formulation is a numerical discretisation used for computing finite difference approximations.
This method is known for the small computation stencil  while allowing accurate approximations.
The compact schemes has the advantage of favorable dispersive error and dissipative error properties when compared to explicit schemes.
However, this method has a drawback as it is implicit and requires solving a diagonal matrix system to evaluate interpolations or derivatives at all grid points.
So it remains a challenge to solve elliptical sss problems optimally with modern HPC... part of my work is devoted to this.

<div class="post-container"> 
    <div class="post-content">
        <h3 class="post-title"> HOCS-cube  a research code </h3>
        <p>
		For 5 years I have been developing a computational code dedicated to the high-performance numerical simulation of incompressible flows in shoeboxes ( referring to the computational domain).
		With this specific tool for compact schemes one can solve the incompressible Naviers-Stokes equations in an *old school way*: semi implicit time scheme, full-staggered.
		This allows me to test new ideas about compact schemes, especially the fact that they can be HPC-compliant (rPDD, parallel diagonalisation, preconditionning )  .
<a href="https://doi.org/10.1016/j.cam.2020.112872">[JCAM]</a> 
<a href="https://doi.org/10.1016/j.compfluid.2018.07.016">[CaF], </a>

	</p>
	</div>
		<div class="post-thumb"><img src="/images/STC-2.png" /></div>
	</div>


<div class="post-container"> 
    <div class="post-content">
        <h3 class="post-title"> SRI - Barocinic waves </h3>
		<p>
		High performance computing is motivated by the challenges of fluid physics.
        In this project led by Uwe Harlander, we try to perform both experiments and numerical simulations to demonstrate that the baroclinic tank can be a useful model for atmospheric flows.
		This flow is known to be difficult to simulate due to its multi-scale characteristics (IGW, 2d turbulence).
		In addition, heat transfers at the free surface can modify the dynamics of the baroclinic wave, making it more difficult to compare numerical calculations with experiments.
		<a href="https://doi.org/10.5194/egusphere-egu21-7003">[EGU]</a> 
		<a href="https://doi.org/10.1080/03091929.2020.1795647">[GAFD]</a>
		</p>
		
<br />

<!--
<div class="post-container"> 
    <div class="post-content">
        <h3 class="post-title"> Spectral colocation  </h3>
		<p>
		Even if I have a preference for compact schemes, I have to admit that the exponential accuracy and pseudo-spectra of spectral methods are really nice.
		For the last few months I have been working on the spectral collocation method in HOCS^3 and have made some comparisons in a differentially heated turbulent cavity.
		</p>
<br />
-->






