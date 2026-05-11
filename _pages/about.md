---
permalink: /
title: "Ahmad Al-Tawaha"
layout: single
author_profile: true
---

News
======
<!-- Most recent on top. Keep ~5–7 entries. -->
- **2026 May**: Joining **Argonne National Laboratory** as a summer intern.
- **2026 Apr**: Submitted to NeurIPS — *Remembering More, Risking More* (memory safety in LLM agents).
- **2026 Jan**: Awarded the **Pratt Fellowship** by the Virginia Tech ECE Department (Spring 2026).
- **2025 Jul**: Paper accepted at ACC 2025 — *An Analytical Approach to Signal Denoising Based on SVD*.
- **2025 Jun**: Presented at L4DC 2025 — *A Dynamic Penalization Framework for Online Rank-1 SDP Relaxations*.
- **2025 Jan**: Two journal papers accepted — *IEEE Systems Journal* and *ASME JDSMC*.

About
======
I am a Ph.D. candidate in the Department of Electrical and Computer Engineering at Virginia Tech, advised by **Prof. Ming Jin**. My current research centers on **safe and reliable agentic AI** — making decision-making systems built on **large language models (LLMs)** stable, predictable, and safe across long horizons of use.

**Memory safety and reasoning stability in LLM agents.** In *Remembering More, Risking More: Longitudinal Safety Risks in Memory-Equipped LLM Agents* (under review at NeurIPS), I study how persistent memory amplifies safety risks over time. The work treats memory and context as evolving internal states and analyzes when they trigger failures such as incorrect commitments, disclosure, or inconsistent decisions; it develops measurable retrieval-time predictors that monitor risk before generation. I also contribute to an ongoing collaboration that takes an **operating-systems-inspired perspective** on evaluating the security of agentic AI systems.

**Differentiable optimization, decision-focused learning, and learning-to-optimize.** A second thread of my research treats optimization as a learnable component inside larger pipelines. In *Dynamic Penalization for Rank-1 SDP Relaxations* (L4DC 2025, with Lavaei and Jin), we differentiate through a penalized SDP solver to learn penalty matrices that drive relaxations toward rank-1 solutions, and meta-learn initializations across tasks for faster, feasibility-preserving solves on Max-Cut and optimal power flow. *Decision-Focused Learning for Inverse Noncooperative Games* (IFAC 2023) represents game equilibria as differentiable variational-inequality layers, with covering-number-based generalization bounds and a convergence analysis that extends naturally to MIPs via differentiable surrogates. *Meta-LMRS* (L4DC 2023) jointly learns a meta-initialization and a meta-manifold for derivative-free optimization across sequential tasks, with task-averaged regret bounds for high-dimensional, nonconvex problems.

**System identification and control.** I work on finite-time identification of LTI systems using **non-causal FIR models** — a unified framework that handles both stable and unstable systems. Earlier work, going back to my Master's, focused on **model order determination**: nonheuristic singular-value-thresholding approaches that recover the order of dynamic systems from noisy data (ASME JDSMC; ACC 2023, 2025).

Before joining Virginia Tech, I completed my M.S. in Mechanical Engineering (Mechatronics) and my B.Tech in Aeronautical Engineering at the **Jordan University of Science and Technology**, advised by **Dr. Khaled Al-Janaideh**.

**Contact:** atawaha@vt.edu  
[CV](../files/cv.pdf) • [GitHub](https://github.com/Ahmad-Tawaha)
