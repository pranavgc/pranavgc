**Machine learning engineer and researcher.** Two research Master's — Physics at Indian Institute of Science Education and Research (IISER) Kolkata, Data Science at the University of Birmingham. I build models, then spend most of my time working out whether they actually hold up.

Mostly that means catching my own mistakes. My MSc thesis ended with a pre-registered five-seed replication that made me withdraw one of my own significant results: training-seed variance turned out to exceed test-set variance. At a hackathon, a reinforcement learning agent I'd trained scored +24.4 and looked fine, until it sat beside the do-nothing baseline and matched it on all twelve reported metrics. It had learned to hold. Both are in the repositories below, written up as they happened.

Portfolio: **[pranavgc.github.io](https://pranavgc.github.io/)**

---

### Selected work

| Repository | What it is | Result |
|---|---|---|
| [**Uncertainty Quantification in Diffusion Models**](https://github.com/pranavgc/Uncertainty-Quantification-in-Diffusion-Models-for-Chest-Radiography) | MSc dissertation. Can a diffusion model's own sampling noise say which parts of a generated chest X-ray it got right? DDIM inversion to a fixed latent, per-pixel variance over 20 stochastic reconstructions, scored against radiologist annotations on VinDr-CXR. Includes a LoRA fine-tuning extension run after submission. | 0.694 pixel AUROC on the best class; one significant finding retracted on replication |
| [**AMM Liquidity Hunter (RL)**](https://github.com/pranavgc/Amm-Liquidity-Hunter-RL) | PPO agent for concentrated liquidity provision on an automated market maker. 48 hours, three people, second place in the challenge group at Imperial College London's UKFinnovator competition. | +48.02% against +2.44% for the best baseline (19.7×), profitable on 300 of 300 paths, Sharpe 3.87 |
| [**Jaffle Demand Lab**](https://github.com/pranavgc/UOB_dbt_workshop_starter) | Forecasting system with ground truth by construction — seeded simulator, 23-model dbt layer, 114 data tests, nine models under rolling-origin cross-validation. | RMSE 38.2% below baseline; random K-fold measured as overstating accuracy by 6.1% |
| [**Spill the Tea**](https://github.com/pranavgc/Spill_the_tea) | UK restaurant insolvency prediction from alternative data. 5.6M Companies House records resolved across four sources with no shared primary key. | AUC 0.73 on a 5% minority class under 95:5 imbalance |
| [**SkillSync**](https://github.com/pranavgc/SkillSync) | Multi-agent LangChain pipeline: skill extraction, live job-market research, gap analysis. Pydantic-constrained decoding, async FastAPI, Cloud Run. | — |

---

### Currently

- Finishing full fine-tuning on the diffusion uncertainty work — the follow-up to the LoRA result below
- Open to machine learning and research engineering roles, UK or international, including ones that require visa sponsorship
- Where I want to go deeper: model evaluation, generative models, reinforcement learning for markets

### Toolkit

**Modelling** PyTorch · diffusers · PyTorch Geometric · Stable-Baselines3 ·  scikit-learn · XGBoost · LightGBM · Tensorflow 

**Statistics** bootstrap CIs · Wilcoxon / Friedman ·  Benjamini–Hochberg · pre-registration · negative controls · rolling-origin CV

**Deep Learning** latent diffusion (LoRA fine-tuning, DDIM inversion, sampler tuning) · Graph Neural Networks · Convolution Neural Networks · Agentic AI · Reinforcement Learning · Transformers  · Sequence Models · Generative Adversarial Networks

**Engineering** dbt · DuckDB · BigQuery · Docker · · GitHub Actions · pytest · Python · SQL · C++

### Elsewhere

[Portfolio](https://pranavgc.github.io/) · [LinkedIn](https://www.linkedin.com/in/pranav-chandratre-6b7988255) · [Hugging Face](https://huggingface.co/Licht1183) · [pranavchandratre00@gmail.com](mailto:pranavchandratre00@gmail.com)


