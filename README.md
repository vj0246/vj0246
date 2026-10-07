<img align="right" src="https://komarev.com/ghpvc/?username=vj0246&color=blue&style=flat-square&label=PROFILE+VIEWS" height="20"/>

<div align="center">

# Vivaan Jain

<a href="https://github.com/vj0246"><img src="https://readme-typing-svg.demolab.com/?lines=Quantitative+Researcher;Systematic+Equity+on+Indian+Markets;Statistics+and+Backtest+Validation;Olympiad+Trained+Mathematics&font=Fira+Code&center=true&width=520&height=45&color=58A6FF&vCenter=true&size=22&pause=1000"/></a>

<a href="https://www.linkedin.com/in/vivaan-jain-398160279"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" height="28"/></a>
<a href="https://vivaan-jain-portfolio.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" height="28"/></a>
<a href="https://medium.com/@vivaan.jain246"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" height="28"/></a>
<a href="https://codeforces.com/profile/Vj0246"><img src="https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white" height="28"/></a>
<a href="https://instagram.com/vivaan.jainn"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" height="28"/></a>
<a href="mailto:vivaan.jain246@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="28"/></a>

</div>

> *The first principle is that you must not fool yourself, and you are the easiest person to fool.* Richard Feynman

I am a quantitative researcher working on systematic equity in Indian markets. I own the whole chain: point in time data from primary NSE sources, cross sectional signals, portfolio construction under the full Indian cost stack, and the validation that decides whether a result is skill or luck.

The most useful thing I have produced is a documented list of what does not work. A beautiful backtest is the default outcome of insufficient care, so the only interesting question about a number is what had to be true for it to survive being counted.

Mathematics came first. Olympiad rounds at school, then the entrance papers, and now the parts of the degree the work actually runs on: statistical modelling and operational research. Markets are what I point it at.

- 🎓 B.Tech Computer Engineering (Honours, Data Science), Dwarkadas J. Sanghvi College of Engineering, Mumbai, 2024 to 2028
- 🔬 Focus: cross sectional momentum, portfolio construction, execution costs, and overfitting control
- 📐 Mathematics I, Mathematics II and Statistical Modelling: 10 out of 10
- 💼 Previously Full Stack Engineering Intern at Zeex AI (Apr to Jun 2026), production grade audio pipelines
- 📫 Open to quantitative research internships: [vivaan.jain246@gmail.com](mailto:vivaan.jain246@gmail.com)

---

## 🏆 Achievements

| | |
|---|---|
| 🥇 **First place** | Urban Empire, data driven resource allocation competition. A constrained budget allocation problem, the same shape as sizing a book |
| 🥉 **Third place** | Alpha Nova bi weekly, Cycle 3, Season 1 |
| 🥉 **Bronze medal** | IMO regionals |

---

## 🔬 Selected Research

| Project | What it is | Result |
|---|---|---|
| **[Artha](https://github.com/vj0246/artha)** | Weekly cross sectional momentum book on NSE equities. Point in time data, Ledoit Wolf minimum variance construction, Garleanu Pedersen partial adjustment, volatility targeting. Paper traded nightly, built on zero paid data | Net **Sharpe 1.02**, **13.7% CAGR**, **−28%** max drawdown, 2012 to 2026, after the full Indian cost stack. Deflated significance reported honestly at 0.20 |
| **[FullBacktester](https://github.com/vj0246/Backtesting-Framework)** | A backtesting library where look ahead is a construction error, not a discipline problem. On PyPI | Two engines agree to **1e-9**. AST and perturbation leakage detectors. Deflated Sharpe and PBO are first class metrics |
| **[Overnight Return Prediction](https://github.com/vj0246/Overnight-Return-Predictor)** | Overnight gap across 208 NSE symbols: magnitude, direction, calibrated confidence, four independently fitted models | Pooled **rank IC 0.178** at t = 24.5, calibration error **0.021**, and a residual direction score of 0.0001 that the write up leads with |
| **[Multi Horizon Transformer](https://github.com/vj0246/Multi-Horizon-Transformer-for-Systematic-Equity-Direction-Forecasting)** | Transformer forecasting Nifty 50 direction across 20 horizons, plus a cross sectional track on 85 NSE stocks | Mean test AUC 0.5033 and deflated Sharpe 0.916, below the 0.95 bar. Reported as no edge, with leakage rules and bootstrap intervals |
| **[FinIntel](https://github.com/vj0246/FinIntel)** | Agentic equity desk on LangGraph with human approval gates. Every number is computed in Python, the LLM only narrates | 31 tool ReAct agent, deterministic backtest and stress engine, compliance guardrail on every output |

---

## 🧪 What did not work

Nulls are the expensive output of research, and the reason to trust the rest.

- **Machine learning does not beat momentum.** Ridge, LightGBM, MLP and a Transformer under one purged protocol. PBO of 0.86 means the in sample winner is overfit in 24 of 28 splits.
- **Post earnings drift runs backwards in India.** Across 1.48M timestamped exchange announcements the biggest positive surprises reverse, t = −6.9.
- **News sentiment gating subtracts value.** Sharpe 0.06 against 0.58.
- **A learned trading speed policy ties the fixed constant.** PBO 0.93 over 728 weekly decisions. The agent was reporting that the surface is flat.
- **Decomposition preprocessing is look ahead.** A literature reports Sharpe above 3 on daily equity forecasting after EMD or CEEMDAN. I reproduced it exactly (IC 0.41, Sharpe 3.6), then recomputed the same transform causally. The whole edge vanished, IC −0.04. The leaky minus causal gap is the published result.

Mistakes I caught in my own work and fixed in public: a corporate action feed that invented a +398% phantom return, a position cap bug that inflated a Sharpe from 1.018 to 1.119, and a significance claim corrected from p = 0.0415 to p = 0.655.

---

## 🛠 Stack

<img src="https://skillicons.dev/icons?i=py,cpp,c,pytorch,tensorflow,sklearn,numpy,pandas,postgres,sqlite,docker,git,github,linux,latex&theme=dark"/>

---

## 📅 3D Contribution Calendar

<img src="https://raw.githubusercontent.com/vj0246/vj0246/main/profile-3d-contrib/profile-night-green.svg"/>

---

## 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=vj0246&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true)
![](https://github-readme-streak-stats.herokuapp.com/?user=vj0246&theme=tokyonight&hide_border=true)
<img src="https://raw.githubusercontent.com/vj0246/vj0246/main/profile/top-langs.svg?v=6"/>

---

## ⚙️ Also builds

When the research is not the point I ship production AI systems: [MindVault](https://github.com/vj0246/MindVault), a multi tenant RAG app with hybrid retrieval, [AuditMind AI](https://github.com/vj0246/auditmind-ai), a multilingual ASR and diarization pipeline across 13 Indian languages, and [ApplyPilot AI](https://github.com/vj0246/ApplyPilot-AI), an autonomous agent on LangGraph.
