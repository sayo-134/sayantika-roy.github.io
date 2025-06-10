---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

<style>
:root {
  --card-bg-light: #ffffff;
  --card-bg-dark: #1e1e1e;
  --card-text-light: #2c3e50;
  --card-text-dark: #ecf0f1;
  --card-subtext-light: #888;
  --card-subtext-dark: #bdc3c7;
}

@media (prefers-color-scheme: dark) {
  .project-card {
    background-color: var(--card-bg-dark);
    color: var(--card-text-dark);
  }
  .project-meta {
    color: var(--card-subtext-dark);
  }
} 

@media (prefers-color-scheme: light) {
  .project-card {
    background-color: var(--card-bg-light);
    color: var(--card-text-light);
  }
  .project-meta {
    color: var(--card-subtext-light);
  }
}

.project-card {
  border-radius: 12px;
  padding: 16px;
  margin-bottom: 20px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.05);
  display: flex;
  gap: 16px;
  align-items: flex-start;
}
.project-image {
  width: 120px;
  height: 80px;
  object-fit: cover;
  border-radius: 8px;
  background-color: #ccc;
}
.project-text {
  flex: 1;
}
.project-title {
  font-size: 1.2em;
  font-weight: bold;
}
.project-meta {
  font-size: 0.9em;
  margin-bottom: 8px;
}
.project-description {
  font-size: 1em;
}
</style>

<div class="project-card">
  <img class="project-image" src="https://via.placeholder.com/120x80" alt="Project Image">
  <div class="project-text">
    <div class="project-title">Hardware Implementation of Hopfield Neural Network with AER for Maxcut Problem</div>
    <div class="project-meta">Course: Neuromorphic AVLSI | Timeline: Mar '25 – Apr '25</div>
    <div class="project-description">
      Designed and simulated a Hopfield Neural Network (HNN) using Verilog to solve the Maxcut problem, incorporating Address Event Representation (AER) for communication. The design was implemented and tested on an FPGA board.
    </div>
  </div>
</div>

<div class="project-card">
  <img class="project-image" src="https://via.placeholder.com/120x80" alt="Project Image">
  <div class="project-text">
    <div class="project-title">RGB Image Filter and HDMI Display on FPGA</div>
    <div class="project-meta">Course: Digital Systems Design with FPGA | Timeline: Mar '25 – Apr '25</div>
    <div class="project-description">
      Created an image processing pipeline using two different median filtering algorithms (Fast Median and Bit Voting) to clean salt-and-pepper noise. The processed image was displayed via HDMI output on a PYNQ-Z1 board.
    </div>
  </div>
</div>

<div class="project-card">
  <img class="project-image" src="https://via.placeholder.com/120x80" alt="Project Image">
  <div class="project-text">
    <div class="project-title">IMU Sensor Controlled Car</div>
    <div class="project-meta">Open Day Demo | Timeline: Feb '25</div>
    <div class="project-description">
      Built a gesture-controlled car using an ESP32 and an IMU sensor. The car responded to hand tilts for directional movement, with a servo motor managing steering and an L298N driver powering the DC motors.
    </div>
  </div>
</div>

<div class="project-card">
  <img class="project-image" src="https://via.placeholder.com/120x80" alt="Project Image">
  <div class="project-text">
    <div class="project-title">16-bit Radix-4 Booth Multiplier with Power Gating</div>
    <div class="project-meta">Course: Digital VLSI | Timeline: Nov '24 – Dec '24</div>
    <div class="project-description">
      Designed a 16-bit signed/unsigned multiplier using Booth encoding and Wallace tree structure. Simulated using Cadence Virtuoso and optimized the layout for minimal area and dynamic power.
    </div>
  </div>
</div>

<div class="project-card">
  <img class="project-image" src="https://via.placeholder.com/120x80" alt="Project Image">
  <div class="project-text">
    <div class="project-title">Air Quality Monitoring System</div>
    <div class="project-meta">Undergrad Project | Guide: Dr. Ankita Pramanik, IIEST Shibpur | Timeline: Sep '22 – Dec '22</div>
    <div class="project-description">
      Developed a real-time air quality monitor using Arduino and multiple gas sensors. The data was visualized through a web dashboard built with HTML, CSS, and JavaScript.
    </div>
  </div>
</div>
