---
permalink: /
title: "About Me"
excerpt: "Homepage of Ziyi Guo"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a fourth-year undergraduate student at **Wuhan University, Hongyi Honor College**, majoring in **Microelectronics Science and Engineering**. My research focuses on **cross-layer design for AI chips and systems**, spanning from algorithms to architecture and circuit design. My research directions are motivated by bottlenecks observed in real hardware implementations.

In **Spring 2025**, I studied at **UC Berkeley** as a visiting student. Since **Summer 2025**, I have been conducting research on **energy-efficient SoC accelerators for generative AI** at **Duke University**, supervised by [Prof. Yiran Chen](https://ece.duke.edu/people/yiran-chen/) and [Dr. Changchun Zhou](https://changchun-zhou.github.io/). 

My research interests include: 
- AI accelerator architecture and microarchitecture for edge computing  
- Hardware–software co-design for efficient AI acceleration
- Chip design for energy-efficient AI accelerators (SoC/ASIC) under bandwidth and dataflow constraints


More details about my research and projects can be found in my [CV](../docs/Ziyi_s_CV.pdf).

<strong style="color:red;">I am actively seeking Ph.D. opportunities for Fall 2026.</strong>


---

# 🔥 News
- 09/2025: I won **Innova International Exchange Scholarship**!
- 06/2025: Joined Duke University as a module leader in the project **Energy-efficient SoC for Generative AI**.  
- 05/2025: Completed **RISC-V 3-Stage CPU with UART on FPGA** projects at UC Berkeley. 
- 09/2024: I won **National Scholarship** (top 0.2% nationwide)!
- 06/2024: Started leading the project **Thermal Dissipation Mechanism of High-Temperature Hydrogels** at Wuhan University.  

---

# 📖 Education
- *Sep 2022 – Jun 2026 (expected)*, **Wuhan University, China**  
  Hongyi Honor College, B.Eng. in Microelectronics Science & Engineering, GPA: 3.94/4.00 
  <!-- , ranked 2/55 -->

- *Jan 2025 – May 2025*, **University of California, Berkeley**  
  Visiting Student, Berkeley International Study Program · Coursework: Digital Design and IC Circuits (A)

---

# 🎖 Honors and Awards
-  **National Scholarship**, *Ministry of Education of China* (Top 0.2% nationwide), 11/2024
-  Innova International Exchange Scholarship, *Wuhan University* (11 recipients university-wide), 09/2025
- University Outstanding Student Scholarship, *Wuhan University* (Top 5%), 2023 & 2024
- University Merit Student, *Wuhan University*, 2023 & 2024
- Outstanding Volunteer of Wuhan University, *Wuhan University*, 09/2024
- University Social Activist, *Wuhan University*, 09/2023

---
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISCAS 2026</div><img src='images/figure_hardware.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<!-- [Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf) -->
A Unified Function Processor with Integer Arithmetic Based on Piecewise Chebyshev Polynomial Approximation

X. Zheng\*, **<u>Z. Guo</u>**\*, et al.

*IEEE International Symposium on Circuits and Systems (ISCAS) (Accepted)*
<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>.  -->

<details>
<summary>Abstract</summary>
Nonlinear functions are fundamental components in widely applied AI algorithms. However, their hardware implementation presents a major challenge due to the diversity of function types and the full precision requirement (e.g., FP32), which results in significant area and energy overheads. To overcome these issues, we present a Unified Function Processor (UFP) with integer arithmetic, capable of efficiently computing a wide range of nonlinear functions with high accuracy under integer constraints. First, we propose a dynamic programming segmentation algorithm within a third-degree Chebyshev polynomial framework that optimally partitions each function into eight integer-aligned segments to minimize global quantization error. Second, a unified three-stage pipelined hardware with computation element reuse is proposed. Implemented in TSMC 28-nm HPC technology and working at 1GHz, the proposed UFP achieves up to 93.6% reductions in area compared to the state-of-the-art works, with a 79% lower energy consumption. The architecture flexibly supports all mainstream functions in AI algorithms with configurable precision and range, offering a compact and scalable solution for AI acceleration hardware.
</details> 

</div>
</div>

# 📝 Research Experience

**Energy-efficient Acceleration SoC for Generative AI**  
Module leader | *Supervised by Prof. Yiran Chen and Dr. Changchun Zhou*  
- Led the design and integration of multiple key IP modules within a generative AI accelerator SoC, including a Unified Function Processor (UFP) for nonlinear operations (ReLU, GeLU, Softmax), sampling and data similarity modules.   

**RISC-V 3-Stage Pipelined CPU with UART on FPGA** (UC Berkeley, 2025)  
- Built a complete pipelined RISC-V CPU from scratch on FPGA, achieving CPI and frequency improvements and gaining system-level insight into control, data hazards, and verification constraints.

**Thermal Dissipation Mechanism of High-Temperature Hydrogels** (Wuhan Univ., 2024–2025)  
- Conducted interdisciplinary research on thermal management for battery systems.

---

# 💻 Skills
- **Digital IC Design:** RTL coding, SoC IP, AXI-4 bus, DPI-C co-simulation
- **EDA Tools:** Cadence, Synopsys VCS, Vivado, ModelSim
- **Programming:** Verilog, Python, C/C++, SQL, Matlab  
- **Languages:** English (TOEFL 106), Chinese (Native)

---

# 💬 Extra-curricular & Leadership
- Head of **Wuhan University Student Art Troupe** (2024–2025)  
- Deputy Head of **Petrel Choir** (2024–2025)  
- Invited to sing at the **2024 WA Chinese New Year Ball** for Australian Prime Minister Albanese  
- Collaborated with **Dai Yuqiang** (One of the "Three Tenors of China")  
- Member of Volunteer Center and Kungfu Association (2022–2023)  

<!-- <div align="center" style="width:50%; display:none;">
  <script type="text/javascript" id="clstr_globe" 
          src="//clustrmaps.com/globe.js?d=k9EkBsh9ikQhvDJjkDUDLz6oSQ7jA4L1koxq-fT3xcg">
  </script>
</div> -->
<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=k9EkBsh9ikQhvDJjkDUDLz6oSQ7jA4L1koxq-fT3xcg&cl=ffffff&w=a"></script>
