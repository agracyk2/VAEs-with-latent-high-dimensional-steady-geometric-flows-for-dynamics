# VAEs-with-latent-high-dimensional-steady-geometric-flows-for-dynamics

We present variational autoencoders (VAEs) for dynamics (PDE data) with geometric latent dynamics. We incorporate a dynamical latent manifold into the latent space, which acts as regularizer for learning and promotes robustness in performance by up to 25% out-of-distribution error reduction and potentially more when compared to baselines of a vanilla VAE and an extended VAE, or VAE endowed with identical architecture we propose.

We reformulate the traditional ELBO loss used in the VAE framework but with a considerate choice of prior. This results in a corresponding loss with a weighting term; we investigate empirical performances with and without this weighting.

We propose using a steady-state geometric flow, or a PDE on the Riemannian metric, that ensures sufficient measure, nondegeneracy, and a canonical geometry, which contribute towards ambient robustness. This choice of flow is computationally efficient, and requires only automatic differentiation of one (time) derivative and incurs low offline computational cost. This allows higher dimensional latent representations conforming to geometric properties, which in turn allow greater expressivity of function representation and incorporate more diverse initial conditions as input data.



<div align="center">
<img src="https://github.com/user-attachments/assets/672af49e-e0fa-41ac-91b4-78307c103d46" width="800">
</div>




