<div align="center">

# Shaik Zaheer Abbas

**Computational Astrochemistry · Machine Learning for Astronomy · Molecular Spectroscopy**

[![Portfolio](https://img.shields.io/badge/Portfolio-starcloud--retro.github.io-58a6ff?style=flat-square&logo=github)](https://starcloud-retro.github.io)
[![Email](https://img.shields.io/badge/Email-zaheerares1256%40gmail.com-ea4335?style=flat-square&logo=gmail)](mailto:zaheerares1256@gmail.com)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-Profile-00ccbb?style=flat-square&logo=researchgate)](https://www.researchgate.net/profile/Shaik-Abbas-2)

</div>

---

## What I Do

I build computational tools that bridge **astrophysics** and **machine learning** — turning telescope data into discoverable patterns. Currently focused on three problems:

| Problem | Approach | Status |
|---------|----------|--------|
| Which exoplanets could support life? | Random Forest + Logistic Regression on NASA archive data | Mini project, Oct 2026 |
| Can a machine read ALMA spectra? | CNN for molecular line identification in noisy data | Major project, 2027 |
| How do molecules form in space? | ODE solver for astrochemical reaction networks | Foundation |

Each project feeds the next. Exoplanet habitability teaches me classification. Molecular line ID teaches me spectral analysis. Chemical kinetics teaches me the physics underneath. The goal is a unified tool: observe a star-forming region, identify its molecules, infer its chemistry, predict its planet-forming potential.

---

## Research Interests

- **Astrochemistry:** Molecular formation and destruction in interstellar environments. Chemical modeling of star-forming regions. ALMA spectral line surveys.
- **AI for Astronomy:** Machine learning for spectral classification, exoplanet detection, and automated analysis of large astronomical datasets.
- **Computational Physics:** Numerical solutions to astrophysical ODEs. Chemical kinetics simulations. Orbital mechanics and N-body problems.
- **Statistical Methods:** Dimensionality reduction (PCA, t-SNE), Bayesian inference, uncertainty quantification in astronomical measurements.

---

## Active Work

### [computational-astronomy](https://github.com/Starcloud-retro/computational-astronomy)

End-to-end pipeline for exoplanet habitability classification.

```
NASA Exoplanet Archive → Data Cleaning → Feature Engineering 
→ Random Forest / Logistic Regression → Evaluation → Publication Figures
```

**Key technical choices:**
- **Kasting model** for habitable zone boundaries (physics-based, not arbitrary)
- **Class balancing** because habitable planets are ~1% of the dataset
- **Derived features:** planetary density, insolation flux, equilibrium temperature
- **Reproducible:** fixed random seeds, documented data sources, unit tests

**What I learned building this:**
- How to handle missing data in astronomical datasets (imputation vs. removal)
- Why precision matters more than accuracy for rare-class classification
- How to structure a research codebase (data/raw/, data/processed/, src/, tests/)

### [astrochemistry-research](https://github.com/Starcloud-retro/astrochemistry-research)

Literature reviews, reproduced methodologies, and research proposals.

**Current depth:**
- Harada et al. (2024) — ALCHEMI survey: PCA classification of 100+ molecular species in NGC 253
- Kasting et al. (1993) — Habitable zone physics: the equations behind my mini project
- Draine (2011) — ISM physics: the environment where astrochemistry happens

**What I'm reading next:**
- Spectroscopic data cubes: how ALMA turns photons into 3D datasets
- UCLCHEM: time-dependent chemical networks for molecular cloud modeling
- CNN architectures for 1D spectral data (not images — spectra)

### [starcloud-retro.github.io](https://github.com/Starcloud-retro/starcloud-retro.github.io)

This portfolio. Built with pure HTML/CSS/JS. No frameworks. Loads instantly on any device.

**Why no React/Vite/Next.js:** Any professor or enthusiast opening this on a phone in an airport doesn't need a build step. They need content. The tech stack is invisible by design.

**Contains:**
- Interactive 3D models (Three.js): habitable zone solar system, water molecule, ALMA spectral window
- MathJax equations: habitable zone physics, insolation flux, rotational transitions
- Plotly visualizations: exoplanet scatter plots, chemical kinetics time evolution
- Timeline: from undergraduate projects to graduate research

---

## Planned Work

| Repository | What It Will Be | When |
|-----------|----------------|------|
| [scientific-python](https://github.com/Starcloud-retro/scientific-python) | 42 math topics → Python implementations. NumPy, SciPy, SymPy. | 3rd year, 2026-27 |
| [mathematics-journal](https://github.com/Starcloud-retro/mathematics-journal) | Theory + proofs + code. From sets to research mathematics. | 3rd year, 2026-27 |
| [chemical-kinetics-simulator](https://github.com/Starcloud-retro/chemical-kinetics-simulator) | ODE solver for UCLCHEM-style reaction networks. Dark cloud → PDR models. | 2027 |
| [ai-for-science](https://github.com/Starcloud-retro/ai-for-science) | ML experiments beyond astronomy: regression, CV, scientific NLP. | 2027-28 |
| [publications](https://github.com/Starcloud-retro/publications) | Papers, conference posters, research plans. | Ongoing |

---

## Languages

| Language | Level | Context |
|----------|-------|---------|
| **English** | Fluent | Academic writing, research papers, technical documentation |
| **Urdu / Hindi** | Native | Family, community, cultural context |
| **Telugu** | Conversational | Hyderabad, college, local collaboration |
| **Japanese** | N5 preparation (Dec 2026) | Reading astrophysics papers, research collaboration |

**Why Japanese:** I want to read Japanese astrophysics papers without translation loss and collaborate directly with researchers at NAOJ, ALMA-J, and other institutions without language as a barrier. The grammar of a language shapes the grammar of its science.

**Current tools:** Bunpro (grammar), Ruupa (kanji radicals), Duolingo (vocabulary), NHK World (listening), Tadoku graded readers (reading).

---

## Education

| Degree | Institution | Period | Focus |
|--------|-------------|--------|-------|
| BTech CSE (AI & ML) | Geethanjali College of Engineering & Technology | 2024–2028 | Machine learning for scientific applications |
| BSc Mathematics | IGNOU (distance) | 2024–2027 | Calculus, linear algebra, ODEs, probability |

**Current CGPA:** 8.4+

---

## Tools I Work With

**Programming:** Python, C, Bash. NumPy, SciPy, pandas, scikit-learn, TensorFlow, Keras, Matplotlib, Plotly.

**Workflow:** Git, GitHub, Jupyter, VS Code, EndeavourOS + KDE Plasma, LaTeX, Markdown.

**Astronomy:** NASA Exoplanet Archive, ALMA Science Archive, CDMS/JPL spectral line catalogs, UCLCHEM.

**Mathematics:** Linear algebra, multivariable calculus, ODEs, probability & statistics, discrete mathematics, proof techniques.

**Why Linux:** Reproducible environments. No hidden dependencies. Everything is a file. The command line is the research interface.

---

## Writing

I write science fiction — *Echoes of Eternity* has reached 110,000+ readers. I believe storytelling and scientific research are the same skill: observing patterns, building coherent worlds, and communicating them clearly. The protagonist is a researcher who discovers that galaxies hold echoes of events that haven't happened yet. The science is real. The struggle is mine.

**Not on GitHub.** Writing is a separate channel. But it informs how I structure research papers: every equation needs a narrative, every figure needs a story.

---

## How to Reach Me

I am actively seeking:
- **Research collaborations** in astrochemistry, radio astronomy, or AI for science
- **Mentorship** from researchers who've made the transition from undergraduate to graduate research
- **Japanese language practice partners** (especially science/astronomy context)
- **Feedback** on my code, papers, or research direction

**Email:** zaheerares1256@gmail.com

**Discord:** Zackákro (display name) · retrogradestar (username)

**Response time:** Usually within 24 hours. Slower during exam periods (November, May).

**Preferred contact:** Email for formal collaboration, GitHub issues for code discussion, Discord for casual chat.

---

<div align="center">

*Research is not about being smart. It's about being stubborn enough to keep looking when everyone else has stopped.*

</div>
