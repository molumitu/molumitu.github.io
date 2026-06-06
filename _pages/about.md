---
permalink: /
title: "Reinforcement Learning is the Ultimate Answer!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% include base_path %}

## Short Bio  
🐣 Born in 2000, I grew up alongside the rise of intelligent machines. I received my B.Eng. degree from the School of Vehicle and Mobility, **Tsinghua University, Beijing, China** <img src="https://flagcdn.com/w20/cn.png" alt="China flag" />, in 2021. I am currently pursuing a Ph.D. in Mechanical Engineering at the same school. From 2025 to 2026, I am a visiting student scholar at the Department of Mechanical Engineering, **UC Berkeley, California, United States** <img src="https://flagcdn.com/w20/us.png" alt="USA flag" />. My research focuses on 🧠 reinforcement learning, and their applications in 🚗 autonomous vehicles and 🤖 robotics.

## Curriculum Vitae  
- 📄 My CV is available here: [Guojian_Zhan_Resume.pdf](https://cloud.tsinghua.edu.cn/f/e61af51e45fe437ba5a7/?dl=1)

# 👋 Welcome to <span style="color:#007bff; font-weight:bold;">@molumitu</span>'s Personal Page  

---

# GPA & Awards
- 🎓 I received my B.Eng. degree from Tsinghua University with a GPA of 3.78/4.0.
- 🎓 I am currently pursuing my Ph.D. with a graduate GPA of 3.93/4.0.  
- 🏅 I have been recognized with the Comprehensive Excellence Award and named an Outstanding Graduate of Tsinghua University.
- 🏅 I was awarded the 2025 National Graduate Scholarship 研究生国奖 (Top 0.2\% nationwide).

# News & Updates
- **2026-05**: SAFLOW and STAPO are submitted to NeurIPS 2026!
- **2026-04**: BOOM-H, BOOM-L, DSAC-E, DSAC-AID and DADP are accepted by ICML 2026!
- **2026-02**: MVP is selected as oral presentation (Top 1\%) by ICLR 2026!
- **2026-01**: MVP is accepted by ICLR 2026!
- **2025-12**: Revision of CTPG is submitted to TPAMI — hope for good luck!
- **2025-09**: BOOM and MPGE are accepted by NeurIPS 2025!
- **2025-08**: BPO is accepted by IEEE TNNLS!
- **2025-05**: PINPE is accepted by IEEE RAL!

# Research Highlights

#### Stable RL for LLMs (STAPO: \url{arxiv.org/abs/2602.15620}), submitted to NeurIPS 2026.

While using RL to improve LLM reasoning has great potential, the training is often unstable, showing sharp changes in entropy and huge jumps in gradients. We studied this problem at the token level and found that removing just a tiny part of the spurious tokens can effectively stabilize the entropy change and lead to steady and continuous performance growth during RL training.


#### Mean Velocity Policy (MVP), ICLR 2026, Oral, Top 1\%.

This work marks the transition of Generative RL into the era of single-step inference, achieving high-fidelity generation and fast execution. We identify a theoretical limitation in current generative mean velocity field learning, the absence of boundary conditions, and consequently propose instantaneous state-wise velocity constraints with a rigorous proof of completeness. By integrating this approach with rejection sampling in an online RL setting, we developed MVP, which performs best on the RoboMimic and OGBench.
% It is promising to extend MVP to VLA models, where the single-step inference capability can significantly reduce the latency, enabling high-frequency, closed-loop control in complex physical environments.

#### Bootstrap Off-policy with World Model (BOOM), NeurIPS 2025.

We propose BOOM, a novel world-model-based RL framework that establishes a bootstrap loop between the policy and the model-driven planner. Utilizing the policy to warm-start the planning process, the planner distills superior trajectories which, in turn, refine the policy via a likelihood-free alignment mechanism. BOOM achieves SOTA performance on the DeepMind Control Suite and HumanoidBench.


# Reviewing & Organizing
- 📝 I am a reviewer for many conferences and journals in the fields of AI and robotics.
(NeurIPS, ICML, ICLR, CoRL, ICRA, IROS, IEEE TNNLS, IEEE RAL, IEEE TITS, etc.)

---

📩 **Contact Me**:  
- **Email**: [zgj21@mails.tsinghua.edu.cn](mailto:zgj21@mails.tsinghua.edu.cn)
- **Email**: [zgj21@berkeley.edu](mailto:zgj21@berkeley.edu)
- **Email**: [zishangzhan@gmail.com](mailto:zgj21@berkeley.edu)

---

# Publications
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>