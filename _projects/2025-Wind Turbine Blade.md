---
layout: project
title: Wind Turbine Blade Design Project
description: MAE 4272
technologies: [MATLAB, LabVIEW VI]
image: /assets/images/wind-turbine-blade.jpg
---


In this project, our team was tasked with designing, modeling, and experimentally testing a small-scale wind turbine blade optimized for realistic operating conditions in a wind tunnel. The goal was to maximize average power output at the most probable wind speed (4.78 m/s) while adhering to strict constraints on rotational speed, torque brake limits, manufacturability, and material strength. A key objective was to evaluate how well a MATLAB-based aerodynamic model could predict real blade performance and to use experimental data to validate or refine that model.

Our design process combined aerodynamic modeling, structural constraints, and probabilistic wind analysis. We assumed steady, incompressible flow, rigid blades, attached flow, and a Weibull-distributed wind speed profile. Unlike most groups, our team evaluated two blade designs instead of a single final design. This decision was based on our initial concern regarding the torque break limit of Big Blue. Based on our MATLAB model and calculations, a longer blade was predicted to generate torque levels that could exceed the safe operating limits. To avoid breaking our blade and potentially damaging testing equipment, we decided to go with a shorter blade for our design and testing. When testing, the shorter blade was spun reliably but produced significantly less torque and power than expected. This suggested that our original analytical model likely overestimated the torque output of a longer blade, leading us to be overly conservative in the first design. As a result, the initial blade, while safe, did not fully utilize the available experimental operating range. After revising our blade, we were able to test again and explore the trade-off between blade size, torque production, and power output. Testing both designs ultimately provided valuable insight into the limitations of our modeling assumptions and highlighted the importance of experimental validation and iterative design.


CAD images of our short and long blades:
![Short and Long Blades]({{ "/assets/images/short blade.png" | relative_url }}){:style="width: 350px"}
![Short and Long Blades]({{ "/assets/images/long blade.png" | relative_url }}){:style="width: 350px"}

Both blade designs were tested in the Big Blue wind tunnel using a pitot tube, pressure transducer, torque brake, and LabVIEW VI. For each blade, we generated power curves by fixing wind speed and incrementally increasing brake voltage until stall, allowing us to measure torque, RPM, and mechanical power. Data were collected across multiple wind speeds within the operational range, averaged to reduce noise, and compared directly against model predictions. While both blades operated safely and showed expected qualitative trends, measured power output was roughly an order of magnitude lower than predicted, revealing shortcomings in the aerodynamic force estimation and pitch distribution assumptions.

Power Curves for the Short Blade:
![Experimental power curves]({{ "/assets/images/short-power-curves.png" | relative_url }}){:style="width: 550px"}


Power Curves for the Long Blade:
![Experimental power curves]({{ "/assets/images/long-power-curves.png" | relative_url }}){:style="width: 550px"}

While our blades operated as expected in terms of rotational behavior, the measured power output was about an order of magnitude lower than predicted. This discrepancy highlighted limitations in our modeling assumptions, particularly the neglect of drag, turbulent losses, and stall effects, which led to an overestimation of the useful aerodynamic forces acting on the blades.
For future iterations, we would refine the model to better account for these effects by incorporating drag and stall behavior into the aerodynamic analysis, adjusting the blade twist to achieve a lower pitch angle near the tip. 


My primary contributions included assisting with the MATLAB modeling and interpretation of results, helping analyze discrepancies between theoretical and experimental performance, and supporting wind tunnel testing and data collection. I also contributed to refining design assumptions after the first round of testing and to synthesizing results into clear conclusions. Throughout the project, our group maintained strong communication and collaboration, with responsibilities well distributed and all members actively engaged in design, testing, and analysis, which was critical to successfully completing an iterative and experimentally driven project.




