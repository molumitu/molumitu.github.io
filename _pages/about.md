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

🐣 Born in 2000, I grew up alongside the rise of intelligent machines. I received my B.Eng. degree from the School of Vehicle and Mobility at **Tsinghua University, Beijing, China** <img src="https://flagcdn.com/w20/cn.png" alt="China flag" />, in 2021. I am currently pursuing a Ph.D. in Mechanical Engineering at Tsinghua University. From 2025 to 2026, I am also a visiting student researcher in the Department of Mechanical Engineering at **UC Berkeley, California, United States** <img src="https://flagcdn.com/w20/us.png" alt="USA flag" />. My research focuses on 🧠 reinforcement learning post-training, with an emphasis on reasoning, planning, and decision-making.

<div style="margin: 1.25rem 0; padding: 1rem 1.25rem; border-left: 4px solid #007bff; border-radius: 4px; background-color: #f3f8ff;">
  <strong>Research & Career Highlights</strong>
  <ul style="margin-top: 0.6rem; margin-bottom: 0;">
    <li><strong>6 papers accepted at top-tier (A-level) venues</strong>, including an <strong>ICLR 2026 Oral (top 1%)</strong>.</li>
    <li><strong>4 additional papers currently under review</strong> at top-tier (A-level) venues.</li>
    <li>Actively seeking <strong>industry opportunities in LLM post-training</strong>, particularly in reinforcement learning, reasoning, and agentic systems.</li>
  </ul>
</div>

## Curriculum Vitae

📄 My CV is available here: [Guojian_Zhan_Resume.pdf](https://cloud.tsinghua.edu.cn/f/e61af51e45fe437ba5a7/?dl=1)

## Research Intern Experience

### Didi <span style="color:#007bff;">Voyager AI Lab</span>

- Worked on reinforcement learning post-training for a multimodal planning model, improving MPCI from 30 to 50.
- Developed **Stable RLVR** methods to enhance the reasoning capabilities of large language models.

### ByteDance <span style="color:#007bff;">Seed Robotics</span>

- Worked on **RLVR** post-training of vision-language models (VLMs) for planning.
- Explored **Agentic RL** post-training to strengthen the planning capabilities of VLM-based agents.

## GPA & Awards

- 🎓 Received my B.Eng. degree from Tsinghua University with a GPA of 3.78/4.0.
- 🎓 Maintaining a graduate GPA of 3.93/4.0 during my Ph.D. studies.
- 🏅 Received the Comprehensive Excellence Award and was named an Outstanding Graduate of Tsinghua University.
- 🏅 Awarded the 2025 National Graduate Scholarship (研究生国家奖学金; top 0.2% nationwide).

## News & Updates

- **2026-05**: SAFLOW and STAPO were submitted to NeurIPS 2026.
- **2026-04**: BOOM-H, BOOM-L, DSAC-E, DSAC-AID, and DADP were accepted to ICML 2026.
- **2026-02**: MVP was selected for an oral presentation at ICLR 2026 (top 1%).
- **2026-01**: MVP was accepted to ICLR 2026.
- **2025-12**: A revision of CTPG was submitted to IEEE TPAMI.
- **2025-09**: BOOM and MPGE were accepted to NeurIPS 2025.
- **2025-08**: BPO was accepted by IEEE TNNLS.
- **2025-05**: PINPE was accepted by IEEE RAL.

## Research Highlights

### Stable RL for LLMs

**STAPO** ([arXiv](https://arxiv.org/abs/2602.15620)), submitted to NeurIPS 2026.

Reinforcement learning holds great promise for improving LLM reasoning, but training can be unstable, with abrupt entropy shifts and gradient spikes. Through token-level analysis, we found that filtering a small fraction of spurious tokens can stabilize entropy dynamics and enable steady, sustained performance gains throughout RL training.

### Mean Velocity Policy

**MVP**, ICLR 2026 Oral (top 1%).

MVP advances generative reinforcement learning toward single-step inference, enabling both high-fidelity action generation and fast execution. We identify a theoretical limitation of existing generative mean velocity field learning: the absence of boundary conditions. To address it, we introduce instantaneous state-wise velocity constraints and provide a rigorous proof of completeness. Combined with rejection sampling in an online RL setting, MVP achieves state-of-the-art performance on RoboMimic and OGBench.

<!-- Extending MVP to VLA models could reduce inference latency and enable high-frequency, closed-loop control in complex physical environments. -->

### Bootstrap Off-Policy Learning with a World Model

**BOOM**, NeurIPS 2025.

BOOM is a world-model-based RL framework that creates a bootstrap loop between a policy and a model-based planner. The policy warm-starts planning, while the planner generates stronger trajectories that improve the policy through likelihood-free alignment. BOOM achieves state-of-the-art performance on the DeepMind Control Suite and HumanoidBench.

## Academic Service

📝 I serve as a reviewer for conferences and journals in AI and robotics, including NeurIPS, ICML, ICLR, CoRL, ICRA, IROS, IEEE TNNLS, IEEE RAL, and IEEE T-ITS.

## Contact

- **Email**: [zgj21@mails.tsinghua.edu.cn](mailto:zgj21@mails.tsinghua.edu.cn)
- **Email**: [zgj21@berkeley.edu](mailto:zgj21@berkeley.edu)
- **Email**: [zishangzhan@gmail.com](mailto:zishangzhan@gmail.com)

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
