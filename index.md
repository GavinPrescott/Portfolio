---
layout: default
title: Home
---

<section id="hero" class="hero">
  <div class="container">
    <h1>Gavin Prescott,<br><em>Robotics Engineer</em></h1>
    <p class="tagline">Building machines that think, move, and adapt — from autonomous platforms to embedded control systems.</p>
    <div class="cta-row">
      <a href="#projects" class="btn btn-primary">View Work</a>
      <a href="{{ '/assets/resume.pdf' | relative_url }}" class="btn btn-ghost">Download Resume</a>
    </div>
  </div>
</section>

<section id="about">
  <div class="container">
    <p class="section-label">About</p>
    <div class="about-grid">
      <img class="about-photo" src="{{ '/assets/img/headshot.jpg' | relative_url }}" alt="Gavin Prescott">
      <div markdown="1">
## Mechatronics at heart.

I'm a first-year MS student in **Robotics and Autonomous Systems** at Boston University, expected to graduate in **2028**. My coursework leans heavily into engineering: designing, building, and iterating on physical systems.

My path here started somewhere unexpected. I came to engineering from **anthropology** — I've always been fascinated by how people think, interact, and shape the world around them. But after graduation I realized I wanted to do more than study human societies; I wanted to build, design, and solve the problems that affect them. Engineering offered too many compelling directions to pick just one, and **robotics became the natural meeting point** — mechanics, electronics, software, and design all converging on systems that act in the physical world. **Mechatronics is where I feel most at home.**

That anthropological lens still shapes what I'm drawn to today, particularly **human-robot interaction (HRI)** — but from a less conventional angle. I'm less interested in **humanoid robots**, which tend to duplicate what humans already do well, and more interested in robots designed to fill the spaces where the human body falters: extreme scales, unfamiliar environments, sensing modalities we don't have, geometries we can't replicate. Studying how humans interact with their world made it natural to ask the inverse — how should *robots* interact with that world, not by imitating us, but by extending what we can reach, sense, and build?

Outside of classes, I'm a **lab technician at RASTIC** (BU's robotics & autonomous systems center) and **Vice President of the BU Robotics Club**. I'm actively looking for **internships and co-ops** where I can build real systems, learn from experienced engineers, and contribute to meaningful problems.

When I'm not in the lab, you'll usually find me reading, working out, exploring Boston for the older architecture, or printing yet another gadget to make the 3D printer purchase feel worth it.
      </div>
    </div>
  </div>
</section>

<section id="projects">
  <div class="container">
    <p class="section-label">Selected Work</p>
    <h2>Projects</h2>
    <div class="projects-grid">

      <article class="project-card">
        <p class="project-meta">01 · Autonomous Systems</p>
        <h3>Autonomous Mobile Robot</h3>
        <p>Differential-drive platform with LiDAR-based SLAM and ROS 2 navigation stack. Built from the ground up — chassis, motor control, sensor fusion, and path planning.</p>
        <div class="tags">
          <span class="tag">ROS 2</span>
          <span class="tag">SLAM</span>
          <span class="tag">C++</span>
          <span class="tag">Python</span>
        </div>
        <a href="#" class="project-link">View Project</a>
      </article>

      <article class="project-card">
        <p class="project-meta">02 · Manipulation</p>
        <h3>6-DOF Robotic Arm</h3>
        <p>Pick-and-place arm with inverse kinematics solver and computer-vision-guided object detection. Designed in SolidWorks, 3D-printed, driven by stepper motors and a Raspberry Pi.</p>
        <div class="tags">
          <span class="tag">SolidWorks</span>
          <span class="tag">OpenCV</span>
          <span class="tag">Inverse Kinematics</span>
          <span class="tag">Raspberry Pi</span>
        </div>
        <a href="#" class="project-link">View Project</a>
      </article>

      <article class="project-card">
        <p class="project-meta">03 · Embedded Control</p>
        <h3>Quadcopter Flight Controller</h3>
        <p>Custom flight-control firmware on an STM32 with IMU sensor fusion (complementary + Kalman filter) and PID stabilization. Bench-tested attitude control before integration.</p>
        <div class="tags">
          <span class="tag">STM32</span>
          <span class="tag">PID Control</span>
          <span class="tag">Embedded C</span>
          <span class="tag">Sensor Fusion</span>
        </div>
        <a href="#" class="project-link">View Project</a>
      </article>

      <article class="project-card">
        <p class="project-meta">04 · Mechatronics</p>
        <h3>Project Four — Placeholder</h3>
        <p>Brief description of a fourth project. Could be a competition robot, a sensor system, a teleoperated platform, or a research-lab contribution. Swap this card for your real work.</p>
        <div class="tags">
          <span class="tag">Tag</span>
          <span class="tag">Tag</span>
          <span class="tag">Tag</span>
        </div>
        <a href="#" class="project-link">View Project</a>
      </article>

    </div>
  </div>
</section>

<section id="experience">
  <div class="container">
    <p class="section-label">Applied Tools</p>
    <h2>Specialized Experience</h2>
    <div class="experience-list">

      <article class="experience-item">
        <h3>GIS &amp; Cartographic Research</h3>
        <p class="experience-meta">Undergraduate Research · Dr. Shinu Anna Abraham</p>
        <p>Contributed five supplemental cartographic figures to peer-reviewed archaeological research on long-distance trade across the ancient Indian Ocean. Each map was designed to be accessible to both domain experts and general readers — work that required learning QGIS from a limited starting base, organizing large geospatial datasets, and iterating through faculty review.</p>
        <div class="tags">
          <span class="tag">QGIS</span>
          <span class="tag">Cartography</span>
          <span class="tag">Geospatial Datasets</span>
          <span class="tag">Information Design</span>
        </div>
        <p class="pub-note">Abraham, S.A. (2023). <a href="https://doi.org/10.1146/annurev-anthro-101819-110124">"Recent Developments in the Archaeology of Long-Distance Connections Across the Ancient Indian Ocean."</a> <em>Annual Review of Anthropology</em>, 52, 115–135.</p>
        <a href="https://www.annualreviews.org/content/journals/10.1146/annurev-anthro-101819-110124#supplementary_data" class="project-link" target="_blank" rel="noopener">View all five maps</a>
      </article>

      <article class="experience-item">
        <h3>CAD &amp; Mechanical Design</h3>
        <p class="experience-meta">[Context — e.g. Warbird Factory internship, EV station R&amp;D, coursework]</p>
        <p>[Placeholder card for your CAD experience. The Warbird Factory restoration work and EV charging station R&amp;D from your SOP would both fit here well — the EV station numbers in particular (40% cost reduction, 40% production time reduction, 60% field assembly improvement) are portfolio gold. Replace this paragraph with whatever framing you want when you're ready.]</p>
        <div class="tags">
          <span class="tag">SolidWorks</span>
          <span class="tag">AutoCAD</span>
          <span class="tag">Mechanical Design</span>
          <span class="tag">DFM</span>
        </div>
      </article>

    </div>
  </div>
</section>

<section id="skills">
  <div class="container">
    <p class="section-label">Capabilities</p>
    <h2>Skills</h2>
    <div class="skills-grid">

      <div class="skill-cat">
        <h3>Programming</h3>
        <div class="skill-list">
          <span class="tag">Python</span>
          <span class="tag">C++</span>
          <span class="tag">C</span>
          <span class="tag">MATLAB</span>
          <span class="tag">Bash</span>
        </div>
      </div>

      <div class="skill-cat">
        <h3>Robotics & Control</h3>
        <div class="skill-list">
          <span class="tag">ROS 2</span>
          <span class="tag">SLAM</span>
          <span class="tag">PID</span>
          <span class="tag">Kalman Filtering</span>
          <span class="tag">OpenCV</span>
        </div>
      </div>

      <div class="skill-cat">
        <h3>Embedded Systems</h3>
        <div class="skill-list">
          <span class="tag">Arduino</span>
          <span class="tag">STM32</span>
          <span class="tag">Raspberry Pi</span>
          <span class="tag">I²C / SPI / UART</span>
          <span class="tag">PCB Design</span>
        </div>
      </div>

      <div class="skill-cat">
        <h3>Design & Manufacturing</h3>
        <div class="skill-list">
          <span class="tag">SolidWorks</span>
          <span class="tag">Fusion 360</span>
          <span class="tag">3D Printing</span>
          <span class="tag">CNC Machining</span>
          <span class="tag">Laser Cutting</span>
        </div>
      </div>

    </div>
  </div>
</section>

<section id="contact" class="contact">
  <div class="container">
    <p class="section-label">Get in touch</p>
    <h2>Let's build something real.</h2>
    <p class="lede">I'm open to internships, research positions, and collaborations in robotics, mechatronics, and embedded systems.</p>
    <div class="contact-links">
      <a href="mailto:{{ site.email }}" class="btn btn-primary">Email me</a>
      <a href="{{ site.github_url }}" class="btn btn-ghost">GitHub</a>
      <a href="{{ '/assets/resume.pdf' | relative_url }}" class="btn btn-ghost">Resume</a>
    </div>
  </div>
</section>
