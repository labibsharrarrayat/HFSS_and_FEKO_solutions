# 🚀 HFSS & FEKO Solutions  
### Electromagnetic Simulation Portfolio with Power Integrity Relevance

This repository contains **full-wave electromagnetic simulations** performed using  
**ANSYS HFSS** and **Altair FEKO**, with a focus on **antenna behavior, field interactions, and impedance characteristics** that are directly relevant to **power integrity (PI) and high-speed hardware design**.

While the primary structures are antennas, the analyses emphasize **current flow, impedance control, field coupling, and frequency-dependent behavior**—the same physical mechanisms that govern **PDN stability, resonance, EMI/EMC, and signal integrity** in real electronic systems.

---

## 🔹 Current Distribution Across a Dipole (FEKO)

Understanding **current distribution** is fundamental to power integrity engineering.  
This simulation visualizes how RF currents propagate and concentrate along a resonant dipole—analogous to **current crowding and standing-wave effects** observed in PDN planes, vias, and interconnects at high frequencies.

![Current pattern](current_resonant1.png)

---

## 🔹 Dipole Radiation Patterns — HFSS vs FEKO

Cross-tool validation is a critical engineering practice.  
Here, far-field radiation patterns computed in **HFSS** and **FEKO** are compared to verify consistency, reinforcing confidence in **field solvers used for EMI prediction, enclosure coupling, and power-plane resonance analysis**.

![Radiation pattern](hfss_feko_comparison.png)

---

## 🔹 Smith Chart Analysis of Dipole Impedance (HFSS)

Impedance control lies at the heart of power integrity.  
This Smith chart illustrates how antenna input impedance varies with frequency, closely paralleling **PDN impedance targets**, **decoupling strategies**, and **resonance avoidance** in high-speed boards.

![Smith chart](hfss_smith_chart.png)

---

## 🔹 Dipole Input Impedance Comparison — HFSS vs FEKO

Accurate impedance prediction is essential for preventing **power rail oscillations and EMI hotspots**.  
This comparison highlights solver agreement on both real and reactive impedance components, a key requirement when modeling **via inductance, package parasitics, and plane discontinuities**.

![Impedance trend](hfss_feko_impedance.png)

---

## 🔹 Frequency-Dependent Radiation Behavior (HFSS)

Power integrity problems are inherently frequency-dependent.  
This study demonstrates how radiation patterns and beamwidth change with frequency—mirroring how **PDN resonances emerge and shift across operating bands**, impacting noise coupling and compliance margins.

![Radiation vs frequency](hfss_half_power_beamwidth2.png)

---

## 🔹 Cross-Polarized Dipole Configuration (3D Model)

Complex current paths and orthogonal field components are common in modern electronics.  
This 3D cross-polarized antenna model provides insight into **multi-axis coupling**, similar to interactions between **power, ground, and signal structures** in dense multilayer designs.

![Cross polarized model](3d_model.png)

---

## 🔹 Cross-Polarized Antenna Radiation Pattern

The resulting radiation pattern reveals polarization isolation and field orientation effects—concepts directly transferable to **EMI suppression, return-path control, and minimizing unwanted coupling** in power-distribution networks.

![Cross polarized radiation pattern](3d_pattern.png)

---

## 🔹 Impedance Magnitude and Phase Trend of a Dipole Across Frequency (HFSS)
This study examines the frequency-dependent impedance behavior of a dipole antenna using ANSYS HFSS, including both magnitude and phase variations across the operating band. The results highlight resonance behavior, impedance transitions, and phase reversal regions that are critical for matching, bandwidth estimation, and high-frequency signal integrity analysis in RF and mixed-signal systems.
![Dipole Impedance Trend](hfss_impedance_plot.png)

---

## 🔹 Right-Hand vs Left-Hand Circular Polarization (Half-Power Beamwidth Analysis in FEKO)
This simulation compares right-hand circular polarization (RHCP) and left-hand circular polarization (LHCP) radiation characteristics using FEKO. The analysis focuses on half-power beamwidth (HPBW) and polarization-dependent radiation behavior, providing insight into polarization purity, coupling effects, and directional performance relevant to antenna-system integration and electromagnetic compatibility studies.
![Right Hand vs Left Hand Polarization](LHC_RHC_HPBW.png)

---

## 🔹 Radar Cross Section estimation of a sperical object in FEKO
This simulation investigates the radar cross section (RCS) of a perfectly conducting spherical target under different polarization conditions using FEKO. The results illustrate fundamental EM scattering mechanisms, polarization sensitivity, and angular response, which are directly applicable to EMI/EMC analysis, unintended radiation assessment, and high-frequency system modeling.
<p align="center">
  <img src="bistatic_sphere2.png" width="35%">
  <img src="sphere_rcs.png" width="45%">
</p>

---

## 🔹 Radar Cross Section estimation of a square object in FEKO
This study extends the RCS analysis to a square conductive target, highlighting how geometry-induced discontinuities and edge diffraction affect scattering behavior. The comparison with spherical targets provides practical intuition for package, board, and enclosure-level EM scattering, which is critical in signal and power integrity analysis of complex electronic systems.
<p align="center">
  <img src="bistatic_square2.png" width="35%">
  <img src="square_go_rcs.png" width="45%">
</p>

---

## 🔹 Dipole with Loading Plates in FEKO
This simulation analyzes the current distribution along a dipole antenna with loading plates, demonstrating how structural loading alters current flow, effective electrical length, and radiation behavior. The results provide insight into impedance control, resonance tuning, and current crowding, which are closely related to return-path integrity and high-frequency conductor design.
<p align="center">
  <img src="dipole_loading_plates.png" width="35%">
  <img src="current_distribution.png" width="35%">
</p>

---

## 🔹 Dipole on a circular PEC plate
This study examines the effect of finite reference planes by simulating a dipole mounted on a circular perfect electric conductor (PEC) plate with varying radii. The resulting radiation patterns illustrate how ground plane size and boundary conditions influence field distribution and radiation behavior, directly analogous to reference-plane effects in PCB signal and power integrity design.
![Radiation Pattern on Plate](radiation_patterns1.png)

---

## 🔹 Circular loop antenna
Simulation and radiation analysis of a circular loop antenna excited at multiple feed locations along the loop. This study highlights how excitation position and loop geometry affect current distribution and radiation patterns, reinforcing fundamental concepts relevant to magnetic-field coupling, near-field behavior, and EMI analysis.
<p align="center">
  <img src="simulation_setup_loop.png" width="35%">
  <img src="feko_radius_large.png" width="35%">
</p>

---

## 🔹 Cone Antenna in HFSS
This simulation explores the impedance characteristics and radiation patterns of a conical antenna across multiple frequencies using HFSS. The results demonstrate broadband impedance behavior and frequency-dependent radiation trends, offering insight into wideband antenna design, impedance stability, and high-frequency electromagnetic modeling.
<p align="center">
  <img src="cone_HFSS.png" width="35%">
  <img src="Impedance_HFSS.png" width="55%">
  <img src="radiation_pattern_hfss.png" width="35%">
</p>

---


