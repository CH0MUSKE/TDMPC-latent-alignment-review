# Comparative Study on Latent World Models & Alignment in TD-MPC Frameworks

> A theoretical survey and comparative analysis exploring the synergy and alignment mechanisms between trajectory optimization (Model Predictive Control) and policy optimization (Reinforcement Learning).

📄 **[Read the Full Synthesis Report (PDF)](./report.pdf)**

---

## 📌 Overview

This synthesis document investigates the core question in hybrid control architectures:  
**How can we combine and ensure synergy between the complementary processes of trajectory optimization (MPC) and policy optimization (RL) within a single framework through effective alignment mechanisms?**

We conduct an in-depth comparative study of four recent state-of-the-art architectures:
* **LOOP** (*Sikchi et al., CoRL 2022*)
* **BMPC / Bootstrapped MPC** (*Wang et al., ICLR 2025*)
* **TD-M(PC)²** (*Lin et al., arXiv 2025*)
* **AC-MPC** (*Romero et al., arXiv 2025*)

---

## 🔍 Key Focus Areas

* **Policy–Planner Alignment:** Evaluating how each framework balances the behavior of the neural network policy against the online trajectory planner.
* **Algorithmic Trade-offs:** Examining explicit policy constraints, imitation-based regularization, and end-to-end differentiable planning.
* **Inverted Directionality in AC-MPC:** Analyzing how Actor-Critic MPC challenges conventional Policy–MPC interaction by embedding differentiable optimization directly inside policy optimization.
* **Theoretical & Empirical Evaluation:** Detailed review of mathematical formulations, distribution shift stability, and continuous control benchmarks.

---

## 📚 References

1. **Wang, Y., Guo, H., Wang, S., Qian, L., & Lan, X. (2025).**  
   *Bootstrapped Model Predictive Control.* ICLR 2025. [arXiv:2503.18871](https://arxiv.org/abs/2503.18871).
2. **Sikchi, H., Zhou, W., & Held, D. (2022).**  
   *Learning Off-Policy with Online Planning (LOOP).* Conference on Robot Learning (CoRL), PMLR.
3. **Lin, H., Wang, P., Schneider, J., & Shi, G. (2025).**  
   *TD-M(PC)²: Improving Temporal Difference MPC Through Policy Constraint.* [arXiv:2502.03550](https://arxiv.org/abs/2502.03550).
4. **Romero, A., Aljalbout, E., Song, Y., & Scaramuzza, D. (2025).**  
   *Actor-Critic Model Predictive Control: Differentiable Optimization Meets Reinforcement Learning.* [arXiv:2306.09852](https://arxiv.org/abs/2306.09852).
5. **Hansen, N., Su, H., & Wang, X. (2024).**  
   *TD-MPC2: Scalable, Robust World Models for Continuous Control.* ICLR 2024.
