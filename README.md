[README_PROFILE_UPDATED.md](https://github.com/user-attachments/files/30633175/README_PROFILE_UPDATED.md)
# Hi, I'm Clément 👋

I am an AI engineer and research student working on **world models, generative modeling, reinforcement learning, and adaptive inference**. I am particularly interested in when learned representations become useful for planning and decision-making, and in how inference-time computation should be allocated under limited budgets.

I am currently completing two degrees in parallel:

- an **Engineering Degree at CentraleSupélec**, majoring in Mathematics and Data Science;
- a **Research Master's in Mathematics & Artificial Intelligence at Université Paris-Saclay**.

Alongside my studies, I work as a **Generative AI Engineer at MBDA**, where I develop and evaluate multi-agent LLM systems and deploy self-hosted models on GPU infrastructure.

My projects emphasize controlled comparisons, reproducible artifacts, and explicit reporting of limitations and negative results.

## Selected research 🔬

### [Ego-World JEPA](https://github.com/clement-callaert/ego-world-sub-jepa) 🤖

A controlled comparison of factored and monolithic JEPA-style world models for planning on PushT, using a shared detector and MPPI planner. The apparent seed-0 planning gap, **12% versus 4%**, disappeared at seed 1, **4% versus 4%**. The factorization hypothesis was therefore not supported, and near-perfect in-slice probe scores did not reliably predict closed-loop planning performance.

### [Few-Step Field Regularity](https://github.com/clement-callaert/fewstep-field-regularity) 🌊

An exact Gaussian Wasserstein study of whether averaged field regularity can rank probability paths for few-step generative sampling. I found **14 ranking inversions out of 36 comparisons** across Euler, Heun, and RK4; the phenomenon replicated in **11 out of 18** comparisons in a preregistered non-centered family and passed an **80-digit precision audit**. A manuscript based on this work is under review.

### [Adaptive Latent Search for LPN](https://github.com/clement-callaert/lpn/blob/research/stochastic-latent-search/README_RESEARCH.md) 🧩

Research extensions to Latent Program Networks for adaptive test-time computation. On a held-out `pattern_2d` split, a REINFORCE stop-or-continue controller matched fixed-five exact match, **0.90625**, while reducing mean search steps from **5.00 to 4.28**. A gradient-norm heuristic achieved the same exact match in **3.44** steps, so the learned controller did not dominate the strongest simple baseline. These are controlled sandbox results, not ARC-AGI claims.

### [Decision Transformer for Limit Order Book Trading](https://github.com/clement-callaert/Decision-Transformer-LOB-Trading) 📈

A reproducible offline-RL benchmark on FI-2010, built with Côme Genet. Across five seeds, the preregistered primary Decision Transformer did not beat buy-and-hold under the frozen cost model. The RTG sweep nevertheless changed deployed behavior substantially, moving mean normalized PnL from **-1.976 at P10 to -0.033 at P90**. Metrics, manifests, plots, and reproduction commands are committed.

### [ACES Sycophancy](https://github.com/clement-callaert/aces-sycophancy/tree/submission) 🧠

An adaptation of ACES to search for regressive sycophancy in a local LLM using programmatic checkers. I diagnosed budget lock-in in a Bayesian ALP selector and introduced a fixed **20% uniform exploration floor**. Across two seeds, mean archive coverage recovered from **0.792 to 0.917**, while mean QD score increased from **9.219 to 11.000**.

### [Proximal Diffusion Models in PyTorch](https://github.com/clement-callaert/proximal-diffusion-models-pytorch) ✨

A from-scratch PyTorch implementation of Proximal Diffusion Models, with reverse-time SDE sampling, proximal-matching losses, low-NFE evaluation, tests, and reproducible Hydra configurations.

## Experience 💼

- **Generative AI Engineer, MBDA** (apprenticeship, Sep 2025 - present): multi-agent LLM systems, reinforcement learning for adversarial cybersecurity scenarios, vLLM, Docker, and GPU-cluster deployment.
- **Data Scientist, TotalEnergies Digital Factory** (apprenticeship, Nov 2023 - Sep 2025): machine learning for EV-charging pricing and public-station accessibility.

## Education 🎓

- **M2 Mathematics & Artificial Intelligence**, Université Paris-Saclay, 2025 - 2026
- **Engineering Degree, Mathematics and Data Science**, CentraleSupélec, 2023 - 2026
- **Exchange in AI for Engineering**, Beihang University, Beijing, 2025
- **CPGE Mathematics and Physics**, La Martinière Monplaisir, 2021 - 2023

I have also taught practical AI workshops with **Automatants** and led a six-person infrastructure team as president of **Rézo Metz-Rennes Fédérés**.

## What I'm looking for 🎯

I am looking for a **PhD or research-engineering position starting in autumn 2026**, primarily in Europe, on world models, diffusion or flow models, adaptive inference, LLM agents, or reinforcement learning.

- LinkedIn: [in/clement-callaert](https://www.linkedin.com/in/clement-callaert)
- Email: [clement.callaert@student-cs.fr](mailto:clement.callaert@student-cs.fr)

♟️ Outside research, I play chess at around **1750 Elo on chess.com**.
