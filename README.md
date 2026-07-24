[README_PROFILE.md](https://github.com/user-attachments/files/30364921/README_PROFILE.md)
# Hi, I'm Clément 👋

## About me 🙂

I am a French AI engineer and student, currently completing two degrees in parallel:

- an **Engineering Degree at CentraleSupélec**, with a major in Mathematics and Data Science;
- a **Research Master's in Mathematics & Artificial Intelligence at Université Paris-Saclay**.

Alongside my studies, I work as a **Generative AI Engineer at MBDA**, where I develop and evaluate multi-agent LLM systems and deploy self-hosted models on GPU infrastructure.

I am interested in **generative models**, **world models**, **reinforcement learning**, **LLM agents**, and **test-time computation**. I enjoy turning research questions into controlled experiments, reproducible code, and honest conclusions, including when the result is negative.

## What I'm looking for 🎯

I am looking for a **PhD or research position starting in autumn 2026**, primarily in Europe, on topics related to **generative models, world models, diffusion and flow models, LLM agents, or reinforcement learning**.

If you work on these topics and think there could be a fit, feel free to contact me by email or LinkedIn.

## Selected research and projects 🔬

### [Few-Step Field Regularity](https://github.com/clement-callaert/fewstep-field-regularity) 🌊

A controlled study of whether averaged field regularity can rank probability paths for few-step generative sampling. I built an exact Gaussian Wasserstein benchmark and found **14 ranking inversions out of 36 comparisons** across Euler, Heun, and RK4. The phenomenon replicated in **11 out of 18** comparisons in a preregistered non-centered family and passed an **80-digit precision audit**. The repository also contains an explicit scalar non-implication proof and a checksummed reproducibility pipeline.

### [Ego-World JEPA](https://github.com/clement-callaert/ego-world-sub-jepa) 🤖

A controlled comparison of factored and monolithic JEPA world models for planning on PushT with a shared detector and MPPI planner. The apparent seed-0 planning gap, **12% versus 4%**, disappeared at seed 1, **4% versus 4%**, so the factorization hypothesis was not supported. The project also shows that near-perfect in-slice probe scores do not reliably predict closed-loop planning success.

### [Decision Transformer for Limit Order Book Trading](https://github.com/clement-callaert/Decision-Transformer-LOB-Trading) 📈

A fully traceable offline-RL benchmark on FI-2010, built with Côme Genet. The canonical protocol uses five seeds, Days 1 to 8 for training, Day 9 for checkpoint selection, and untouched Day 10 evaluation. The preregistered primary Decision Transformer did not beat buy-and-hold under the frozen cost model, but the RTG sweep showed a strong behavioral effect, with mean normalized PnL moving from **-1.976 at P10 to -0.033 at P90**. Metrics, manifests, plots, and reproduction commands are committed.

### [ACES Sycophancy](https://github.com/clement-callaert/aces-sycophancy/tree/submission) 🧠

An adaptation of the NeurIPS 2024 ACES framework to search for regressive sycophancy in a local LLM using programmatic checkers. I diagnosed budget lock-in in a Bayesian ALP selector and added a fixed **20% uniform exploration floor**. Across two seeds, mean archive coverage recovered from **0.792 to 0.917**, while mean QD score increased from **9.219 to 11.000**.

### [Adaptive Latent Search for LPN](https://github.com/clement-callaert/lpn/tree/research/stochastic-latent-search) 🧩

Research extensions to the Latent Program Network codebase for adaptive test-time computation. On a held-out `pattern_2d` split, a REINFORCE stop/continue controller matched fixed-five exact match, **0.90625**, while reducing mean search steps from **5.00 to 4.28**. A gradient-norm heuristic reached the same exact match in **3.44** steps, so the learned controller did not dominate the best heuristic. This is a controlled sandbox result, not an ARC claim.

### [Proximal Diffusion Models in PyTorch](https://github.com/clement-callaert/proximal-diffusion-models-pytorch) ✨

A from-scratch implementation of Proximal Diffusion Models, including reverse-time SDE sampling through proximal operators and proximal-matching denoising. The project reproduces the low-NFE trade-off between sample sharpness and FID on controlled benchmarks.

## Experience 💼

- **Generative AI Engineer, MBDA** (apprenticeship, Sep 2025 - present): multi-agent LLM systems, reinforcement learning for adversarial cybersecurity scenarios, vLLM, Docker, and GPU-cluster deployment.
- **Data Scientist, TotalEnergies Digital Factory** (apprenticeship, Nov 2023 - Sep 2025): machine learning for EV charging, including a transparent pricing model and a station-accessibility predictor.

## Leadership and community 🌱

- **Training Team Member, Automatants**, CentraleSupélec's AI association (Oct 2024 - Nov 2025): workshops and practical sessions on neural networks, Transformers, diffusion models, GANs, and reinforcement learning.
- **President, Rézo Metz-Rennes Fédérés** (Nov 2023 - Apr 2024): led a six-person team operating residential network infrastructure for more than 450 members and managing an annual budget of approximately EUR 70,000.

## Education 🎓

- **M2 Mathematics & Artificial Intelligence**, Université Paris-Saclay, 2025 - 2026
- **Engineering Degree, Mathematics and Data Science**, CentraleSupélec, 2023 - 2026
- **Exchange in AI for Engineering**, Beihang University, Beijing, 2025
- **CPGE Mathematics and Physics**, La Martinière Monplaisir, 2021 - 2023

## Tools 🛠️

**Python, PyTorch, NumPy, pandas, scikit-learn, Hydra, vLLM, Docker, Git, Linux, CI, GPU clusters**

I also use a personal RTX 5090 workstation for research experiments, model serving, and benchmarking.

## How to reach me 📬

- LinkedIn: [in/clement-callaert](https://www.linkedin.com/in/clement-callaert)
- Email: [clement.callaert@student-cs.fr](mailto:clement.callaert@student-cs.fr)

♟️ Outside research, I play chess at around **1750 Elo on chess.com**.
