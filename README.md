# VAEs-with-latent-high-dimensional-steady-geometric-flows-for-dynamics

We present variational autoencoders (VAEs) for dynamics (PDE data) with geometric latent dynamics. We incorporate a dynamical latent manifold into the latent space, which acts as regularizer for learning and promotes robustness.

We propose using a steady-state geometric flow, or a PDE on the Riemannian metric, that ensures sufficient measure, nondegeneracy, and a canonical geometry, which contribute towards ambient robustness. This choice of flow is computationally efficient, and requires only automatic differentiation of one (time) derivative and incurs low offline computational cost. This allows higher dimensional latent representations conforming to geometric properties, which in turn allow greater expressivity of function representation and incorporate more diverse initial conditions as input data.



<div align="center">
<img src="https://github.com/user-attachments/assets/672af49e-e0fa-41ac-91b4-78307c103d46" width="800">
</div>




