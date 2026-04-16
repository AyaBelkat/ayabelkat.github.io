---
layout: page
title: Projects
permalink: /projects/
---

## Trajectory Design and Optimisation of a Flyby Mission to Asteroid 2024 YR4

**MSc Dissertation · University of Surrey · 2024–2025**


A high-fidelity interplanetary trajectory design and optimisation framework for a flyby mission to Asteroid 2024 YR4, developed in MATLAB. Three mission architectures were explored and compared: a ballistic direct transfer, an Earth gravity assist, and a Venus gravity assist — each incorporating a Deep Space Manoeuvre (DSM) to minimise total propellant requirements.

**Key methods:** Izzo's Lambert solver, MGADSM framework, Monotonic Basin Hopping global optimisation, B-plane targeting, NASA SPICE toolkit for high-fidelity ephemeris propagation.

**Launch window analysis** — Earth–2024 YR4 porkchop plot identifying optimal departure and arrival dates:

![Earth-2024YR4 Porkchop Plot](/assets/images/projects/asteroid_porkchop_plot_2031_2032.jpg)

**Optimised Venus flyby trajectory** — achieving a 26.5% ΔV reduction over the ballistic baseline:

![MGADSM Venus Flyby Trajectory](/assets/images/projects/MGADSM_venus_traj.png)

**Ballistic transfer baseline** — direct Earth to 2024 YR4 transfer for comparison:

![Ballistic Trajectory](/assets/images/projects/plot_ballistic_trajectory.png)

**Results summary:**

| Architecture | Departure | Arrival | Total ΔV (km/s) | TOF (days) |
| :--- | :--- | :--- | :--- | :--- |
| Ballistic Transfer | 17 Feb 2032 | 17 Nov 2032 | 1.749 | 274 |
| Earth Gravity Assist + DSM | 14 Oct 2028 | 07 Nov 2032 | 3.807 | 1485 |
| Venus Gravity Assist + DSM | 27 May 2031 | 13 Oct 2032 | 2.796 | 505 |

Full implementation, results, and documentation available on [GitHub](https://github.com/AyaBelkat/Trajectory-Design-and-Optimization-for-a-Flyby-Mission-to-Asteroid-2024-YR4).

---

## Hybrid Rocket Engine — Race2Space Competition

**Sensor Integration Lead & Manufacturing Co-Lead · Peryton Space Society, University of Surrey · 2024–2025**

Designed, built, and hot-fire tested a paraffin-based hybrid rocket engine as part of the international Race2Space competition. Led sensor selection, integration, and data acquisition system compatibility across a cross-functional team of mechanical and electronics engineers.

The team achieved **5th place out of 12 international teams**, with a successful hot-fire test validating engine performance and structural integrity.

[View team post on LinkedIn](https://www.linkedin.com/posts/peryton-space_phyre-1-hot-fire-on-june-27th-2025-activity-7350449024086228992-4udp)

---

*More projects coming soon.*
