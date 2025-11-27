Key Features:
- Autoregressive Transformer-style decoder that models the full spin chain probability distribution one site at a time.
- Time encoder that conditions the network on continuous time.
- Training via physics-informed loss, enforcing the initial condition where all spins are pointing up at $t=0$.
- The TDVP/McLachlan residual, ensuring dynamics consistent with quantum evolution.
- Sampling function to generate spin configurations at any time using autoregressive sampling.

What This Model Does:
- Learns how the TFIM wavefunction evolves after a quench.
- Predicts full configuration probabilities without solving Schrödinger’s equation directly.
- Uses the network to sample trajectories and compute physical observables.
