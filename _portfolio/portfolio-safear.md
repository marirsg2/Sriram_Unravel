---
title: "SafeAR: Risk-Aware Algorithmic Recourse"
excerpt: "Mitigating downside risks in actionable algorithmic recourse policies under stochastic execution (AAAI-24 Oral)."
collection: portfolio
permalink: /portfolio/portfolio-safear/
date: 2024-02-01
pillar: "Human-AI Interaction"
---

<div class="project-pillar-badge"><i class="fa fa-tag"></i> Pillar: <strong>Human-AI Interaction</strong></div>

<div class="project-tags">
  <span class="tag">Algorithmic Recourse</span> <span class="tag">CVaR</span> <span class="tag">Human-in-the-Loop</span> <span class="tag">Safe RL</span>
</div>

### Overview
Algorithmic Recourse empowers users to reverse unfavorable algorithmic decisions (e.g. loan denials or credit limits). However, classical recourse algorithms implicitly assume that whenever a user attempts an action, it succeeds deterministically. In reality, human efforts have uncertain outcomes.

**SafeAR** reformulates algorithmic recourse through the lens of risk-sensitive Markov Decision Processes:
- Minimizes the probability of catastrophic downside trajectories using **Conditional Value-at-Risk (CVaR)** criteria.
- Provides actionable, robust recourse policies that remain safe even under significant human execution noise.
- Recognized with an **Oral Presentation (Top 2%)** at AAAI 2024.

