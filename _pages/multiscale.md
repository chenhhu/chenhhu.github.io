---
layout: archive
title: "Advanced Multiscale coupling problems"
collection: research
permalink: /research/multiscale/
---

## Advanced Multiscale coupling problems
<p align="justify">
The effective stress concept and the poromechanical framework pioneered by Terzaghi and Biot have been widely adopted to illustrate coupled fluid flow and solid deformation in porous rocks, but there were still some links missing for anisotropic and ductile rocks like shale. There hardly exists complete discussions in existing research work on poromechanical formulations that consider material anisotropy, elastoplastic, and grain compressibility, and they are all critical components in quantifying the hydromechanical processes in transversely isotropic rocks. Based on the mixture theory and continuum thermodynamics, I derived a novel mathematical framework for coupled solid deformation and fluid flow with all of the aforementioned factors addressed[1].  
</p> 
<p align="justify">
The proposed framework involves a new set of governing equations for mass conservation of fluid and solid, and a new effective stress formulation that identifies distinct forms of effective stress for elastic response and plastic response respectively. Coefficients that emerge in the governing equations are evaluated naturally through the derivation, thus the proposed framework won’t require any additional constitutive law or assumption for parameter evaluation. For this work, I also developed a mixed finite element framework for its numerical implementation and conducted simulations of a consolidation problem with strip loading to reveal the unique hydromechanical response in anisotropic elastoplastic porous rocks, as demonstrated in the ensuing figures.   
</p>

<img src="/images/SP_1.PNG"/>  
<h6 align="center">Setup of the consolidation problem in a transversely isotropic medium under a strip load.  
</h6>

## Reference:
\[1\] <b>Zhao Y.</b>, Borja R.I.\* (2020). A continuum framework for coupled solid deformation–fluid flow through anisotropic elastoplastic porous media. <i>Computer Methods in Applied Mechanics and Engineering</i>, 369, 113225.  <br>
