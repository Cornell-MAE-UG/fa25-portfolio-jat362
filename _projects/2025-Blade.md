---
layout: project
title: Wind Turbine Blade Design Project
description: MAE 4272
technologies: [MATLAB, LabVIEW VI]
image: /assets/images/wind-turbine-blade.jpg
---


In this project, our team was tasked with designing, modeling, and experimentally testing a small-scale wind turbine blade optimized for realistic operating conditions in a wind tunnel. The goal was to maximize average power output at the most probable wind speed (4.78 m/s) while adhering to strict constraints on rotational speed, torque brake limits, manufacturability, and material strength. A key objective was to evaluate how well a MATLAB-based aerodynamic model could predict real blade performance and to use experimental data to validate or refine that model.

Our design process combined aerodynamic modeling, structural constraints, and probabilistic wind analysis. We assumed steady, incompressible flow, rigid blades, attached flow, and a Weibull-distributed wind speed profile. Early modeling predicted that a longer blade would exceed torque brake limits, so we initially designed a short, conservative blade to ensure safe testing. After testing revealed that the model significantly overestimated torque and power, we revised our design and produced a second, longer blade. This second iteration allowed us to explore the trade-off between blade length, rotational speed, and power output, and highlighted the importance of iterative design and experimental validation when theoretical assumptions break down.

Both blade designs were tested in the Big Blue wind tunnel using a pitot tube, pressure transducer, torque brake, and LabVIEW VI. For each blade, we generated power curves by fixing wind speed and incrementally increasing brake voltage until stall, allowing us to measure torque, RPM, and mechanical power. Data were collected across multiple wind speeds within the operational range, averaged to reduce noise, and compared directly against model predictions. While both blades operated safely and showed expected qualitative trends, measured power output was roughly an order of magnitude lower than predicted, revealing shortcomings in the aerodynamic force estimation and pitch distribution assumptions.

My primary contributions included assisting with the MATLAB modeling and interpretation of results, helping analyze discrepancies between theoretical and experimental performance, and supporting wind tunnel testing and data collection. I also contributed to refining design assumptions after the first round of testing and to synthesizing results into clear conclusions. Throughout the project, our group maintained strong communication and collaboration, with responsibilities well distributed and all members actively engaged in design, testing, and analysis, which was critical to successfully completing an iterative and experimentally driven project.


![Experimental power curves]({{ "/assets/images/power-curves.png" | relative_url }}){:style="width: 550px"}