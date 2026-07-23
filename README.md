# Shreyas Ekanathan

Hi! I'm a Turing Scholar at UT Austin (Class of 2028).

I am interested in numerical methods for differential equations, and increasingly
the machine learning side. I work across the Julia SciML ecosystem, with a focus
on ODE solvers, and I'm building toward the intersection: scientific machine
learning for dynamical systems and climate.

Currently at JuliaHub working with Chris Rackauckas, and researching machine
learning methods for Hamiltonian dynamics with Chandrajit Bajaj at UT's Center
for Computational Visualization.

## Research

- **Adaptive-order Radau IIA stiff ODE solver** ([IEEE HPEC 2025](https://ieeexplore.ieee.org/document/11196706), [arXiv:2412.14362](https://arxiv.org/abs/2412.14362)).
  Roughly 2x faster than the classic Fortran RADAU. Landed in OrdinaryDiffEq.jl:
  [order adaptivity](https://github.com/SciML/OrdinaryDiffEq.jl/pull/2478),
  [parallelization](https://github.com/SciML/OrdinaryDiffEq.jl/pull/2584).
- **Discontinuity detection for implicit solvers** (publication coming). Shipped as an ecosystem-wide
  feature ([OrdinaryDiffEq.jl #3121](https://github.com/SciML/OrdinaryDiffEq.jl/pull/3121),
  [OrdinaryDiffEq.jl #3720](https://github.com/SciML/OrdinaryDiffEq.jl/actions/runs/30018859629?pr=3720).

## Open source (SciML / Julia)

Some highlight projects:

- **Butterfly Factorization** in
  [LinearSolve.jl #785](https://github.com/SciML/LinearSolve.jl/pull/785) and
  [RecursiveFactorization.jl #97](https://github.com/JuliaLinearAlgebra/RecursiveFactorization.jl/pull/97).
- Authored
  [SparseBandedMatrices.jl](https://github.com/SciML/SparseBandedMatrices.jl/pull/1) to support the above work.
- **Symbolic logging** spanning the stack:
  [ModelingToolkit.jl #4720](https://github.com/SciML/ModelingToolkit.jl/pull/4720),
  [SciMLBase.jl #1434](https://github.com/SciML/SciMLBase.jl/pull/1434), and
  [OrdinaryDiffEq.jl #3731](https://github.com/SciML/OrdinaryDiffEq.jl/pull/3731).
- Plus other contributions across the ecosystem.

## Deep learning

[**Deep-Learning**](https://github.com/Shreyas-Ekanathan/Deep-Learning): the
modern DL canon built from scratch (numpy backprop, then PyTorch), plus applied
projects. This is my bridge from numerics into ML. I work through some of the
traditional ML projects and put my own scientific twist on a few.

- [GNN interatomic potentials](https://github.com/Shreyas-Ekanathan/Deep-Learning/tree/main/GNN): learn a Lennard-Jones energy, get forces by autograd, run it as a differentiable MD sim.
- [MRI to CT translation](https://github.com/Shreyas-Ekanathan/Deep-Learning/tree/main/MRI2CT): six image-translation architectures benchmarked (U-Net through conditional diffusion).
- [Acrobot control](https://github.com/Shreyas-Ekanathan/Deep-Learning/tree/main/RL/acrobot-control): from-scratch DQN and PPO, continuous swing-up and balance with an LQR handoff.

## Now

Neural ODEs and neural operators (FNO / DeepONet), the natural fusion of the
solver work and deep learning, heading toward scientific ML for climate.

## Awards

- **Regeneron Science Talent Search** Top 300 Scholar (2025), for the Radau research
- **MIT PRIMES** Computer Science Research Scholar (2024 to 2025)
- **2x National Science Bowl Champion** (2023, 2024)
- **Non-Trivial Fellow** (~1% acceptance), on climate change and agricultural yields
- **USESO National Finalist** (2024, 2025)
