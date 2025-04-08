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

### Research Interests

My work focuses on **robot learning** and **robotic manipulation**, recently using reinforcement learning (RL) to achieve **generalizable** and **high-precision robotic assembly** with **Isaac Lab(Isaac Sim)**—my favorite framework and simulator at the moment.

Currently, I'm exploring the best way to combine classical robotic control and learning-based methods to achieve 0.2mm precision peg-in-hole assembly while keeping strong pose generalization ability.

Feel free to reach out for a small chat on:
- Reinforcement Learning
- Imitation Learning
- Sim2Real

---

## Publications:

---

### *A General Peg-in-Hole Assembly Policy Based on Domain Randomized Reinforcement Learning*

<div style="display: flex; flex-wrap: wrap; gap: 1.2em; margin: 2em 0; align-items: center;">

  <!-- Teaser Image: ~38% width to match golden ratio -->
  <img src="https://github.com/user-attachments/assets/1cac5868-0c91-4885-b4bd-e72ddb1efa42" 
       alt="GenPiH Teaser" 
       style="flex: 0 0 38%; max-width: 38%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <img src="https://github.com/user-attachments/assets/1ba56528-c9b1-49d8-b478-9257c4e5b645" 
       alt="GenPiH Teaser" 
       style="flex: 0 0 38%; max-width: 38%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">

  <!-- Text Content: ~62% width -->
  <div style="flex: 1; min-width: 250px;">
    <p><strong>Xinyu Liu</strong>, Aljaž Kramberger, Leon Bodenhagen</p>
    <p><em>The Maersk Mc-Kinney Moller Institute, University of Southern Denmark</em></p>
    <p><strong>34th International Conference on Robotics in Alpe-Adria-Danube Region (RAAD 2025)</strong> — <em>Oral Presentation</em></p>

    <p>
      <strong>GenPiH</strong> is a reinforcement learning-based general policy for peg-in-hole assembly with 6-DOF generalization. Trained using PPO and domain randomization in Isaac Lab, GenPiH achieves nearly 100% success across 8000+ random hole poses. The trajectory replayed directly on a UR10e robot <em>without any task-specific tuning</em>.
    </p>

    <p>
      📄 <a href="https://arxiv.org/abs/2504.04148" target="_blank">Paper</a> &nbsp;|&nbsp;
      💻 <a href="https://github.com/calmdw/genpih" target="_blank">Code</a> &nbsp;|&nbsp;
    </p>
  </div>

</div>

---

### *Reinforcement Learning-Based Sequential Control Policy for Multiple Peg-in-Hole Assembly*

<div style="display: flex; flex-wrap: wrap; gap: 1.2em; margin: 2em 0; align-items: center;">

  <!-- Two Teaser Videos - 38% width each -->

<img src="https://github.com/user-attachments/assets/d128fd65-153d-4593-ac69-0566b851627b" width="80%" alt="Generalization Test">
       alt="SeqPolicy" 
       style="flex: 0 0 88%; max-width: 38%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">

  <!-- Text Content -->
  <div style="flex: 1; min-width: 250px;">
    <p><strong>Xinyu Liu</strong>, Chao Zeng, Chenguang Yang, Jianwei Zhang</p>
    <p><em>Denmark Technical University, University of Liverpool, University of Hamburg</em></p>
    <p><strong>CAAI Artificial Intelligence Research, 2024</strong></p>

    <p><strong>SeqPolicy</strong> proposes a modular control workflow using reinforcement learning to solve multiple peg-in-hole assembly task. The approach breaks down the task into three primitive skills: pick, align, and insert—each trained individually, enabling efficient training and reusable deployment.</p>

    <p>
      📄 <a href="https://www.sciopen.com/article/10.26599/AIR.2024.9150043" target="_blank">Paper</a> &nbsp;|&nbsp;
      💻 <a href="https://github.com/calmdw/SeqPolicy" target="_blank">Code</a> &nbsp;|&nbsp;
    </p>
  </div>
</div>

---

### *Self-supervised Fusion of IR and RGB Images for Illumination-Robust Visual Teach and Repeat Navigation*

<div style="display: flex; flex-wrap: wrap; gap: 1.2em; margin: 2em 0; align-items: center;">

  <!-- Teaser Image: Matches 38% width ratio -->
  <img src="https://github.com/user-attachments/assets/23832614-3adf-4583-91b7-2829a2c82a26" 
       alt="IR-RGB Fusion Teaser" 
       style="flex: 0 0 88%; max-width: 38%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">

  <!-- Text Content -->
  <div style="flex: 1; min-width: 250px;">
    <p><strong>Xinyu Liu</strong>*, Zdenek Rozsypalek*, Tomas Krajnik</p>
    <p><em>Technical University of Denmark, Czech Technical University in Prague</em></p>
    <p><strong>European Conference on Mobile Robots (ECMR), 2023</strong></strong> — <em>Oral Presentation</em></p>
    
    <p>Presents a self-supervised framework for fusing infrared and RGB images in VT&R navigation systems to enable robot localize under extreme chaning illumination conditions. Our method achieves <strong>5% error</strong> for localization under dark night and sun glare conditions.
    </p>

    <p>
      Key innovations:<br>
      • Contrastive learning pipeline bridging RGB/IR domains<br>
      • Three decision-level fusion strategies<br>
      • Validation on real-world parking lot dataset<br>
    </p>

    <p>
      📄 <a href="https://ieeexplore.ieee.org/document/10163408" target="_blank">Paper</a> &nbsp;|&nbsp;
      🎥 <a href="#vtr-demo" target="_blank">Navigation Demo</a> &nbsp;|&nbsp;
    </p>
  </div>
</div>

---

