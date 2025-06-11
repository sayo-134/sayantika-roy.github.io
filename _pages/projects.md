---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

<style>
:root {
  --tile-text-light: #000000;
  --tile-text-dark: #ffffff;
  --tile-subtext-light: #666666;
  --tile-subtext-dark: #cccccc;
  --tile-border-light: rgba(0, 0, 0, 0.1);
  --tile-border-dark: rgba(255, 255, 255, 0.1);
  --tile-shadow-light: rgba(0, 0, 0, 0.08);
  --tile-shadow-dark: rgba(255, 255, 255, 0.05);
}

@media (prefers-color-scheme: dark) {
  .project-tile {
    background-color: transparent;
    color: var(--tile-text-dark);
    border: 1px solid var(--tile-border-dark);
    box-shadow: 0 2px 8px var(--tile-shadow-dark);
  }
  .project-meta {
    color: var(--tile-subtext-dark);
  }
  .project-image {
    border: 1px solid var(--tile-border-dark);
  }
} 

@media (prefers-color-scheme: light) {
  .project-tile {
    background-color: transparent;
    color: var(--tile-text-light);
    border: 1px solid var(--tile-border-light);
    box-shadow: 0 2px 8px var(--tile-shadow-light);
  }
  .project-meta {
    color: var(--tile-subtext-light);
  }
  .project-image {
    border: 1px solid var(--tile-border-light);
  }
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  gap: 20px;
  margin-top: 20px;
}

.project-tile {
  border-radius: 8px;
  padding: 20px;
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  cursor: pointer;
}

.project-tile:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 16px rgba(0,0,0,0.12);
}

@media (prefers-color-scheme: dark) {
  .project-tile:hover {
    box-shadow: 0 4px 16px rgba(255,255,255,0.08);
  }
}

.project-image {
  width: 100%;
  height: 120px;
  object-fit: cover;
  border-radius: 6px;
  background-color: #f0f0f0;
  margin-bottom: 16px;
}

@media (prefers-color-scheme: dark) {
  .project-image {
    background-color: #333333;
  }
}

.project-title {
  font-size: 1.25em;
  font-weight: bold;
  margin-bottom: 8px;
  line-height: 1.3;
}

.project-meta {
  font-size: 0.85em;
  margin-bottom: 12px;
  font-weight: 500;
}

.project-description {
  font-size: 0.95em;
  line-height: 1.5;
}

@media (max-width: 768px) {
  .projects-grid {
    grid-template-columns: 1fr;
    gap: 16px;
  }
  
  .project-tile {
    padding: 16px;
  }
  
  .project-image {
    height: 100px;
  }
}
</style>

<div class="projects-grid">
  <div class="project-tile">
    <img class="project-image" src="https://via.placeholder.com/400x120" alt="Hopfield Neural Network Project">
    <div class="project-title">Hardware Implementation of Hopfield Neural Network with AER for Maxcut Problem</div>
    <div class="project-meta">Course: Neuromorphic AVLSI | Timeline: Mar '25 – Apr '25</div>
    <div class="project-description">
      Designed and simulated a Hopfield Neural Network (HNN) using Verilog to solve the Maxcut problem, incorporating Address Event Representation (AER) for communication. The design was implemented and tested on an FPGA board.
    </div>
  </div>

  <div class="project-tile">
    <img class="project-image" src="https://via.placeholder.com/400x120" alt="RGB Image Filter Project">
    <div class="project-title">RGB Image Filter and HDMI Display on FPGA</div>
    <div class="project-meta">Course: Digital Systems Design with FPGA | Timeline: Mar '25 – Apr '25</div>
    <div class="project-description">
      Created an image processing pipeline using two different median filtering algorithms (Fast Median and Bit Voting) to clean salt-and-pepper noise. The processed image was displayed via HDMI output on a PYNQ-Z1 board.
    </div>
  </div>

  <div class="project-tile">
    <img class="project-image" src="https://via.placeholder.com/400x120" alt="IMU Sensor Car Project">
    <div class="project-title">IMU Sensor Controlled Car</div>
    <div class="project-meta">Open Day Demo | Timeline: Feb '25</div>
    <div class="project-description">
      Built a gesture-controlled car using an ESP32 and an IMU sensor. The car responded to hand tilts for directional movement, with a servo motor managing steering and an L298N driver powering the DC motors.
    </div>
  </div>

  <div class="project-tile">
    <img class="project-image" src="https://via.placeholder.com/400x120" alt="Booth Multiplier Project">
    <div class="project-title">16-bit Radix-4 Booth Multiplier with Power Gating</div>
    <div class="project-meta">Course: Digital VLSI | Timeline: Nov '24 – Dec '24</div>
    <div class="project-description">
      Designed a 16-bit signed/unsigned multiplier using Booth encoding and Wallace tree structure. Simulated using Cadence Virtuoso and optimized the layout for minimal area and dynamic power.
    </div>
  </div>

  <div class="project-tile">
    <img class="project-image" src="https://via.placeholder.com/400x120" alt="Air Quality Monitor Project">
    <div class="project-title">Air Quality Monitoring System</div>
    <div class="project-meta">Undergrad Project | Guide: Dr. Ankita Pramanik, IIEST Shibpur | Timeline: Sep '22 – Dec '22</div>
    <div class="project-description">
      Developed a real-time air quality monitor using Arduino and multiple gas sensors. The data was visualized through a web dashboard built with HTML, CSS, and JavaScript.
    </div>
  </div>
</div>