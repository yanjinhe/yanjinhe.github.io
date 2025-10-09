---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I'm Yanjin He (<font face=STKaiti>何彦瑾</font>), a 4th-year undergraduate student at School of Mathematical Sciences, Peking University. I visited the University of Notre Dame in the summer of 2024 (lucky to be mentored by [Meng Jiang](http://www.meng-jiang.com/)), and I visited UIUC in the summer of 2025 (lucky to be mentored by [Tong Zhang](https://tongzhang-ml.org/)).

My research interests focus on generative models (especially diffusion models) and large language models (LLMs). I have a soild foundation in mathematics, particularly in probability and statistics, which has provided strong theoretical support for my research.

**<font color="#94070A">I am seeking USA PhD (2026 Fall)</font>**
- GPA: 3.87/4.0 (93.0/100), Major GPA: 3.88/4.0(93.6/100)
- **Top 1**, **Data Science and Big Data Technology** major, School of Mathematical Sciences, Peking University
- Selected Courses: 
  - Mathematical Analysis (I) (96), Geometry (100), Advanced Algebra (I) (99), Abstract Algebra (96), Mathematical Statistics (98)
  - Foundations of Machine Learning (97), Data Structure and Algorithm (96), Introduction to Computation (97), Introduction to Finance (96)
- If you are interested in me (or just chatting with me), please feel free to email me. Thank you for the opportunity.


# 🔥 News
- *2025.09*: &nbsp;🎉 1 Paper (as first author) accepted by **EMNLP 2025** （Main Conference).
- *2025.09*: &nbsp;🏅 I was named a **Merit Student**.
- *2025.09*: &nbsp;🏅 I was awarded the **Leo KoGuan Scholarship**.
- *2025.06*: &nbsp;✈️ I will go to UIUC for summer intern.


# 📝 Publications 
(\*: Equal Contribution)

- **Pre-trained Models Perform the Best When Token Distributions Follow Zipf's Law**\\
**<u>Yanjin He</u>**, Qingkai Zeng, Meng Jiang\\
**_EMNLP 2025_**（Main Conference)\\
[[pdf](https://arxiv.org/pdf/2507.22543)] [[arxiv](https://arxiv.org/abs/2507.22543)]


# 🏅 Talent Programs
- **Top Talent Program in Applied Mathematics and Statistics** (**应用数学及统计拔尖人才计划**), Peking University


# 🏅 Honors and Awards
- **Merit Student**, Peking University, *2025*
- **Leo KoGuan Scholarship**, Peking University, *2025*
- **Merit Student**, Peking University, *2024*
- **Ding Shisun-Gui Linlin Academic Scholarship (丁石孙-桂琳琳优秀学生奖学金)**, Peking University, *2024*
- **WizardQuant Scholarship**, Peking University (1 awardee in the School), *2024*
- **First Prize**, 16th National College Student Mathematics Competition, Beijing, *2024*
- **Panasonic Scholarship**, Peking University (5 awardees in the University), *2023*
- **Outstanding Study Award**, Peking University, *2023*
- **First Prize**, 15th National College Student Mathematics Competition, Beijing, *2023*
## Selected High School Awards
- **Gold Medalist**, Chinese Mathematical Olympiad (CMO Finals), *2021*
- **Outstanding Graduate**, Affiliated High School of South China Normal University, *2021*
- **Top 10 School Stars**, Affiliated High School of South China Normal University, *2020*


# 📖 Educations
- *2022.09 - 2026.07 (now)*, Undergraduate Student, School of Mathematical Sciences, Peking University
- *2021.09 - 2022.07*, Senior High School, Affiliated High School of South China Normal University
- *2018.09 - 2021.07*, Junior High School, Affiliated High School of South China Normal University


# 🔬 Research Experience
**Analyze ODE based diffuison under Fokker-Plank Equation**
- **Supervisor:** [Tong Zhang](https://tongzhang-ml.org/) (UIUC)
- Doing theoretical analysis of the gap of ODE-based diffusion and SDE-based diffusion under the Fokker-Plank Equation assumption, set up a theoretical bound of the Wasserstein-2 distance of the distribution lead by ODE/SDE diffusion.
- Analysing the convergence rate of ODE based diffusion, getting a good bound for ODE-based diffuison by controlling the divergence error and the Fokker-Plank error of score function, which could motivate us a better training objective for diffusion model.

**Investigate the Impact of Tokenizers and decide the optimal tokenizer for pre-trained models**
- **Supervisor:** [Meng Jiang](http://www.meng-jiang.com/) (University of Notre Dame)
- Doing extensive experiments across NLP, genomics, and chemistry demonstrate that models consistently achieve peak performance when the token distribution closely adheres to Zipf's law, which inspire us a criterion for deciding the tokenizer.
- Proposed a method for selecting the most suitable tokenizer for different datasets prior to pre-training and fine-tuning process. Experiments over several domains has proven the robustness nad effectiveness of our method.
- [Pre-trained Models Perform the Best When Token Distributions Follow Zipf's Law](https://arxiv.org/abs/2507.22543), **_EMNLP 2025_**（Main Conference)

**Inference-Time Guidance of ODE-Based Diffusion Models via Langevin Dynamics**
- **Supervisors:** [Liwei Wang](http://www.liweiwang-pku.com/), [Di He](https://dihe-pku.github.io/) (Peking University)
- Combining the Langevin process with the energy-based distribution lead by KL-regularized Reinforcement Learning Objective, we derive a inference time refinement for diffusion model to increase the expected reward of generated images under a specfic differentiable reward function. This method could not only be used to increase the image quality, but also guide the diffusion model toward generating images of specific categories.


# 🔗 Links
(Alphabetical Order) 
- **Advisors & Senior Co-authors**: [Di He](https://dihe-pku.github.io/) (Peking University), [Meng Jiang](http://www.meng-jiang.com/) (University of Notre Dame), [Liwei Wang](http://www.liweiwang-pku.com/) (Peking University), [Tong Zhang](https://tongzhang-ml.org/) (UIUC)
- **Co-authors**: [Nishant Jain](https://scholar.google.com/citations?user=VKcqFW8AAAAJ) (UIUC), [Qingkai Zeng](https://qingkaizeng.github.io/) (University of Notre Dame)
