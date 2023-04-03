---
layout: home2
permalink: /projects/
title: Research interest
tags: [tools]
modified: 6-3-2018
comments: false


---
<br>
# High-Perpformance Computing for Simulation
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
		This allows me to test new ideas about compact schemes, especially the fact that they can be HPC-compliant rPDD (Abide,2017), (Abide,2018),  (Abide,202) .
<a href="http://www.youtube.com/watch?feature=player_embedded&v=RYzgyOgVzM4">[Video]</a> 
<a href="https://www.researchgate.net/publication/305695638_A_Real-time_Augmented_Reality_System_to_See-Through_Cars">[TVCG16, </a>
<a href="https://link.springer.com/chapter/10.1007/978-3-319-48881-3_15">ECCVW16]</a>

 </p></div>
<div class="post-thumb"><img src="/images/STC-2.png" /></div>
</div>


<div class="post-container"> 
    <div class="post-content">
        <h3 class="post-title"> Barocinic waves (tu me fais tourner la tête...) </h3>
		<p>
		High performance computing is motivated by challenges in physics of fluids.
	    Thanks to Uwe Harlander to demonstrate that the baroclinic reservoir can be a model for atmospheric flows. This flow is complex because it is multi-scale, with exchanges at the free surface that can modify the dynamics of the baroclinic wave...
		</p>
<br />

<div class="post-container"> 
    <div class="post-content">
        <h3 class="post-title"> Spectral colocation  </h3>
		<p>
		Even if I have a preference for compact schemes, I have to admit that the exponential accuracy and pseudo-spectra of spectral methods are really nice.
		For the last few months I have been working on the spectral collocation method in HOCS^3 and have made some comparisons in a differentially heated turbulent cavity.
		Nice results have been 
		</p>
<br />






