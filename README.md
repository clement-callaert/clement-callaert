[README_PUBLIC.md](https://github.com/user-attachments/files/30364707/README_PUBLIC.md)
# Hi, I'm Clément Callaert

I am an AI engineer and research-oriented applied mathematician completing two degrees in parallel:

- a **Diplôme d'ingénieur at CentraleSupélec**, with a major in Mathematics and Data Science;
- an **M2 in Mathematics and Artificial Intelligence at Université Paris-Saclay**.

Alongside my studies, I work as a **Generative AI Engineer at MBDA**, where I develop and evaluate multi-agent LLM systems and deploy self-hosted models on GPU infrastructure.

I am looking for a **PhD or research position starting in autumn 2026**. My main interests are generative models, world models, reinforcement learning, LLM agents, test-time computation, and reliable experimental methodology.

## Featured research

### [Ego-World JEPA](https://github.com/clement-callaert/ego-world-sub-jepa)
Controlled study of factored ego/world latent representations for model-based control on PushT. An eight-configuration screening grid and two-seed follow-up did not support a robust planning advantage from factorization: 12% versus 4% success at seed 0, then 4% versus 4% at seed 1. The project also shows that near-perfect in-slice probe scores do not predict closed-loop planning success.

### [Decision Transformer for Limit Order Book Trading](https://github.com/clement-callaert/Decision-Transformer-LOB-Trading)
A fully traceable offline-RL benchmark on FI-2010 with five training seeds, Days 1-8 for training, Day 9 for checkpoint selection, and untouched Day 10 evaluation. Return-to-go conditioning materially changes deployed behavior, although the preregistered Decision Transformer did not beat buy-and-hold under the frozen nonzero-cost protocol. Metrics, plot data, manifests, and canonical figures are machine-readable and reproducible.

### [ACES Sycophancy](https://github.com/clement-callaert/aces-sycophancy)
Adaptation of the NeurIPS 2024 ACES quality-diversity framework to search for regressive sycophancy in a local LLM, using Python-grounded fitness rather than LLM judges. A Bayesian learning-progress selector initially suffered from budget lock-in; adding a fixed 20% uniform exploration floor recovered mean coverage to 0.917 and mean QD score to 11.0 across two seeds.

### [Adaptive Test-Time Search for Latent Program Networks](https://github.com/clement-callaert/lpn/tree/research/stochastic-latent-search)
Research extension of the NeurIPS 2025 Latent Program Network codebase. I reproduced the three-seed `pattern_2d` latent-search baseline and implemented an RL stop/continue controller. On the matched sandbox test, the controller preserved fixed-5 exact match of 0.90625 while reducing average search from 5.000 to 4.281 steps. These are implementation results on in-family tasks, not ARC-AGI claims.

### [Proximal Diffusion Models in PyTorch](https://github.com/clement-callaert/proximal-diffusion-models-pytorch)
From-scratch implementation of Proximal Diffusion Models, including reverse-time SDE sampling and proximal-matching denoising on low-dimensional distributions and MNIST.

### Anonymous generative-modeling manuscript under review
I am also developing a controlled closed-form study of field-regularity criteria and fixed-budget discretization error in probability-flow ODE sampling. Public submission details and the direct repository link are intentionally omitted while the work is under double-blind review.

## Experience and leadership

- **Generative AI Engineer, MBDA**: multi-agent LLM systems, reinforcement learning, vLLM, Docker, and GPU model serving.
- **Data Scientist, TotalEnergies Digital Factory**: machine learning and transparent pricing models for EV-charging data.
- **Training Team Member, Automatants**: technical workshops on neural networks, Transformers, diffusion models, and reinforcement learning in CentraleSupélec's AI association.
- **President, Rézo Metz-Rennes Fédérés**: led a six-person team operating network infrastructure for more than 450 members and managing an annual budget of approximately EUR 70,000.

## Selected coursework

Reinforcement Learning 18/20, Machine Learning 18.6/20, Optimization for Computer Vision 16.28/20, Large-Scale Modeling 16/20, Graphical Models 16/20, and Advanced Unsupervised Learning 15/20.

## Tools

Python, PyTorch, JAX, NumPy, pandas, scikit-learn, Hydra, vLLM, Docker, Git, Linux, GPU clusters, experiment tracking, statistical evaluation, and reproducible research pipelines.

## Contact

- [LinkedIn](https://www.linkedin.com/in/clement-callaert)
- [Email](mailto:clement.callaert@student-cs.fr)
