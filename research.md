---
layout: default
title: "3D localization using defect-induced waves"
---
# 3D localization using defect-induced waves
The goal of this research is to minimize the number of receivers needed for defect localization in hazardous environments, where robotic deployment is crucial to eliminate human exposure. Focusing on hollow cylindrical structures, we have developed a waveform-based method that exploits the unique patterns created by the cylindrical geometry.
<a target="_blank" href="https://doi.org/10.1177/14759217241260254">[article]</a>

## Impact  
### Receiver Efficiency  
Our method reduces the required receivers from 4 to 2, ensuring precise defect localization while simplifying robotic deployment logistics.  
### Enhanced 3D Localization  
By leveraging the entire waveform, our approach achieves 3D defect positioning, surpassing traditional 2D methods and empowering more informed maintenance decisions.  

## Propagation Pattern  
The formation of defects induces elastic waves to propagate through the structure. In plate-like structures—such as a hollow cylinder, which can be thought of as a wrapped-up plate, the boundary conditions give rise to a special wave mode called **guided wave**. Unlike traditional ultrasonic waves that bounce within a medium (like in medical ultrasound exams), guided waves carry energy along the boundary of the medium.  

These waves propagate from the source in circular-crested wave fronts, similar to the ripples created when a stone is dropped into a lake. In most cases, we observe the **fundamental symmetric mode (S0)** and the **fundamental asymmetric mode (A0)**, with S0 traveling faster than A0.

And here's the cool part: in a hollow cylinder, the "plate" has no boundary, meaning there are infinite possible paths between two points. For example, the **direct path** and **2nd-order paths** are shown in the figure below. More interestingly, the lengths of these paths are unique to the source's coordinates!  

As a result, **energy arrives at a receiver with time delays corresponding to the unique combination of path lengths**, making the waveform distinctive for each source location. The figure below illustrates how path lengths and mode arrivals contribute to the waveform's uniqueness relative to the source coordinates.

<img src="assets\img\content\vae\waveforms.jpg" alt="helical paths figure" style="display: block; margin: 0 auto;max-width: 600px" />


