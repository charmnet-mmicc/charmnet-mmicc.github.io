## Model Theory and Novel Closures 

We will advance closure models and their associated theory to bridge scales in transport and plasma simulations by building kinetic effects into coarse-grained models in a systematic way.
In the context of kinetic theory, moment equations offer a natural way to increase fidelity beyond local thermodynamic equilibrium (LTE) fluid models. Moment equations will be considered in several different ways: (1) as stand-alone models; (2) as members of an adaptive hierarchy; and (3) as components of highly efficient hybrid approaches. At low-order, the behavior of a model depends heavily on the closure assumptions used to derive it. Thus, the design and implementation of the closure  is critical. For both fluid and kinetic plasma models, closures determine not just moments of the single-particle distribution function, but also elements of the electromagnetic (EM) field, fluid quantities like electron velocity, and non-gyrotropic parts of particle distribution function. We seek closures that (1) are well-posed; (2) can capture non-equilibrium, non-perturbative  effects; (3) preserve important mathematical structures; and (4) are efficient to evaluate. 



## Linear and non-linear surrogates for subgrid modeling and closures

We will develop surrogate models for transport and plasmas that naturally tame the CoD by exploiting and preserving underlying structure of the full-order models (FOMs). Within our proposed ecosystem, surrogate models will (1) be physics-preserving (preferably built into mathematical structure of the surrogates, vs. weak enforcement through constraints in the training); (2) be used to accelerate high-performance computing (HPC), e.g., through preconditioning or multi-physics coupling; (3) facilitate multi-scale modeling; and (4) be used in a manner consistent with physics intuition to facilitate physical discovery.  These surrogates will play an essential role in the MF hierarchy of models that comprise the proposed ecosystem of CHaRMNET and enable uncertainty quantification (UQ), optimal design/control (ODC), and high-consequence decision-making (HCDM)

## Operator discovery and automating the Mori-Zwanzig formalism

We seek to extract operators that describe the dynamics of the mathematical structure
that is embedded within the data. We will use this approach to automate the Mori-Zwanzig 
formalism for extracting multi-scale models in the context of plasmas.
Operator-based surrogates in the CHaRMNET ecosystem should (1) facilitate extraction
of mesoscale models from Particle-In-Cell (PIC) or experimental data as stand-alone models or closures for other
models and (2) enable the automation of building scale-bridging, interpretable models direct
from data. Mesoscale models that capture fine-scale features at lower
computational cost are a critical aspect of the proposed ecosystem
of CHaRMNET to facilitate UQ, ODC, and HCDM.



<script type="text/x-mathjax-config">MathJax.Hub.Config({TeX: {equationNumbers: {autoNumber: "all"}}, tex2jax: {inlineMath: [['$','$']]}});</script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js?config=TeX-AMS_HTML"></script>
