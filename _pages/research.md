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

.hero-section {
  position: relative;
  width: 100%;
  max-width: 1050px; /* 너무 커지지 않도록 최대 너비 제한 */
  margin: 20px auto 0 auto;
  overflow: hidden;
  border-radius: 14px;
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
  width: 100% ;  /* 부모 너비에 무조건 맞춤 */
  height: auto ; /* 가로에 맞춰 세로 높이가 자동으로 늘어남 (잘림 방지 핵심) */
  object-fit: fill;     /* 비율 유지하며 fill */
  position: relative;      /* absolute로 붕 떠있던 기본 설정을 해제 */
  top: auto;
  left: auto;
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
      Recent breakthroughs have enabled humanoid robots to walk, climb stairs, and traverse rough terrain. However, operating in the real world requires substantially more than standard locomotion. To achieve true full autonomy, future humanoids must simultaneously master <b>Agility, Safety</b>, <b>Precision</b>, and <b>Adaptability</b>. These requirements introduce deep theoretical and experimental trade-offs that define the core research agenda of the HIER Lab.
    </p>
  </div>
</section>


<section class="research-section">

  <h2 style="text-align:center; margin-top:40px; color:#003366; font-weight:700;">
    Core Research Pillars
  </h2>

  <div class="research-box">
    <p>🚀 <b>Pillar 1: Agile Speed Control & Safety-Critical Dynamics</b>: We develop optimization-based control architectures and dynamic locomotion strategies that allow full-body humanoids to maneuver with human-level agility while providing mathematical safety guarantees. </p>
    <p> - <b>Agile Motion Generation</b>: Overcoming the limitations of current methods by enabling rapid acceleration, deceleration, and sharp maneuvering without sacrificing whole-body balance.</p>
    <p> - <b>Safety–Performance Optimization</b>: Utilizing Control Barrier Functions (CBFs) and Model Predictive Control (MPC) to establish formal safety boundaries, allowing the robot to maximize performance without risking catastrophic system instability.</p>
    <p> - <b>Dynamicity-Precision Balancing</b>: Developing frameworks that resolve the inherent trade-off between high dynamicity (fast, powerful motions) and high precision (accurate, stable contact execution) during rapid real-world deployment.</p>
  </div>

  <div class="research-box">
    <p>🤝 <b>Pillar 2: Multi-Contact Planning & Environmental Intelligence</b>:  We empower humanoid robots to intelligently perceive their surroundings and exploit multi-contact interactions with the environment to expand their stability, reachability, and task capabilities.</p>
    <p> - <b>Locomotion in Unmodeled Environments</b>: Engineering real-time perception and predictive control algorithms that allow legged systems to adjust to moving obstacles, sudden terrain variations, and external disturbances.</p>
    <p> - <b>Multi-Contact Decision Making</b>: Solving computationally intensive mixed-integer and non-linear optimization problems to enable robots to autonomously determine when, where, and how to sequence contacts using hands, arms, and legs.</p>
    <p> - <b>Whole-Body Loco-Manipulation</b>: Creating unified frameworks where locomotion and manipulation merge, enabling rich physical interaction with unstructured surroundings.</p>
  </div>


  <div class="research-box">
    <p>🧠 <b>Pillar 3: Lifelong Adaptation & Embodied AI</b>:  We investigate data-driven methods and modern robotic learning paradigms to build humanoids capable of continuous improvement throughout their operational lifespan.</p>
    <p> - <b>Sim-to-Real Generalization</b>: Applying advanced Reinforcement Learning (RL) that remains robust even when deployed well outside the initial offline training distributions.</p>
    <p> - <b>Lifelong Learning with Safety Bounds</b>: Developing adaptation loops—Perceive, Adapt, Learn, Deploy—ensuring the robot continuously learns from new tasks and environments without catastrophic forgetting.</p>
    <p> - <b>Morphology-Aware Intelligence</b>: Designing algorithms that automatically compensate for physical or morphological changes in the robot hardware during long-term field deployment.</p>
  </div>
  
</section>



