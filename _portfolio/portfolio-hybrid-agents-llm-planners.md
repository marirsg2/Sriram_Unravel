---
title: "Hybrid-Agent Architectures: TRIP-PAL & GenPlanX"
excerpt: "Combining Large Language Models (LLMs) and automated planners to create verifiable, constraint-satisfying hybrid agent systems for complex workflows."
collection: portfolio
permalink: /portfolio/portfolio-hybrid-agents-llm-planners/
date: 2024-06-01
pillar: "Hybrid-Agent Systems"
---

<div class="project-pillar-badge"><i class="fa fa-tag"></i> Pillar: <strong>Hybrid-Agent Systems</strong></div>

<div class="project-tags">
  <span class="tag">LLMs</span> <span class="tag">Automated Planning</span> <span class="tag">Agentic Workflows</span> <span class="tag">Constraint Satisfaction</span>
</div>

### Overview
Large Language Models excel at understanding unstructured natural language and capturing user preferences, but they fundamentally struggle with arithmetic reasoning, temporal scheduling, and formal constraint adherence. 

In projects like **TRIP-PAL** (Travel Planning with Guarantees) and **GenPlanX**, we architected hybrid neuro-symbolic systems:
- **LLM Frontend:** Handles natural language extraction, conversational preference elicitation, and entity recognition.
- **Formal Translation Layer:** Maps extracted constraints and objectives into standard planning representations (PDDL/RDDL).
- **Symbolic Solver:** Classical planners (e.g. Metric-FF, Fast Downward, CPLEX) compute provably optimal and constraint-respecting plans.
- **Explainable Feedback:** Dispatches verified schedules back to the user with full mathematical correctness guarantees.

