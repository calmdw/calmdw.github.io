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

Currently, I'm exploring the best way to combine robotic control and learning-based methods to achieve 0.2mm tolerance peg-in-hole assembly while keeping strong pose generalization ability.

Feel free to reach out for a small chat on:
- Reinforcement Learning
- Imitation Learning
- Sim2Real

### New Achievement on 5.8mm/6mm assembly with admittance controller, soft contact!

<div style="text-align: center; margin-top: 1.5em;">
  <iframe width="560" height="315" src="https://github.com/user-attachments/assets/6c1a233e-7bcc-4311-84d8-82cfcd288531" 
    title="GenPiH Video Demo" frameborder="0" allowfullscreen></iframe>
</div>


## Publications

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
    <p>accepted</p>

    <p>
      <strong>GenPiH</strong> is a reinforcement learning-based general policy for peg-in-hole assembly with 6-DOF generalization. Trained using PPO and domain randomization in Isaac Lab, GenPiH achieves nearly 100% success across 8000+ random hole poses in simulation. The trajectory replayed directly on a UR10e robot <em>without any task-specific tuning</em>.
    </p>

    <p>
      💻 <a href="https://github.com/calmdw/genpih" target="_blank">Code</a> &nbsp;|&nbsp;
    </p>
  </div>

</div>

<hr style="height: 2px; background-color: #e0e0e0; border: none; margin: 2.5em 0;">

### *Reinforcement Learning-Based Sequential Control Policy for Multiple Peg-in-Hole Assembly*

<div style="display: flex; flex-wrap: wrap; gap: 1.2em; margin: 2em 0; align-items: center;">

  <img src="https://github.com/user-attachments/assets/d128fd65-153d-4593-ac69-0566b851627b"
       alt="SeqPolicy" 
       style="flex: 0 0 88%; max-width: 88%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">

  <!-- Text Content -->
  <div style="flex: 1; min-width: 250px;">
    <p><strong>Xinyu Liu</strong>, Chao Zeng, Chenguang Yang, Jianwei Zhang</p>
    <p><em>Denmark Technical University, University of Liverpool, University of Hamburg</em></p>
    <p><strong>CAAI Artificial Intelligence Research, 2024</strong></p>

    <p> It is hard to have a super-hero model to deal with long-term/complex automation tasks, so let's build one expert team!</p>
    <p>
    <strong>SeqPolicy</strong> proposes a modular control workflow using reinforcement learning to solve multiple peg-in-hole assembly task. The approach breaks down the task into three primitive skills: pick, align, and insert—each trained individually, enabling efficient training and reusable deployment.</p>

    <p>
      📄 <a href="https://www.sciopen.com/article/10.26599/AIR.2024.9150043" target="_blank">Paper</a> &nbsp;|&nbsp;
      💻 <a href="https://github.com/calmdw/SeqPolicy" target="_blank">Code</a> &nbsp;|&nbsp;
    </p>
  </div>
</div>

<hr style="height: 2px; background-color: #e0e0e0; border: none; margin: 2.5em 0;">

### *Self-supervised Fusion of IR and RGB Images for Illumination-Robust Visual Teach and Repeat Navigation*

<div style="display: flex; flex-wrap: wrap; gap: 1.2em; margin: 2em 0; align-items: center;">

  <!-- Teaser Image: Matches 38% width ratio -->
  <img src="https://github.com/user-attachments/assets/23832614-3adf-4583-91b7-2829a2c82a26" 
       alt="IR-RGB Fusion Teaser" 
       style="flex: 0 0 88%; max-width: 88%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">

  <!-- Text Content -->
  <div style="flex: 1; min-width: 250px;">
    <p><strong>Xinyu Liu</strong>*, Zdenek Rozsypalek*, Tomas Krajnik</p>
    <p><em>Technical University of Denmark, Czech Technical University in Prague</em></p>
    <p><strong>European Conference on Mobile Robots (ECMR), 2023</strong> — <em>Oral Presentation</em></p>

    <p>one robot is running at one night, how to make it recognize the same place it passed in daylight</p>
    <p>
    Presents a self-supervised framework for fusing infrared and RGB images in VT&R navigation systems to enable robot to localize under extreme changing illumination conditions. Our method achieves <strong>5% error</strong> for localization under dark night and sun glare conditions.
    </p>

    <p>
      📄 <a href="https://ieeexplore.ieee.org/abstract/document/10256333" target="_blank">Paper</a> &nbsp;|&nbsp;
    </p>
  </div>
</div>

---

### *Deep Learning assists detection of mussel reefs in Roskilde Fjord*

<div style="display: flex; flex-wrap: wrap; gap: 1.2em; margin: 2em 0; align-items: center;">

  <!-- Teaser Image: Matches 88% width ratio -->
  <img src="https://raw.githubusercontent.com/calmdw/Detecting-Potential-Mussel-Reef-in-ROV-Videos-Using-Deep-Learning/main/example.gif" 
       alt="mussel reef" 
       style="flex: 0 0 88%; max-width: 88%; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">

  <!-- Text Content -->
  <div style="flex: 1; min-width: 250px;">
    <p>
     We propose a method based on the YOLO algorithm to detect mussels in videos, estimate their coverage, and identify potential mussel reefs. We also built a dataset of 1000 labeled mussel images to support future marine research.
    </p>

    <p>
      📄 <a href="https://backend.orbit.dtu.dk/ws/portalfiles/portal/336098585/Liu_et_al._2023_Roskilde_Fjord_og_muslinge-rev_removed.pdf" target="_blank">Paper</a> &nbsp;|&nbsp;
      💻 <a href="https://github.com/calmdw/Detecting-Potential-Mussel-Reef-in-ROV-Videos-Using-Deep-Learning/tree/main" target="_blank">Code</a>
    </p>
  </div>
</div>

<a href="https://info.flagcounter.com/3VQ2"><img src="https://s01.flagcounter.com/count2/3VQ2/bg_FFFFFF/txt_000000/border_CCCCCC/columns_2/maxflags_10/viewers_0/labels_0/pageviews_0/flags_0/percent_0/" alt="Flag Counter" border="0"></a>

<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=jdKmcJP6gV_COpF3-5Nvpsc_buHuDv7RVqg0F7XfzvI&cl=ffffff&w=a"></script>

