---
layout: page
subheadline: "Emergency Department Simulation"
title: "Background and Motivation"
teaser: "A high-level overview of why we are building an emergency department LLM simulation and the impact we hope it will have."
header:
   image_fullwidth  : "widget_hospital_background.jpg"

permalink: "/background/"
---

**Background.** Canadians rely extensively on Emergency Department (ED) care. In fact, we have the highest rate of ED use among wealthy countries with universal health care. However, the emergency care experience in Canada is substandard. Often, the volume of patients seeking care outmatches the capacity to move patients through the ED, leading to overcrowding. This results in excessive wait times and patients leaving without seeing a physician. This delayed, or lack of, access to care results in poor patient experience and increased risk of morbidity and mortality. We have experienced steadily increasing wait times for patients to see a physician and lengths of stay in the ED over the past decade with no signs of improvement. Overcrowding in the ED has been referred to as the "canary in the coal mine" of the healthcare system. It is not just simply a function of the number of patients presenting to the ED (input), but also depends on ED throughput (length of stay in the ED), and the ability to move patients out of the ED through admission to in-patient units or safe discharge.

**Motivation.** We are focused on relieving multiple, compounding pressures inside emergency departments:

- **High ED utilization rates:** Canada leads wealthy nations in ED use, stretching limited resources.
- **Inefficient patient throughput:** EDs are sociotechnical systems where human, technical, and organizational factors ripple through every handoff.
- **Physician and nurse burnout:** Clinicians face record levels of burnout as documentation and chart review consume scarce time.
- **Electronic health record friction:** Clinicians often meet patients for the first time in the ED and must rapidly reconstruct a complete history from fragmented records.

To tackle these challenges, we are leveraging large language models to:

- Improve chart summarization so clinicians can reach a clear picture faster and with less effort.
- Develop agent-based simulations that explore and optimize ED workflows before changes happen on the floor.

We expect these LLM-powered tools to unlock timelier, more accurate diagnoses, lessen provider burnout, and ultimately deliver better outcomes for patients depending on emergency care.

**Team Composition.** Our interdisciplinary team brings together expertise from a variety of fields, including:

- Emergency medicine physicians and nurses
- Social workers
- Software engineers
- Machine learning researchers
- Data scientists
- Social scientists
- ED patients

This diverse team ensures that our research stays technically sound, ethically grounded, and aligned with the real-world needs of both patients and healthcare providers.
