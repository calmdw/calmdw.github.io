---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hej! 👋 I'm a Research Assistant at the [Maersk Mc-Kinney Moller Institute](https://www.sdu.dk/en/om-sdu/institutter-centre/mmmi_maersk_mckinney_moeller), University of Southern Denmark.  

Previously, I held research internships at the [AI Center, CVUT](https://www.aic.fel.cvut.cz/), [TAMS Group, Universität Hamburg](https://tams.informatik.uni-hamburg.de/), and DTU Aqua. I hold a Master's degree in Autonomous Systems from [Technical University of Denmark](https://www.dtu.dk/english/).

---

### 🧠 Research Interests

My work focuses on **robot learning** and **robotic manipulation**, recently using reinforcement learning (RL) to achieve **generalizable** and **high-precision robotic assembly** with **Isaac Lab(Isaac Sim)**—my favorite framework and simulator at the moment.

Currently, I'm exploring the best way to combine classical robotic control methods and learning-based methods to achieve 0.2mm precision peg-in-hole assembly while keeping strong pose generalization ability.

Feel free to reach out for a small chat on:
- Reinforcement Learning
- Imitation Learning
- Sim2Real Robotics

---

## 🚀 Research:

### *A General Peg-in-Hole Assembly Policy Based on Domain Randomized Reinforcement Learning*

<div style="display: flex; flex-wrap: wrap; gap: 1.2em; margin: 2em 0; align-items: center;">

  <!-- Teaser Image: ~38% width to match golden ratio -->
  <img src="https://github.com/user-attachments/assets/1ba56528-c9b1-49d8-b478-9257c4e5b645" 
       alt="GenPiH Teaser" 
       style="flex: 0 0 38%; max-width: 38%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">

  <!-- Text Content: ~62% width -->
  <div style="flex: 1; min-width: 250px;">
    <p><strong>Xinyu Liu</strong>, Aljaž Kramberger, Leon Bodenhagen</p>
    <p><em>The Maersk Mc-Kinney Moller Institute, University of Southern Denmark</em></p>
    <p><strong>34th International Conference on Robotics in Alpe-Adria-Danube Region (RAAD 2025)</strong> — <em>Oral Presentation</em></p>

    <p>
      <strong>GenPiH</strong> is a reinforcement learning-based general policy for peg-in-hole assembly with 6-DOF generalization. Trained using PPO and domain randomization in Isaac Sim, GenPiH achieves nearly 100% success across 8000+ unseen hole poses. It transfers directly to a UR10e robot <em>without any task-specific tuning</em>.
    </p>

    <p>
      🔗 <a href="https://your-paper-link.com" target="_blank">Paper</a> &nbsp;|&nbsp;
      💻 <a href="https://github.com/calmdw/genpih" target="_blank">Code</a> &nbsp;|&nbsp;
      🌐 <a href="https://calmdw.github.io/genpih" target="_blank">Project Website</a>
    </p>
  </div>

</div>
