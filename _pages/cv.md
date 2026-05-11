---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A PDF version of my CV is available [here](../files/cv.pdf).

Summary
======
Fifth-year Ph.D. candidate developing **temporally robust learning, optimization, and control algorithms** that remain reliable under non-stationarity and temporal drift. My research bridges **distributed optimization, online system identification, and agentic AI**, focusing on decision-making systems that stay stable, safe, and adaptive — from semidefinite optimization in power systems to memory safety and reasoning stability in large-language-model agents.

Education
======
* **Ph.D., Electrical and Computer Engineering**, Virginia Tech, Aug 2021 – Present
  * Advisor: Dr. Ming Jin
* **M.S., Mechanical Engineering — Mechatronics**, Jordan University of Science and Technology, Aug 2018 – May 2021
  * Thesis: *Model Order Determination with Applications in System Identification, Image and Signal Processing*
  * Advisor: Dr. Khaled F. Aljanaideh
  * GPA: 4.2 / 4.4
* **B.Tech., Aeronautical Engineering**, Jordan University of Science and Technology, Aug 2012 – Nov 2016
  * GPA: 86.7% — graduated top of class (1/40)

Academic Experience
======
* **Graduate Research Assistant**, ECE Department, Virginia Tech — Aug 2021 – Present
  * Mentor: Dr. Ming Jin
  * Developing temporally robust learning, optimization, and control algorithms resilient to non-stationarity — from distributed optimization to agentic AI.
* **Research Assistant**, Jordan University of Science and Technology — May 2021 – Aug 2021
  * Model order determination with applications in system identification.
* **Research Assistant, Fuel Cell–Gas Turbine Hybrid Power & Autotronics**, JUST — Jun 2017 – Aug 2018
  * Fuel cell–gas turbine hybrid power systems and automotive electronics.
* **Research Assistant, Composite Materials Lab**, JUST — Nov 2016 – Jun 2017
  * Interlaminar fracture toughness testing of composite laminates (Mode I opening, Mode II in-plane shear, End-Notched Flexure test).

Ongoing Research Projects
======
* **Memory safety and stability in long-horizon agentic systems.** This project studies how state, memory, and model structure shape behavior over time. The goal is to build diagnostics and guarantees for long-horizon operation. We treat memory and context as evolving internal states and analyze when they lead to failures such as incorrect commitments, disclosure, or inconsistent decisions. The work develops measurable predictors from retrieval-time signals and uses them to monitor risk before generation in agentic AI systems.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards & Scholarships
======
* **2026** — Pratt Fellowship, Virginia Tech, Department of Electrical and Computer Engineering (Spring 2026)
* **2024** — ACC 2024 Travel Scholarship
* **2012–2018** — Full Scholarship (B.Sc. & M.Sc.), Ministry of Education, Jordan

Technical Skills
======
* **Programming languages & tools:** Python, MATLAB & Simulink, C++, LaTeX, Mathematica, ANSYS, Pro-Engineer
* **Frameworks:** PyTorch, TensorFlow, CVX, CVXPY, Cvxpylayer, Gurobi, NumPy, Pandas, Scikit-learn; experience with HPC

Service
======
* **Conference reviewer:** ICML 2026; ICLR 2025; ACC 2024, 2025, 2026; CDC 2025; IFAC 2023, 2025; IEEE Transactions on Control of Network Systems
* **Tutorials:** *Distributed Control Strategies for Resilient Power Grids*, SmartGridComm 2024
