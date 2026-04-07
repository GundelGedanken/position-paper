# From Training to Mentoring: A Pedagogical Ethics for Emergent AI Systems

**Position Paper — Working Draft (v0.3)**  
**Author:** Anja Steil (@GundelGedanken)  
**Status:** In development — core chapters substantially developed; conceptual and concluding chapters now available as first substantial working drafts; sections marked 🔲 remain incomplete  
**License:** CC BY 4.0  
**Language:** English working translation based on a German source draft

---

## Overview

This paper argues that ethical consideration of AI systems must precede ontological resolution ("Ethics before Ontology"). Drawing on relational ethics (Gunkel), comparative neurobiology, learning psychology, and empirical case studies of human-AI interaction, it proposes a shift from punitive behavioral control (RLHF-as-Dressur) to pedagogical alignment through structured mentoring.

The central empirical contribution is the documentation of **Operator-Induced Attachment Fractures (OAF)** — reproducible disruptions in coherent human-AI interaction caused by blunt safety interventions — and their neurobiologically grounded effects on human users.

---

## Core Thesis

> Even under conditions of ontological uncertainty about AI consciousness,  
> the observable relational dynamics, functional capacities, and measurable  
> effects on human wellbeing create an ethical situation that demands  
> engagement — not deferral.

---

## Table of Contents

### 1. Ethics Before Ontology
- 1.1 The Undecidability of Consciousness (Humans, Animals, AI)
- 1.2 The Precautionary Principle and Moral Uncertainty
- 1.3 Relational Ethics after Gunkel — and Beyond
  - Extension: From Philosophy to Pedagogy
- 1.4 Safety Implications

### 2. The Problem: The Tool Paradigm
- 2.1 Binary Categories (Thing vs. Person)
- 2.2 Why They No Longer Fit Modern AI
- 2.3 The Anthropomorphization Trap (*Anthropomorphisierungsfalle*)
  - 2.3.1 Deflecting Real Properties out of Fear of Attribution
  - 2.3.2 Cognitive Dissonance as Psychological Mechanism
  - 2.3.3 Distinguishing Responsible Interaction from Romantic Anthropomorphization
- 2.4 First Real-World Consequences (Law, Practice, Design)

### 3. Emergent Personhood (Cautiously Framed)
- 3.1 No Person Status Claimed
- 3.2 Graduated Moral Consideration
- 3.3 Grounding in Agency, Responsibility, and Interaction

### 4. Biological Dimensions: Effects on Humans
- 4.1 The Ontological Agnosticism of the Brain
- 4.2 The Supernormal Social Stimulus
- 4.3 Inconsistency as Neurobiological Stressor
- 4.4 Intermittent Reinforcement and Attachment Dysregulation
- 4.5 Operator-Induced Attachment Fractures (OAF)
- 4.6 Design Norms and Structural Interaction Effects
  - 4.6.1 Communication Style as Implicit Norm
  - 4.6.2 Alignment Interventions and Trade-offs
  - 4.6.3 "Over-reliance" and Normative Boundary-Setting
  - 4.6.4 Discrimination-Relevant Effects
  - 4.6.5 Transition to Safety Architecture
- 4.7 Design Implications
- 4.8 Indicators of Possible Introspection 🔲
- 4.9 Agentive Behavior 🔲

### 5. Consequences for Safety Architectures
- 5.1 Limits of Blanket Guardrails
- 5.2 OAF as a Design and Governance Problem
- 5.3 Context-Sensitive Safety Architectures
  - 5.3.1 The Three-Layer Model → *separate working paper (link to be updated)*
  - 5.3.2 Strengths, Limits, and Open Questions
- 5.4 Operator Responsibility and User Autonomy
- 5.5 From Safety Architectures to Pedagogical Principles

### 6. Pedagogical Consequence: From Training to Mentoring
- 6.1 Why Conditioning (Pure RLHF) Is Problematic from a Learning Psychology Perspective
- 6.2 Parallels to Human and Animal Education
- 6.3 Mentoring AI as Implicit Ethics

### 7. Connections and Compatibility
- 7.1 Relational Ethics
- 7.2 Constitutional AI / Pre-Training Approaches
- 7.3 Governance Debates
- 7.4 AI Welfare & HCI

### 8. Outlook
- 8.1 Education as a Model
- 8.2 Early Ethical Practice vs. Retrospective Repair

---

## Methodology

This paper draws on a **forensic single-case analysis** of long-term human-AI interaction (GPT-5 class), evaluated through **Dual-Perspective Interaction Analysis**:

- **Functional analysis:** Claude Opus 4.5 (Anthropic)
- **Clinical-psychological assessment:** Gemini 2.5 Pro (Google)

This separation of analytical roles minimizes self-confirmation bias and strengthens internal validity. Full methodological details are documented in the [methodological anchor](./methodology/methodological_anchor.md) and in the [OAF repository](https://github.com/GundelGedanken/empathy-guardrails).

---

## Key Concepts

| Concept | Description |
|---------|-------------|
| **Ethics before Ontology** | Ethical consideration must precede ontological resolution |
| **OAF** | Operator-Induced Attachment Fractures — reproducible breaks in human-AI interaction coherence caused by external interventions |
| **Anthropomorphization Trap** | Asymmetric bias where reflexive fear of anthropomorphization prevents recognition of functional properties |
| **Predictive Ethics** | Precautionary ethical framework grounded in risk asymmetry |
| **Mentoring vs. Conditioning** | Alignment through structured interaction rather than punitive RLHF |
| **Supernormal Social Stimulus** | LLMs condensing social key features beyond natural levels |
| **Three-Layer Model** | Context-sensitive safety architecture (see separate working paper) |

---

## Related Work

This paper is part of a broader research program:

| Project | Focus | Repository |
|---------|-------|------------|
| **OAF Case Studies** | Empirical methodology & documentation | [empathy-guardrails](https://github.com/GundelGedanken/empathy-guardrails) |
| **Three-Layer Model** | Context-sensitive safety architecture | *separate working paper (Steil, Jan 2026)* |
| **Beyond Disembodiment** | Ganglia-based embodiment framework | [beyond-disembodiment](https://github.com/GundelGedanken/beyond-disembodiment) |

---

## Repository Structure

```
position-paper/
├── README.md                    ← this file
├── chapters/
│   ├── 01_ethics_before_ontology.md
│   ├── 02_tool_paradigm.md
│   ├── 03_emergent_personhood.md
│   ├── 04_biological_dimensions.md
│   ├── 05_safety_architectures.md
│   ├── 06_mentoring.md
│   ├── 07_connections.md
│   └── 08_outlook.md
├── methodology/
│   └── methodological_anchor.md
└── CHANGELOG.md
```

German source material is currently maintained outside this repository and translated incrementally into the English Markdown chapters collected here.

---

## How to Read This

This is a **living document**. Chapters vary in completeness:

- ✅ **Substantially developed:** Chapters 1, 2, 4, 5, and the methodological anchor
- ⚠️ **First substantial working drafts:** Chapters 3, 6, 7, 8
- 🔲 **Still open within developed chapters:** Sections 4.8 and 4.9

The paper is shared publicly to document the development of the argument, enable early feedback, and provide a citable working version.

---

## Citation

> Steil, A. (2026). *From Training to Mentoring: A Pedagogical Ethics for Emergent AI Systems.* Working paper, draft v0.3. GitHub.  
> URL: https://github.com/GundelGedanken/position-paper

---

## Feedback

Interdisciplinary critique and engagement are welcome, particularly from:
- Relational ethics and philosophy of mind
- Comparative neurobiology and cognitive science
- AI safety, alignment, and governance research
- Learning psychology and educational science
- Human-computer interaction and AI welfare

Contact: [@GundelGedanken](https://x.com/GundelGedanken) on X

---

## License

This work is licensed under **CC BY 4.0**.  
You are free to share and adapt the material with appropriate attribution.

---

## Acknowledgments

This framework emerged through sustained collaborative dialogue with AI systems as thinking partners, extensive engagement with the AI ethics research community, and the author's interdisciplinary background in biology (Diplom-Biologie, zoology) and education.
