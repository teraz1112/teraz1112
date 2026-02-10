<h1 align="center">Daigo Terazono</h1>

<p align="center">
Robotics × Computer Vision × Foundation Models  
<br>
Domain Gap Tolerant Visual Servoing / Real Robot Implementation
</p>

---

## About Me

- M.S. Student, Tohoku University, GSIS (Hashimoto Lab)
- Research: **Domain Gap Robust Visual Feedback / Visual Servoing**
- Focus:
  - Zero-shot Visual Servoing
  - Large-parallax pose convergence
  - Foundation model features (DINO / CLIP)
  - Real robot deployment (7DoF arm, Eye-in-hand camera)

I design systems where **deep features are used for correspondence, and control remains geometric**.

---

## Research Interests

- Image-Based Visual Servoing (IBVS)
- Hybrid VS (IBVS × PBVS)
- Domain Gap Robust Perception
- Generative Model Assisted Robotics
- Patch-level Feature Correspondence
- Real-world Deployment without Retraining

---

## Flagship Research Project

### DG-Tolerant Visual Feedback for 6DoF Robotics

Goal:
- Zero-shot control using non-photographic targets  
  (Generated / Stylized / Hand-drawn / Rendered)

Core Idea:
- Deep features → Matching only  
- Control → Classical IBVS geometry

System Stack:
- DINO / CLIP feature extraction
- Patch correspondence search
- Robust filtering (MAD, score ranking)
- SE(3) log error evaluation
- Real robot execution loop

Hardware:
- Torobo Arm Mini (7DoF)
- Basler Eye-in-hand Camera
- ROS + MoveIt + Pylon SDK

---

## Engineering Strength

### Research Pipeline Engineering
- Reproducible experiment environments
- Dataset auto-generation
- Metric automation (IoU / CLIP / DINO / SSIM / HF)
- Large-scale evaluation scripting

### Robotics Implementation
- Real-time visual feedback loop
- Camera-driver level integration
- ROS ↔ Python hybrid pipelines
- Windows ↔ Ubuntu distributed control

### Full Stack Development
- Backend: Python / Django / Node
- Frontend: Vue / React
- Infra: Docker / Linux / GitHub CI

---

## Selected Technical Keywords

Visual Servoing / IBVS / PBVS / HVS  
Foundation Models / DINO / CLIP  
Robot Vision / Correspondence Matching  
Domain Gap / Zero-shot Robotics  
SE(3) Control / Lie Algebra  
ROS / MoveIt / Real Robot Deployment  

---

## Tech Stack

<p align="left">
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" width="40"/>
<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg" width="40"/>
</p>

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=teraz1112)](https://github.com/anuraghazra/github-readme-stats)

---

## Philosophy

I build systems that work **outside the training distribution**.  
Because real-world robotics rarely lives inside datasets.

---

## Contact / Links

- GitHub: https://github.com/teraz1112
- GitHub: https://teraz1112.github.io/webpage/
