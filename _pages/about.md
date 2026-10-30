---
permalink: /
title: ""
description: "Shuyuan Zhao — Statistics undergraduate at Guangzhou University, interested in statistical inference, data modeling and robotics control."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<section class="profile-section" markdown="1" aria-labelledby="about-me">

# About Me {#about-me}

I am an undergraduate in **Statistics at Guangzhou University**, with graduation expected in July 2027. My research focuses on exact Poisson inference with unknown backgrounds. Through competitions, I have also explored longitudinal health data and sustainable tourism modeling. I am interested in applying mathematical and computational methods to real-world problems.

During my robotics internship, I worked on **admittance and impedance control** for a six-axis manipulator through MuJoCo simulation and integration testing on an ELFIN10-L robot. I have received an offer for the **Redbird MPhil** at **HKUST (Guangzhou)**, with entry expected in September 2027.

[Curriculum Vitae (PDF)]({{ '/files/Zhao_Shuyuan_CV.pdf' | relative_url }}) · [中文主页]({{ '/zh/' | relative_url }})

</section>

<section class="profile-section" markdown="1" aria-labelledby="education">

# Education {#education}

<div class="education-list" markdown="0">
<div class="education-entry">
<a class="education-logo" href="https://www.hkust-gz.edu.cn/" target="_blank" rel="noopener noreferrer" aria-label="Visit the HKUST Guangzhou website">
<img src="{{ '/images/universities/hkust-gz-logo.png' | relative_url }}" alt="HKUST Guangzhou logo" width="46" height="46" loading="lazy">
</a>
<div class="education-details">
<h3 class="education-school"><a href="https://www.hkust-gz.edu.cn/" target="_blank" rel="noopener noreferrer">HKUST (Guangzhou)<span class="education-external" aria-hidden="true"> ↗</span></a></h3>
<p class="education-degree">Redbird MPhil</p>
<p class="education-note">Offer received</p>
</div>
<p class="education-dates">Sep 2027 – Jul 2029<br><span>Expected</span></p>
</div>
<div class="education-entry">
<a class="education-logo" href="https://www.gzhu.edu.cn/" target="_blank" rel="noopener noreferrer" aria-label="Visit the Guangzhou University website">
<img src="{{ '/images/universities/gzhu-mark.png' | relative_url }}" alt="Guangzhou University emblem" width="46" height="46" loading="lazy">
</a>
<div class="education-details">
<h3 class="education-school"><a href="https://www.gzhu.edu.cn/" target="_blank" rel="noopener noreferrer">Guangzhou University<span class="education-external" aria-hidden="true"> ↗</span></a></h3>
<p class="education-degree">B.Sc. in Statistics</p>
</div>
<p class="education-dates">Sep 2023 – Jul 2027<br><span>Expected</span></p>
</div>
</div>

</section>

<section class="profile-section" markdown="1" aria-labelledby="publications">

# Publications {#publications}

<div class="profile-entry publication-entry" markdown="1">

**Dynamic truncation and the Berger–Boos corrected h–function method for optimal exact Poisson confidence intervals with unknown backgrounds**<br>
Lu, H., **Zhao, S.**, & Wu, Q.<br>
*Manuscript submitted to [Statistical Papers](https://link.springer.com/journal/362).*

Research on exact Poisson inference for weak signals and unknown backgrounds, combining dynamic truncation, Berger–Boos correction and the h-function. The study compares interval coverage and efficiency, with an application to KARMEN neutrino detection data.

</div>

<div class="profile-entry publication-entry" markdown="1">

**[Sustainable Tourism Model Based on DPSIR and Non-linear Programming — A Case Study of Juneau, Alaska, USA](https://doi.org/10.61369/ASDS.12187)**<br>
Wang, J., **Zhao, S.**, & Gu, Z.<br>
*Applied Statistics and Data Science (ASDS), 1(3), 112–116, 2025.*

Combines entropy-weighted TOPSIS, the DPSIR framework and nonlinear programming with a genetic algorithm to study sustainable tourism in Juneau, balancing tourism revenue, resource constraints and residents' interests.

[DOI](https://doi.org/10.61369/ASDS.12187) · [PDF]({{ '/files/publications/sustainable-tourism-dpsir-2025.pdf' | relative_url }})

</div>

</section>

<section class="profile-section" markdown="1" aria-labelledby="research-experience">

# Research Experience {#research-experience}

<div class="profile-entry" markdown="1">

### Exact Poisson inference with unknown backgrounds
<p class="entry-meta"><em>Research member · September 2025–April 2026</em></p>

- Investigated exact inference for rare-event data, with application contexts in high-energy physics and biomedical detection.
- Participated in research on dynamic truncation using Poisson quantiles, Berger–Boos correction and the h-function.
- Compared initial, one-time improved and optimal exact confidence intervals across Bayesian, IM and NIM methods through simulation studies.

</div>

</section>

<section class="profile-section" markdown="1" aria-labelledby="internship-experience">

# Internship Experience {#internship-experience}

### Xinbairen Robotics — Control Algorithms Department
<p class="entry-meta"><em>Reinforcement Learning Assistant Engineer Intern · June–September 2026</em></p>

<div class="internship-project" markdown="1">

#### Cartesian-space admittance control for a six-axis manipulator

- Built a mass–damping–stiffness admittance model, verified responses to three-dimensional forces in MuJoCo, and corrected coordinate transformations and response directions affected by inconsistent orientation representations.
- Contributed to fixed-point admittance deployment in CODESYS and the addition of position offsets along linear trajectories; used segmented interpolation to reduce response lag and corrected ACS/MCS coordinate-system settings.
- Tested Python–CODESYS TCP communication and integration with an ELFIN10-L robot, addressing sensor zero offsets, sampling periods and target-command update rates, and identifying stalled force-sensor data updates.

</div>

<div class="internship-project" markdown="1">

#### Joint-space impedance control for a six-axis manipulator

- Developed spring–damper impedance control from joint position and velocity errors, contributing to six-axis control implementation and CST torque-output tests on hardware.
- Integrated Pinocchio-based gravity compensation with friction compensation, calibrated drive-torque mappings and scaling, adjusted torque limits and added connection-loss protection.
- Corrected the ELFIN10-L forward-kinematics model, verified forward/inverse kinematics and parallel comparisons of the original and revised interpolators, and conducted linear-trajectory and inclined-surface contact tests.

</div>

</section>

<section class="profile-section" markdown="1" aria-labelledby="competition-experience">

# Competition Experience {#competition-experience}

<div class="profile-entry competition-entry" markdown="1">

### Multidimensional health risks in middle-aged and older adults
**2025 11th National College Students Statistical Modeling Competition — Guangdong Division First Prize**

<p class="entry-meta"><em>Team lead · March–May 2025</em></p>

- Led topic selection, research framework design, modeling strategy and team coordination for a longitudinal study of health risks.
- Constructed 6,800+ modeling samples from 21,000+ CHARLS records across three waves; combined Random Forest and XGBoost feature selection with fixed-effects models and GEE.
- Identified 12 key frailty predictors from 26 indicators across five risk dimensions, and analyzed age-specific patterns to inform stratified intervention and community health planning.

</div>

<div class="profile-entry competition-entry" markdown="1">

### Sustainable tourism optimization
**2025 Mathematical Contest in Modeling (MCM) — Honorable Mention**

<p class="entry-meta"><em>Team member, report writing and modeling analysis · January 2025</em></p>

- Synthesized literature and multi-source data for a DPSIR indicator framework, and contributed nonlinear optimization analysis balancing tourism revenue, ecological constraints, infrastructure and residents' interests in Juneau.
- Organized the report, visualized genetic-algorithm results and supported a comparison between Juneau and Xi'an.

</div>

<div class="profile-entry competition-entry" markdown="1">

### High-entropy alloy platform commercialization
**China International College Students' Innovation Competition (2025), Guangdong Division — Silver Prize**

<p class="entry-meta"><em>Technology commercialization and business plan lead · April–August 2025</em></p>

- Translated an ML-assisted alloy performance prediction and optimization platform into a product proposal for aerospace and advanced manufacturing.
- Conducted market analysis and coordinated technical, marketing, financial and legal inputs to develop the commercialization strategy and business plan.

</div>

</section>

<section class="profile-section" markdown="1" aria-labelledby="honors-awards">

# Honors & Awards {#honors-awards}

- **2025** — Guangdong Division First Prize, 11th National College Students Statistical Modeling Competition.
- **2025** — Honorable Mention, Mathematical Contest in Modeling (MCM).
- **2025** — Guangdong Division Silver Prize, China International College Students' Innovation Competition.
- **2025** — National Third Prize, 15th “Zhengda Cup” National College Students Market Survey and Analysis Competition.
- First-Class Scholarship, Guangzhou University.

</section>

<section class="profile-section" markdown="1" aria-labelledby="technical-skills">

# Technical Skills {#technical-skills}

- **Programming and tools:** Python, R, Linux, Git, CODESYS.
- **Statistics and data analysis:** statistical modeling, longitudinal data analysis, machine learning, survey data analysis, NumPy, Pandas, Matplotlib.
- **Robotics:** MuJoCo, Pinocchio, admittance control, impedance control, PD/PID and dynamics compensation.
- **Languages:** Mandarin (native), English (IELTS 6.5).

</section>
