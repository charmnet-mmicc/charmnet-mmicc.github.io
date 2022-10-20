## Advanced Discretizations
To reduce the processing and memory requirements for the discrete representation of the high-dimensional particle distribution function.
Through a combination of novel discretization and solver techniques that leverage the structure of the solutions, we will effectively reduce the impact of the CoD, both in terms of memory usage and compute time. 
We will consider particle- and mesh-based approaches that are able to mollify the curse of dimensionality, as well as temporal strategies (IMEX, parallel-in-time) that can reduce the cost per timestep, the number of timesteps, and/or increase concurrency.


## Multi-model algorithms
To profitably use of one or more models with different fidelities (physical or numerical) to reduce time to solution of the highest fidelity model. We will develop a variety of multi-model algorithms that preserve the structure of the solution space (i.e., a mathematically rigorous hierarchy) to realize additional performance gains while ensuring robustness and high fidelity. Targeted applications include scale-bridging and preconditioning.  We will also seek to leverage connections between the multi-model algorithms and the multi-fidelity approaches to simultaneously advance both fields.



<script type="text/x-mathjax-config">MathJax.Hub.Config({TeX: {equationNumbers: {autoNumber: "all"}}, tex2jax: {inlineMath: [['$','$']]}});</script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js?config=TeX-AMS_HTML"></script>
