# Shreyas Ekanathan

Numerical methods for differential equations, and increasingly the machine
learning side. I work in the Julia SciML ecosystem on stiff ODE solvers, and
I'm building toward the intersection: scientific machine learning for dynamical
systems and climate.

Currently at JuliaHub, working with Chris Rackauckas.

## Research

- **Adaptive-order Radau IIA stiff ODE solver** (arXiv:2412.14362). Roughly 2x faster than the classic Fortran RADAU.
  Landed in OrdinaryDiffEq.jl:
  [order adaptivity](https://github.com/SciML/OrdinaryDiffEq.jl/pull/2478),
  [parallelization](https://github.com/SciML/OrdinaryDiffEq.jl/pull/2584).
- **Discontinuity detection for implicit solvers**. Shipped as an ecosystem-wide feature
  ([OrdinaryDiffEq.jl #3121](https://github.com/SciML/OrdinaryDiffEq.jl/pull/3121)).

## Open source (SciML / Julia)

Some highlight projects:

- **Butterfly Factorization** in
  [LinearSolve.jl #785](https://github.com/SciML/LinearSolve.jl/pull/785).
- Authored
  [SparseBandedMatrices.jl](https://github.com/SciML/SparseBandedMatrices.jl/pull/1).
- **Symbolic logging** spanning the stack:
  [ModelingToolkit.jl #4720](https://github.com/SciML/ModelingToolkit.jl/pull/4720),
  [SciMLBase.jl #1434](https://github.com/SciML/SciMLBase.jl/pull/1434), and
  [OrdinaryDiffEq.jl #3731](https://github.com/SciML/OrdinaryDiffEq.jl/pull/3731).
- The Radau and discontinuity-detection work above, plus contributions to
  ModelingToolkit.jl and SciMLBase.jl.

## Deep learning

[**Deep-Learning**](https://github.com/Shreyas-Ekanathan/Deep-Learning): the
modern DL canon built from scratch (numpy backprop, then PyTorch), plus applied
projects. This is my bridge from numerics into ML. I explore some of the traditional ML projects,
while also putting my own scientific twist on a few for my interest. 

- [GNN interatomic potentials](https://github.com/Shreyas-Ekanathan/Deep-Learning/tree/main/GNN): learn a Lennard-Jones energy, get forces by autograd, run it as a differentiable MD sim.
- [MRI to CT translation](https://github.com/Shreyas-Ekanathan/Deep-Learning/tree/main/MRI2CT): six image-translation architectures benchmarked (U-Net through conditional diffusion).
- [Acrobot control](https://github.com/Shreyas-Ekanathan/Deep-Learning/tree/main/RL/acrobot-control): from-scratch DQN and PPO, continuous swing-up and balance with an LQR handoff.

## Now

Neural ODEs and neural operators (FNO / DeepONet), the natural fusion of the
solver work and deep learning, heading toward scientific ML for climate.
