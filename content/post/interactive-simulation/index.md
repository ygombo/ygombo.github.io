---
title: "Interactive Simulation: Standard vs DSR (Pinned Laplacian Tracking)"
date: 2023-08-24
description: "Interactive simulation comparing Standard and DSR methods for pinned Laplacian tracking"
draft: false
---

This interactive simulation allows you to explore and compare the Standard and DSR (Dynamic Surface Reset) methods for pinned Laplacian tracking. The simulation is based on models from Gombo, Tiwari, Devasia (arXiv:2102.09056).

{{< rawhtml >}}
<iframe src="/sim.html" style="width:100%; height:1200px; border:none; border-radius:12px; background:#0b0f14;"></iframe>
{{< /rawhtml >}}

### About the Simulation

The simulation lets you experiment with different parameters:

- Number of agents and topology configuration
- Neighbor and pin stiffness
- Control parameters for both Standard and DSR methods
- Various input types (step, ramp, sine)

You can observe:
- Real-time agent states
- Deformation and tracking history
- Time series of agent positions
- Key metrics like settling time and stability conditions

Feel free to adjust parameters and observe how both methods perform under different conditions.