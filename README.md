<div align="center">

# Kartikey Singh
### **Computational Mathematician & Scientific AI Systems Researcher**
**Department of Mathematics, University of Delhi** • **Advisor: Prof. Vinay Kumar**

[![Portfolio](https://img.shields.io/badge/Portfolio-kartikeygangwar.github.io-blue?style=for-the-badge&logo=googlechrome&logoColor=white)](https://kartikeygangwar.github.io)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0009--1973--7532-green?style=for-the-badge&logo=orcid&logoColor=white)](https://orcid.org/0009-0009-1973-7532)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-kartikey--singh-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kartikey-singh-2a3434329/)
[![Email](https://img.shields.io/badge/ProtonMail-kartikeysingh525-8A2BE2?style=for-the-badge&logo=protonmail&logoColor=white)](mailto:kartikeysingh525@protonmail.com)

<br/>

```
  ____   ____ ___ __  __ _        ____  _  _  _  _   _   _ _   _ 
 / ___| / ___|_ _|  \/  | |      / ___|| || || \| | | \ | | \ | |
 \___ \| |    | || |\/| | | _____\___ \| || || .` | |  \| |  \| |
  ___) | |___ | || |  | | |_____|___) |__   _| |\ | | |\  | |\  |
 |____/ \____|___|_|  |_|_|      |____/   |_| |_| \_|_| \_|_| \_|
```
*Bridging Continuous Differential Geometry, High-Performance Systems, and Deep Learning.*

</div>

---

### 🔬 Research Philosophy & Executive Profile

I am an undergraduate mathematical researcher at the **University of Delhi** (Department of Mathematics) working under the advisement of **Prof. Vinay Kumar**. My research is situated at the intersection of **Scientific Machine Learning (SciML)**, **Symplectic Mechanics**, **Inverse Problems (EIT)**, and **High-Dimensional Stochastic PDEs**.

Rather than treating deep networks as empirical black boxes, my methodology builds on **structural physical invariants**:
1. **Geometric Manifold Preservation:** Exact symplectic 2-form conservation ($\omega = \sum dq^i \wedge dp_i$) and contact Hamiltonian phase spaces for non-conservative celestial orbits.
2. **The Adaptive Subspace (AS) Paradigm:** Resolving destructive multi-task gradient interference via algebraic parameter null-space splitting ($\Theta_0 \oplus \Theta_1$), autonomous parameter-space Adaptive Mesh Refinement (AMR), and latent mixture-of-experts in Vision Transformers.
3. **Curse of Dimensionality Elimination:** Computing forward-mode directional autograd traces in strictly $\mathcal{O}(d)$ linear complexity and $\mathcal{O}(1)$ memory ($<3\,\mathrm{GB}$ VRAM for $d=50$ asset basket options).
4. **Zero-Allocation Systems Engineering:** Developing deterministic 2000Hz real-time soft-body physics telemetry and high-performance FDM solvers operating at the hardware roofline limit.

---

### 🏛️ Flagship Research Repositories & Working Papers

#### 🌌 Pillar I: Symplectic Astrodynamics, Inverse Problems & Fluid Mechanics

| Repository & Framework | Key Mathematical Breakthrough | Status & Identifiers |
|---|---|---|
| **[cpa-shnn](https://github.com/KartikeyaGangwar/cpa-shnn)**<br/>*CPA-SHNN: Symplectic Celestial Dynamics* | Proved **Separable Kinetic-Coriolis Splitting** ($\nabla_{\mathbf{z}} \cdot \mathbf{f}_\theta \equiv 0$) & **Arnold Extended Contact Phase Space** ($\mathcal{K}_\theta \equiv 0$) across 6 chaotic systems (Binary Quasars, Sitnikov 5-Body, CR3BP). $126.4\times$ Fourier gain. | Target: *Astronomy & Computing*<br/>[![arXiv](https://img.shields.io/badge/Preprint-Coming_Soon-red)](#) |
| **[eit-neural-surrogate-inversion](https://github.com/KartikeyaGangwar/eit-neural-surrogate-inversion)**<br/>*Deep Shape Inversion in EIT* | Overcame Calderón logarithmic ill-posedness via **Stochastic Directional JVP Supervision on $\mathbb{S}^{63}$**. Bounded peak VRAM to $342.8\,\mathrm{MB}$ with a **$56.8\times$ wall-clock speedup** ($35.6\,\mathrm{ms}$ vs $2.02\,\mathrm{s}$/step). | **Under Review at IEEE TCI**<br/>[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22096368.svg)](https://doi.org/10.5281/zenodo.22096368) |
| **[pinn-fluid-formulations](https://github.com/KartikeyaGangwar/pinn-fluid-formulations)**<br/>*High-$Re$ Incompressible Navier-Stokes* | Discovered **Operator Diffusion & False Convergence** in continuous $\psi-\omega$ PINNs caused by lack of discrete spatial stencils for Thom's wall-vorticity formula. Formulated hard-constrained $\psi-p$ Helmholtz-Hodge projection. | Target: *Physics of Fluids*<br/>[![Ghia Benchmark](https://img.shields.io/badge/Benchmark-Ghia_1982-blue)](#) |

#### ⚡ Pillar II: The Adaptive Subspace (AS) Optimization Paradigm

| Repository & Framework | Key Mathematical Breakthrough | Status & Identifiers |
|---|---|---|
| **[null-space-pinn](https://github.com/KartikeyaGangwar/null-space-pinn)**<br/>*Null-Space Parameter Subspaces (RPS)* | Decomposed parameter manifold into orthogonal direct-sum subspaces ($\Theta = \Theta_0 \oplus \Theta_1$) blended via a **$C^2$ Quintic Hermite seam operator** ($\psi(\xi) = 6\xi^5 - 15\xi^4 + 10\xi^3$). Eliminates boundary-PDE gradient conflict. | Target: *J. Comput. Phys. (JCP)*<br/>[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22132799.svg)](https://doi.org/10.5281/zenodo.22132799) |
| **[as-pinn](https://github.com/KartikeyaGangwar/as-pinn)**<br/>*Adaptive $N$-Subspace PINN (AS-PINN)* | Autonomous parameter-space AMR via per-sample Gram alignment profiling (`torch.func.vmap`) with **Exact Zero-Disruption Cleavage Invariance** ($\|u^{(N+1)} - u^{(N)}\| = 0$). **$725.6\times$ loss reduction** on high-frequency Helmholtz ($k=4\pi$). | Target: *SIAM J. Sci. Comput. (SISC)*<br/>[![9-PDE Suite](https://img.shields.io/badge/Verified-9_Canonical_PDEs-orange)](#) |
| **[as-vit-multitask](https://github.com/KartikeyaGangwar/as-vit-multitask)**<br/>*Adaptive Subspace Vision Transformers* | Resolves multi-task negative transfer by tracking inter-task Gram matrix negative eigenvalues ($\lambda_{\min}(\mathcal{G}) < -\tau$) and dynamically cleaving latent expert subspaces using Partition of Unity (PoU) gating. $+5.84\%$ mean gain on NYUv2. | Target: *IEEE TPAMI / CVPR*<br/>[![Multi-Task](https://img.shields.io/badge/Tasks-Depth_|_Normals_|_Seg_|_Edges-purple)](#) |

#### 📈 Pillar III: High-Dimensional Stochastic Systems & HPC Infrastructure

| Repository & Framework | Key Mathematical Breakthrough | Status & Identifiers |
|---|---|---|
| **[Deep-EEP-PINN](https://github.com/KartikeyaGangwar/Deep-EEP-PINN)**<br/>*50D American Basket Options* | Solved American free-boundary obstacle problems for correlated basket options up to **$d=50$ assets (1,225 correlations)**. Directional Autograd Hessian Trace Contraction computes exact diffusion in $\mathcal{O}(d)$ time and $<3\,\mathrm{GB}$ VRAM. | Target: *J. Comput. Finance*<br/>[![Longstaff-Schwartz](https://img.shields.io/badge/Validation-100K_Path_MC-green)](#) |
| **[PINN-Bayesian-Posterior-Fidelity](https://github.com/KartikeyaGangwar/PINN-Bayesian-Posterior-Fidelity)**<br/>*Bayesian Fidelity Ratio (BFR) UQ* | Formulated the **Bayesian Fidelity Ratio (BFR)**: $\mathrm{BFR} = \mathcal{W}_1(\pi_E, \pi_A) / \mathcal{W}_1(\pi_{E,1}, \pi_{E,2})$ using Kantorovich-Rubinstein 1-Wasserstein optimal transport normalized by paired MCMC stochastic noise floors. | Target: *Reliab. Eng. & Sys. Safety*<br/>[![UQ Metric](https://img.shields.io/badge/Metric-Wasserstein_BFR-yellow)](#) |
| **[Lid-Driven-Cavity-FDM-Solver](https://github.com/KartikeyaGangwar/Lid-Driven-Cavity-FDM-Solver)**<br/>*High-Performance 2D Navier-Stokes FDM* | High-resolution 2D incompressible fluid solver on dense $251 \times 251$ grids ($Re=1000$). Peaceman-Rachford ADI vorticity solver + **Red-Black SOR Chebyshev acceleration** ($\omega=1.80$) breaking loop dependencies into bipartite sublattices. | **Open-Source Ground Truth**<br/>[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18312938.svg)](https://doi.org/10.5281/zenodo.18312938) |
| **[BRSDK](https://github.com/KartikeyaGangwar/BRSDK)**<br/>*BeamNG Research SDK* | Deterministic real-time telemetry extraction framework operating inside the **2000Hz Vehicle Lua physics thread**. Features pre-allocated static ring buffers, zero-allocation hot path (0 bytes/s GC allocations), and RFC 8259 JSON metadata sidecars. | **Scientific Research SDK**<br/>[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21729606.svg)](https://doi.org/10.5281/zenodo.21729606) |

---

### 💻 Core Technology Stack & Computational Toolchain

<div align="center">

| Domain | Technologies & Libraries |
|---|---|
| **Core Languages** | `Python 3.11+` • `C++20` • `Lua / LuaJIT` • `Bash / Linux` • `LaTeX (TikZ, pgfplots)` |
| **Deep Learning & Autograd** | `PyTorch` (`torch.func.vmap`, forward-mode AD, custom JVPs) • `JAX` • `CUDA` • `TorchVision` |
| **Scientific & Numerical Computing** | `NumPy` • `SciPy` (sparse matrices, solvers) • `Matplotlib` • `OpenMP` • `CMake` |
| **Simulation & High-Performance** | `BeamNG.tech / JBeam (2000Hz soft-body)` • `FDM (Peaceman-Rachford ADI, RB-SOR)` • `MCMC` |
| **Standards & Reproducibility** | `Git / GitHub` • `Zenodo DOIs` • `Docker` • `RFC 8259 JSON Sidecars` • `Apache-2.0 / MIT` |

</div>

---

### 📐 Mathematical Invariants Preserved in Code

```math
\begin{aligned}
\text{Symplectic 2-Form Invariance:} \quad & \omega(t) = \sum_{i=1}^n dq^i(t) \wedge dp_i(t) \equiv \omega(0) \\
\text{Null-Space Direct-Sum Splitting:} \quad & \Theta = \Theta_0 \oplus \Theta_1, \quad \mathcal{W}_0 \mathcal{W}_1^T = \mathbf{0} \implies \langle \nabla\mathcal{L}_{\mathrm{if}}, \nabla\mathcal{L}_{\mathrm{des}} \rangle \equiv 0 \\
\text{Hard Incompressible Helmholtz-Hodge:} \quad & \mathbf{u} = \left(\frac{\partial \psi}{\partial y}, -\frac{\partial \psi}{\partial x}\right)^T \implies \nabla \cdot \mathbf{u} = \frac{\partial^2 \psi}{\partial x \partial y} - \frac{\partial^2 \psi}{\partial y \partial x} \equiv 0 \\
\text{Directional Autograd Trace Contraction:} \quad & \mathrm{Tr}\left(\boldsymbol{\Sigma} \mathbf{S} \nabla^2 V \mathbf{S} \boldsymbol{\Sigma}^T\right) = \sum_{i=1}^d \left.\frac{\partial}{\partial \epsilon} \left(\nabla V(\mathbf{S} + \epsilon \mathbf{v}_i) \cdot \mathbf{v}_i\right)\right|_{\epsilon=0} \in \mathcal{O}(d)
\end{aligned}
```

---

### 📬 Academic Verification & Contact

- **Institutional Affiliation:** Department of Mathematics, University of Delhi, Delhi, India
- **Dissertation Supervisor:** Prof. Vinay Kumar (Department of Mathematics, DU)
- **Primary Research Email:** [kartikeysingh525@protonmail.com](mailto:kartikeysingh525@protonmail.com)
- **Personal Web Portfolio:** [https://kartikeygangwar.github.io](https://kartikeygangwar.github.io)
- **ORCID Record:** [0009-0009-1973-7532](https://orcid.org/0009-0009-1973-7532)
- **LinkedIn:** [linkedin.com/in/kartikey-singh-2a3434329](https://www.linkedin.com/in/kartikey-singh-2a3434329/)
- **Zenodo Developer Profile:** [Kartikey Singh on Zenodo](https://zenodo.org/search?q=metadata.creators.person_or_org.name%3A%22Singh%2C%20Kartikey%22)

<div align="center">
  <sub>Engineered with mathematical rigor and bare-metal computational efficiency. © 2026 Kartikey Singh.</sub>
</div>
