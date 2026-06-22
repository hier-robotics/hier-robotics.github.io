---
layout: splash
classes:
  - landing
  - dark-theme
toc: false
title: Research Directions
permalink: /research/
---

<style>

/* GENERAL RESETS & LIGHT THEME */
body {
  background-color: #ffffff !important;
  color: #333333 !important;
}

/* HERO SECTION */
.hero-section {
  position: relative;
  height: 520px;
  overflow: hidden;
  border-radius: 14px;
  margin-top: 20px;
}

.hero-video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: -1;
}

.hero-overlay {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, 0.05); /* 흰색 배경에 맞춰 오버레이 투명도 조절 */
}

/* IMAGE SECTION */
.hero-images {
  display: flex;         /* 가로 배치 */
  gap: 20px;            /* 사진 사이 간격 */
  justify-content: center; /* 중앙 정렬 */
  width: 100%;
  margin: 40px 0;
}

.hero-images img {
  height: 400px;         /* 고정 높이 */
  object-fit: scale-down;     /* 비율 유지하며 Crop */
  flex: 1;               /* 반씩 공간 차지 */
  min-width: 0;          
  border-radius: 12px;
  box-shadow: 0 5px 15px rgba(0,0,0,0.05);
  transition: transform 0.3s ease;
}

.hero-images img:hover {
  transform: scale(1.02);
}

/* 모바일 대응 */
@media (max-width: 768px) {
  .hero-images {
    flex-direction: column;
    gap: 15px;
  }
  .hero-images img {
    height: 300px;
    width: 100%;
  }
}
  
.research-section {
  margin-top: 40px;
}

/* 클래스명 불일치 해결 (.news-box와 혼용되던 부분 통합) */
.research-box {
  background: #f6f8fb;
  padding: 24px;
  border-radius: 12px;
  border: 1px solid #eef2f6;
  margin-top: 20px;
}

.research-box p {
  font-size: 11pt;
  text-align: justify;
  line-height: 1.7;
  color: #333333;
}  

</style>


<!-- HERO IMAGE 구역 -->
<section class="hero-section">
  <img src="/assets/images/Research_intro.jpg" alt="Key Open Problems" class="hero-video">  
  <div class="hero-overlay"></div>
</section>

  
<!-- 연구 내용 소개 구역 -->
<section class="research-section">

  <h2 style="text-align:center; margin-top:40px; color:#003366; font-weight:700;">
    Towards Agile, Safe, Precise, and Adaptive Robots for the Real World
  </h2>

  <div class="research-box">
    <p>
      The <b>Hybrid Intelligent Experimental Robotics (HIER) Lab</b> develops next-generation humanoid robots capable of operating autonomously in complex and dynamic environments. Our research bridges <b>planning</b>, <b>control</b>, <b>learning</b>, and <b>physical interaction</b> to create robots that move beyond simple terrain traversability and achieve true physical intelligence.
    </p>
    <p>
      Recent breakthroughs have enabled humanoid robots to walk, climb stairs, and traverse rough terrain. However, operating in the real world requires substantially more than standard locomotion. To achieve true full autonomy, future humanoids must simultaneously master **Agility, Safety, Precision, and Adaptability**. These requirements introduce deep theoretical and experimental trade-offs that define the core research agenda of the HIER Lab.
    </p>
  </div>
</section>


<section class="research-section">

  <h2 style="text-align:center; margin-top:40px; color:#003366; font-weight:700;">
    Core Research Pillars
  </h2>

  <div class="research-box">
    <p>🚀 <b>Pillar 1: Agile Speed Control & Safety-Critical Dynamics</b>: We develop optimization-based control architectures and dynamic locomotion strategies that allow full-body humanoids to maneuver with human-level agility while providing mathematical safety guarantees. </p>
  </div>

</section>




# 

We systematically address the **6 Key Open Problems** in humanoid robotics by dividing our research into three tightly coupled pillars, blending model-based control theory with modern embodied AI.

---

## 🚀 Pillar 1: Agile Speed Control & Safety-Critical Dynamics
*Addressing Key Problems (1) Agile Speed Control, (3) Safety-Performance Trade-off, and (4) Dynamicity-Precision Trade-off*

We develop optimization-based control architectures and dynamic locomotion strategies that allow full-body humanoids to maneuver with human-level agility while providing mathematical safety guarantees.

* **Agile Motion Generation:** Overcoming the limitations of current methods by enabling rapid acceleration, deceleration, and sharp maneuvering without sacrificing whole-body balance.
* **Safety–Performance Optimization:** Utilizing Control Barrier Functions (CBFs) and Model Predictive Control (MPC) to establish formal safety boundaries, allowing the robot to maximize performance without risking catastrophic system instability.
* **Dynamicity-Precision Balancing:** Developing frameworks that resolve the inherent trade-off between high dynamicity (fast, powerful motions) and high precision (accurate, stable contact execution) during rapid real-world deployment.

---

## 🤝 Pillar 2: Multi-Contact Planning & Environmental Intelligence
*Addressing Key Problems (2) Locomotion in Unknown Environments and (5) Multi-Contact Decision Making*

We empower humanoid robots to intelligently perceive their surroundings and exploit multi-contact interactions with the environment to expand their stability, reachability, and task capabilities.

* **Locomotion in Unmodeled Environments:** Engineering real-time perception and predictive control algorithms that allow legged systems to adjust to moving obstacles, sudden terrain variations, and external disturbances.
* **Multi-Contact Decision Making:** Solving computationally intensive mixed-integer and non-linear optimization problems to enable robots to autonomously determine when, where, and how to sequence contacts using hands, arms, and legs.
* **Whole-Body Loco-Manipulation:** Creating unified frameworks where locomotion and manipulation merge, enabling rich physical interaction with unstructured surroundings.

---

## 🧠 Pillar 3: Lifelong Adaptation & Embodied AI
*Addressing Key Problem (6) Lifelong Adaptation and Generalization*

We investigate data-driven methods and modern robotic learning paradigms to build humanoids capable of continuous improvement throughout their operational lifespan.

* **Sim-to-Real Generalization:** Applying advanced Reinforcement Learning (RL) that remains robust even when deployed well outside the initial offline training distributions.
* **Lifelong Learning with Safety Bounds:** Developing adaptation loops—*Perceive, Adapt, Learn, Deploy*—ensuring the robot continuously learns from new tasks and environments without catastrophic forgetting.
* **Morphology-Aware Intelligence:** Designing algorithms that automatically compensate for physical or morphological changes in the robot hardware during long-term field deployment.

---

# Our Approach

At HIER Lab, we believe that physical intelligence emerges from the integration of four fundamental elements:

<div align="center">

### Planning × Control × Learning × Embodiment

</div>

By bridging optimization-based planning, whole-body control, machine learning, and hardware innovation, we establish the scientific foundations for robots capable of working safely and efficiently alongside humans.

---

# Long-Term Vision

> To create humanoid robots that move dynamically, interact safely, exploit contacts intelligently, and continuously adapt to new environments.
