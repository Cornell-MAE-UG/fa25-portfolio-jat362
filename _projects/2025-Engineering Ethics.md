---
layout: project
title: Engineering Ethics Portfolio (MAE 4300)
description: MAE 4300
#sources: [SolidWorks, Machining]
image: /assets/images/lion air crash.webp
---

**Background of the Boeing 737 MAX:**


The Boeing 737 MAX incidents involved two fatal crashes. One was Lion Air Flight 610 in October 2018 and the other was Ethiopian Airlines Flight 302 in March 2019. Together, both incidents resulted in the loss of 346 lives. These accidents were linked to failures in the design, implementation, and certification of the Maneuvering Characteristics Augmentation System (MCAS), a flight control software introduced on the 737 MAX.

*Lion Air Flight 610 Crash (Source: CNN News):*
![Experimental power curves]({{ "/assets/images/lion air cnn.jpg" | relative_url }}){:style="width: 550px"}


*Ethiopian Airlines Flight 302 Crash (Source: ABC News):*
![Experimental power curves]({{ "/assets/images/eth airlines crash.jpg" | relative_url }}){:style="width: 550px"}

The 737 MAX was developed in response to competitive pressure from Airbus’s A320neo. To improve fuel efficiency, Boeing installed larger, more fuel-efficient engines, which were mounted higher and farther forward on the wing than on previous 737 models. This change altered the aircraft’s aerodynamics, increasing the tendency for the nose to pitch up at high angles of attack (AoA).

To compensate for this behavior and maintain handling characteristics similar to earlier 737s, Boeing implemented MCAS. MCAS was designed to automatically command nose-down stabilizer trim when it detected a high AoA, helping prevent stalls.

However, there were many technical failures with the MCAS. 
1. Single-Sensor Dependency:
The MCAS relied on input from only one angle-of-attack sensor at a time, despite the aircraft having two sensors available. If that sensor failed or provided erroneous data, MCAS could activate incorrectly.

2. Repeated Activation Authority:
The MCAS could repeatedly command nose-down trim without pilot input and with greater authority than initially disclosed. This led to cumulative nose-down trim that pilots struggled to counteract.

3. Lack of Pilot Awareness and Training:
The MCAS was not clearly documented in pilot manuals, and pilots were not trained on its behavior or failure modes. Many were unaware the system existed.

4. Human–Machine Interface Issues:
The alerts that could indicate sensor disagreement were optional features, meaning some aircraft lacked clear warnings that data was faulty.

*MCAS graphic (Source: Seattle Times):*
![Experimental power curves]({{ "/assets/images/mcas system.png" | relative_url }}){:style="width: 550px"}

As a result, a faulty AoA sensor triggered MCAS shortly after takeoff in both crashes since the MCAS repeatedly forced the aircraft’s nose downward. The pilots were confused by conflicting indications and unaware of MCAS’s role as they were unable to recover control before impact.


**General Analysis:**

This report examines the ethical failures surrounding the Boeing 737 MAX accidents through the lens of an engineering ethics framework. Using the MCAS (Maneuvering Characteristics Augmentation System) as a focal point, the analysis evaluates how technical decisions, organizational culture, regulatory oversight, and economic pressures interacted within a complex sociotechnical system to produce catastrophic outcomes. The objective of this report is to identify key ethical issues, clarify underlying assumptions and definitions, and assess the roles and responsibilities of individual and institutional stakeholders.

The analysis begins by identifying a broad set of ethical concerns, including:
1. Inadequate system
2. Insufficient pilot training
3. Lack of transparency with regulators and airlines
4. Economic pressure influencing design decisions
5. Failures in internal communication and escalation of safety concerns. 

These issues highlight systemic failures rather than isolated technical errors.

To support ethical evaluation, the report demonstrates how differing interpretations can shape ethical judgments and influence decision-making within engineering organizations. Given gaps in publicly available information, this report makes assumptions grounded in internal communications, and established patterns of organizational behavior. Relevant facts are categorized into material, individual, and organizational domains, emphasizing the interconnected nature of engineering decisions and institutional processes. Evidence from government reports and accident investigations supports the conclusion that competitive pressure, delegated regulatory authority, and a culture prioritizing efficiency over safety played a significant role in the failure of the 737 MAX system.

In addition, the incidents revealed systemic issues beyond technical flaws. 

There was economic pressure where Boeing prioritized rapid certification and minimal pilot retraining to compete with Airbus, influencing design and disclosure decisions. The FAA delegated significant certification authority to Boeing, limiting independent review of MCAS’s safety implications. Furthermore, safety concerns raised internally by engineers were not always effectively escalated or addressed. As a result, there have been many moving parts and factors that contributed to the accidents of the 737 MAX. Many people often only look at Boeing as the one to take the blame, others the engineers who worked on the plane, but in many cases like these, it is a combination of many. There were many reasons that drove decisions, some of which were more unethical than others. 


**Ethical Analysis Using the ASME Code of Engineering Ethics:**

The Boeing 737 MAX accidents represent a failure of engineering ethics across technical design, organizational decision-making, and regulatory oversight. Applying the ASME Code of Ethics highlights where actions and omissions conflicted with core professional obligations, particularly regarding public safety, transparency, and accountability. Below are some examples of cannons that were not adhered. 

<u>Canon 1: Engineers shall hold paramount the safety, health, and welfare of the public.</u>

Relevant Principles: Engineers must consider the safety implications of their work and disclose factors that might endanger the public. Engineers shall not approve unsafe designs.

This canon is the most directly violated in the 737 MAX case. MCAS was designed with single-sensor dependency, lacked redundancy, and had the authority to repeatedly command nose-down trim without adequate pilot awareness. These design decisions created a single point of failure in a safety-critical system.

Additionally, pilots were not fully informed or trained on MCAS behavior or failure modes. By allowing an automated system to exert significant control without ensuring pilots understood how to recognize and disable it, Boeing failed to prioritize passenger safety over cost and schedule pressures. The resulting crashes demonstrate that public welfare was not held paramount.


<u>Canon 3: Engineers shall issue public statements only in an objective and truthful manner.</u>

Relevant Principles: Engineers must avoid deceptive acts. Technical communications must be complete and accurate.

Boeing minimized MCAS’s role in aircraft handling characteristics in communications with airlines, pilots, and regulators. MCAS was not emphasized in pilot manuals, and its full authority and failure modes were not clearly disclosed.

This lack of transparency hindered pilots’ ability to respond effectively during emergencies and limited regulators’ ability to fully assess system risks. These actions conflict with the ethical requirement for honest and complete technical communication.


<u>Canon 5: Engineers shall avoid deceptive acts.</u>

Relevant Principles: Engineers must not misrepresent facts or omit critical information.



The delegation of certification authority to Boeing and the incomplete disclosure of MCAS functionality to the FAA raise ethical concerns under this canon. By not fully communicating the system’s authority, redundancy limitations, and reliance on a single AoA sensor, Boeing contributed to regulatory blind spots that compromised safety oversight.


**Conclusion:**

Overall, this report concludes that the Boeing 737 MAX tragedies resulted from compounded ethical failures across technical design, corporate governance, and regulatory oversight. The case underscores the ethical responsibility of engineers and organizations to prioritize public safety, ensure transparency, and uphold accountability within complex systems. These lessons remain critical for preventing future failures in high-risk engineering domains.

Following the second crash, the 737 MAX was grounded worldwide for nearly two years. During this process, Boeing redesigned the MCAS to use data from both AoA sensors, limit control authority, improve pilot alerts and training, and much more. The 737 MAX was recertified in late 2020, but the incident remains a defining case study in engineering ethics, systems engineering, human factors, and safety-critical design.


*New Boeing 737 Max after undergoing updates to their system (Source: Skies Mag):*
![Experimental power curves]({{ "/assets/images/new 737 max.jpg" | relative_url }}){:style="width: 550px"}

