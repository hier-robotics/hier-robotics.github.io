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

/* ===============================
   HIER LAB RESEARCH PAGE
================================ */

.research-page {
  width: 100%;
  max-width: 1400px;
  margin: 0 auto;
  padding: 40px 30px 80px;
  box-sizing: border-box;
  color: #222;
}

/* Research Introduction */

.research-intro {
  text-align: center;
  max-width: 1100px;
  margin: 0 auto 75px;
}

.research-eyebrow {
  color: #cc0000;
  font-size: 13px;
  font-weight: 700;
  letter-spacing: 2px;
  margin-bottom: 20px;
}

.research-intro h1 {
  font-size: clamp(30px, 3.5vw, 52px);
  line-height: 1.2;
  font-weight: 750;
  margin-bottom: 35px;
  color: #111;
}

.research-intro h1 span {
  color: #cc0000;
}

.research-intro p {
  font-size: 17px;
  line-height: 1.85;
  text-align: justify;
  margin-bottom: 22px;
}

/* Research Directions Heading */

.research-heading {
  text-align: center;
  margin: 70px 0 50px;
}

.research-heading h2 {
  font-size: 36px;
  color: #111;
  margin-bottom: 15px;
}

.research-heading::after {
  content: "";
  display: block;
  width: 65px;
  height: 4px;
  background: #cc0000;
  margin: 20px auto 0;
}

/* Research Item */

.research-item {
  display: grid;
  grid-template-columns: 1fr 1.15fr;
  align-items: center;
  gap: 55px;
  margin: 0 0 90px;
}

/* Alternating layout */

.research-item.reverse {
  grid-template-columns: 1.15fr 1fr;
}

.research-item.reverse .research-image {
  order: 2;
}

.research-item.reverse .research-description {
  order: 1;
}

/* Research Image */

.research-image {
  width: 100%;
}

.research-image img {
  display: block;
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  border-radius: 10px;
}

/* Placeholder for missing images */

.research-image-placeholder {
  width: 100%;
  aspect-ratio: 4 / 3;
  border-radius: 10px;
  background: #f0f0f0;
  border: 1px solid #ddd;

  display: flex;
  justify-content: center;
  align-items: center;

  color: #888;
  font-size: 15px;
  text-align: center;
  padding: 20px;
}

/* Description */

.research-number {
  color: #cc0000;
  font-size: 15px;
  font-weight: 700;
  letter-spacing: 2px;
  margin-bottom: 14px;
}

.research-description h3 {
  font-size: 28px;
  line-height: 1.3;
  color: #111;
  margin: 0 0 24px;
}

.research-description p {
  font-size: 16px;
  line-height: 1.85;
  color: #444;
  text-align: justify;
}

/* Research Tags */

.research-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 25px;
}

.research-tags span {
  background: #f5f5f5;
  border: 1px solid #e0e0e0;
  border-radius: 5px;
  padding: 7px 12px;
  font-size: 12px;
  color: #555;
}

/* Divider */

.research-divider {
  width: 100%;
  height: 1px;
  background: #e5e5e5;
  margin: 0 0 90px;
}

/* ===============================
   RESPONSIVE
================================ */

@media (max-width: 900px) {

  .research-page {
    padding: 30px 20px 60px;
  }

  .research-item,
  .research-item.reverse {
    grid-template-columns: 1fr;
    gap: 25px;
    margin-bottom: 55px;
  }

  .research-item.reverse .research-image,
  .research-item.reverse .research-description {
    order: initial;
  }

  .research-intro {
    margin-bottom: 55px;
  }

  .research-intro h1 {
    font-size: 32px;
  }

  .research-intro p {
    font-size: 15px;
  }

  .research-heading h2 {
    font-size: 28px;
  }

  .research-description h3 {
    font-size: 23px;
  }

  .research-description p {
    font-size: 15px;
  }

  .research-divider {
    margin-bottom: 55px;
  }
}

</style>


<div class="research-page">

  <!-- =============================
       RESEARCH VISION
  ============================== -->

  <section class="research-intro">

    <div class="research-eyebrow">
      HIER LAB · RESEARCH VISION
    </div>

    <h1>
      Towards
      <span>Intelligent, Agile, Safe,
      Precise, and Adaptive</span>
      Robots for the Real World
    </h1>

    <p>
      The <strong>Hybrid Intelligent Experimental
      Robotics (HIER) Lab</strong> develops next-generation
      humanoid and animaloid robots capable of operating
      autonomously in complex, dynamic, and unstructured
      environments. Our research integrates
      <strong>planning, control, learning, and physical
      interaction</strong> to advance robotic capabilities
      beyond conventional locomotion toward intelligent,
      autonomous loco-manipulation in the real world.
    </p>

    <p>
      Recent advances in robotics have enabled humanoid
      and legged robots to walk, climb stairs, and navigate
      challenging terrain. However, achieving reliable
      autonomy in real-world environments requires
      substantially more than locomotion alone.
      Future robots must simultaneously demonstrate
      <strong>intelligence, agility, safety, precision,
      and adaptability</strong> while physically interacting
      with their surroundings, manipulating objects,
      and responding to unpredictable conditions.
    </p>

    <p>
      These capabilities introduce fundamental challenges
      and trade-offs in robot design, motion planning,
      control, and learning. The HIER Lab addresses
      these challenges through an integrated research
      approach that combines
      <strong>theoretical foundations, computational
      algorithms, and experimental validation on
      real robotic platforms.</strong>
    </p>

  </section>


  <!-- =============================
       RESEARCH DIRECTIONS
  ============================== -->

  <div class="research-heading">
    <h2>Research Directions</h2>
  </div>


  <!-- RESEARCH 01 -->

  <section id="locomanipulation" class="research-item">

    <div class="research-image">
    <img src="/assets/images/Peginhole.jpg" alt="peginhole">
    </div>

    <div class="research-description">

      <div class="research-number">RESEARCH 01</div>

      <h3>
        Intelligent and Autonomous
        Humanoid Loco-Manipulation
      </h3>

      <p>
        We develop autonomous loco-manipulation
        capabilities that enable humanoid and animaloid
        robots to coordinate locomotion, manipulation,
        and environmental interactions in complex
        environments. Our research explores contact-rich
        motion planning, multi-contact behaviors,
        adaptive locomotion, and the integration
        of whole-body movements with task-oriented
        manipulation.
      </p>

      <div class="research-tags">
        <span>Humanoid Robotics</span>
        <span>Loco-Manipulation</span>
        <span>Multi-Contact Planning</span>
        <span>Autonomous Robotics</span>
      </div>

    </div>

  </section>

  <div class="research-divider"></div>


  <!-- RESEARCH 02 -->

  <section id="learning" class="research-item reverse">

    <div class="research-image">
    <img src="/assets/images/box_carry.jpg" alt="boxcarry">
    </div>

    <div class="research-description">

      <div class="research-number">RESEARCH 02</div>

      <h3>
        Learning-Enabled Whole-Body
        Planning and Control
      </h3>

      <p>
        We investigate hierarchical planning and
        whole-body control frameworks that integrate
        model-based optimization with learning-based
        approaches. By combining reinforcement learning,
        adaptive control, and whole-body optimization,
        we aim to achieve coordinated, agile, and robust
        robotic behaviors while accounting for physical
        constraints and dynamic interactions.
      </p>

      <div class="research-tags">
        <span>Whole-Body Control</span>
        <span>Reinforcement Learning</span>
        <span>Hierarchical Control</span>
        <span>Robot Learning</span>
      </div>

    </div>

  </section>

  <div class="research-divider"></div>


  <!-- RESEARCH 03 -->

  <section id="heterogeneous" class="research-item">

    <div class="research-image">
    <img src="/assets/images/Human-robot-collaboration.jpeg" alt="Robot Team">
    </div>

    <div class="research-description">

      <div class="research-number">RESEARCH 03</div>

      <h3>
        Heterogeneous Robot Teams with
        Physical and Contextual Interactions
      </h3>

      <p>
        We study collaborative robotic systems
        composed of heterogeneous platforms,
        including humanoids, quadrupeds, and robotic
        manipulators. Our research focuses on
        coordinated behaviors, physical interaction,
        and context-aware decision-making to enable
        robots with complementary capabilities to
        accomplish complex tasks collaboratively.
      </p>

      <div class="research-tags">
        <span>Multi-Robot Systems</span>
        <span>Robot Collaboration</span>
        <span>Physical Interaction</span>
        <span>Context-Aware Planning</span>
      </div>

    </div>

  </section>

  <div class="research-divider"></div>


  <!-- RESEARCH 04 -->

  <section id="control" class="research-item reverse">

    <div class="research-image">
    <img src="/assets/images/safety_locomotion.jpg" alt="Safety locomotion">
    </div>

    <div class="research-description">

      <div class="research-number">RESEARCH 04</div>

      <h3>
        Optimal, Safety-Critical,
        and Stochastic Control
      </h3>

      <p>
        We develop theoretical and computational
        methods for controlling nonlinear, constrained,
        and uncertain robotic systems. Our research
        includes nonlinear optimal control,
        safety-critical control, stochastic control,
        and scalable optimization, with an emphasis
        on reliable decision-making and control
        under dynamic uncertainty and physical
        constraints.
      </p>

      <div class="research-tags">
        <span>Optimal Control</span>
        <span>Safety-Critical Control</span>
        <span>Stochastic Control</span>
        <span>Nonlinear Systems</span>
      </div>

    </div>

  </section>

  <div class="research-divider"></div>


  <!-- RESEARCH 05 -->

  <section id="hardware" class="research-item">

    <div class="research-image">
      <div class="research-image-placeholder">
        Robotic Hardware and Mechanism Image
      </div>
    </div>

    <div class="research-description">

      <div class="research-number">RESEARCH 05</div>

      <h3>
        Robotic Hardware and
        Mechanism Innovation
      </h3>

      <p>
        We design and develop innovative robotic
        mechanisms and integrated experimental
        platforms to overcome limitations of
        conventional robot morphologies. Our research
        investigates novel locomotion and manipulation
        mechanisms, morphology-aware design, custom
        robotic hardware, and integrated actuation
        and sensing systems that expand robotic
        capabilities in challenging real-world
        environments.
      </p>

      <div class="research-tags">
        <span>Robot Mechanisms</span>
        <span>Hardware Design</span>
        <span>Morphology Optimization</span>
        <span>Experimental Robotics</span>
      </div>

    </div>

  </section>

</div>
