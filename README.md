# <img src="assets/Rubric.png" width="40" style="vertical-align:middle"> From Holistic Evaluation to Structured Criteria: A Survey of Rubrics Across the Evolving LLM Landscape

## 📌 Overview

This survey introduces the **rubric** as a unifying framework for understanding how LLM evaluation and alignment have co-evolved with successive paradigm shifts. We define a rubric as an explicit set of criteria that transforms complex quality judgments into structured, actionable standards, and demonstrate that their recurrence across otherwise independent efforts in evaluation, reinforcement learning, and safety alignment is not coincidental, but a structural necessity.

The survey is organized into three interconnected parts covering the conceptual foundations of rubrics, a full methodological framework (construction, evaluation, training, and reliability), and a broad synthesis of benchmarks, applications, and future directions.

<p align="center">   <img src="assets/Organization.png" width="90%" alt="Conceptual Organization of This Survey">   <br><em>Figure 1: Conceptual organization of this survey.</em> </p>

------

## 🔑 Core Contributions

### C1: Co-evolutionary Perspective and Unified Taxonomy

We introduce the first framework that situates rubric development within successive LLM paradigm shifts. Rather than treating rubrics as isolated tools, we show that each leap in model capability, from alignment to reasoning, agentic deployment, and self-evolution, has structurally demanded a more sophisticated form of rubric. This co-evolutionary perspective reveals why rubrics have independently recurred across evaluation, RL, and safety research threads, and traces their progression from external evaluation instruments to endogenous mechanisms for self-improvement.

<p align="center">   <img src="assets/Co-evolutionary_Perspective.png" width="90%" alt="Co-evolutionary Framework">   <br><em>Figure 2: The co-evolutionary development of rubrics and LLMs across five paradigm phases.</em> </p>

Alongside this historical arc, we establish a unified taxonomy organized along structural form and evaluative content that brings the full diversity of rubric designs in practice under a single coherent framework.

### C2: Full Rubric Lifecycle and Reliability Boundaries

We systematically examine rubrics across their complete lifecycle: how they are constructed (human expert, automated LLM, human-in-the-loop), how they are optimized from passive refinement to active co-evolution with model capabilities, and how they function as evaluation criteria, training signals, and ultimately endogenous mechanisms within the model itself.

We further conduct the first rigorous **reliability analysis** of rubrics from multiple independent perspectives, covering generation quality, execution fidelity, theoretical constraints, and security threats, revealing that rubric reliability is stratified across dimensions that must each be addressed for evaluation to be trustworthy as a whole.

<p align="center">   <img src="assets/Taxonomy_Tree.png" width="90%" alt="Rubric Research Taxonomy">   <br><em>Figure 3: Taxonomy of rubric research across construction, evaluation, training, and reliability.</em> </p>

### C3: Benchmarks, Applications, and Research Roadmap

We provide the first comprehensive synthesis of rubric-based benchmarks spanning general, professional, deep research, multimodal, and academic categories, and downstream applications across healthcare, law, education, finance, society, and scientific research. Across all domains, a shared tension recurs: translating the implicit judgment standards of domain experts into explicit, programmatically verifiable criteria without sacrificing the depth that makes those standards meaningful.

We conclude with four open research directions (reliable rubric generation, dynamic rubric design, multimodal extension, and rubric internalization) that together define the trajectory toward scalable supervision and self-evolving aligned AI systems.

------

## 🗺️ Survey Structure

```
Part I: Foundation
  └── Chapter 2: What Is a Rubric? Definitions, Taxonomy, and Paradigm Shifts

Part II: Core Framework
  ├── Chapter 3: How Are Rubrics Constructed and Optimized?
  ├── Chapter 4: How Do Rubrics Power Evaluation?
  ├── Chapter 5: How Do Rubrics Power Training?
  └── Chapter 6: How Reliable Are Rubrics?

Part III: Impact and Outlook
  ├── Chapter 7: Where Are Rubrics Applied?
  └── Chapter 8: Where Does Rubric Research Head?
```

------

## 📚 Paper List

The full categorized paper list is coming soon. Stay tuned!

------

## 📬 Contact

For questions, suggestions, or paper additions, please open a GitHub Issue or reach out via email at methanechen@126.com.