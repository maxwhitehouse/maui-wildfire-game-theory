# Rebuilding After Wildfire: Externalities, Strategy, and the Compliance Problem in Maui

A reproducible research project that develops a game-theoretic model of post-wildfire rebuilding decisions in Lahaina, Maui. The project combines game theory, Monte Carlo simulation, spatial externalities, and an interactive GIS application to examine how compliance costs, wildfire risk, and enforcement incentives influence rebuilding behavior following major wildfire disasters.

---

# Project Overview

The 2023 Lahaina wildfire highlighted the challenges of rebuilding communities while reducing future wildfire risk. Property owners often face significant costs associated with wildfire-resilient construction, while many of the resulting benefits extend beyond individual parcels through reduced wildfire exposure for neighboring properties.

This project models rebuilding as a local externality game between neighboring homeowners. The framework combines game theory, Monte Carlo simulation, and spatial visualization to examine how compliance costs, wildfire risk, behavioral responses, and enforcement mechanisms jointly determine equilibrium rebuilding outcomes.

---
# Repository Contents

```text
.
├── LICENSE                         # MIT License
├── README.md                       # Project documentation
└── maui-wildfire-game-theory.pdf   # Full research manuscript
```
---
# Research Question

> **Under what conditions do homeowners comply with wildfire-resilient rebuilding standards, and how do compliance costs, enforcement mechanisms, and spatial spillovers influence equilibrium rebuilding outcomes?**

---

# Methods

The analysis combines several complementary approaches.

- Game-theoretic modeling
- Nash equilibrium analysis
- Monte Carlo simulation (10,000 draws)
- Expected-loss calibration using representative Lahaina housing values
- Policy sensitivity analysis
- Interactive GIS visualization using Leaflet.js and Turf.js

---

# Manuscript

The repository includes the final research manuscript in PDF format.

The paper presents the complete theoretical framework, Monte Carlo simulation methodology, sensitivity analyses, figures, and references.

---

# Results

The baseline Lahaina calibration produces several key findings.

- Approximately **81%** of simulation draws result in non-compliant equilibrium outcomes.

- Approximately **19%** produce compliant equilibria.

- Compliance costs frequently exceed perceived mitigation benefits under representative post-disaster conditions.

- Stronger enforcement and reduced mitigation costs substantially increase compliance.

- Localized wildfire spillovers generate coordination failures in which individually rational rebuilding decisions reduce overall community resilience.

---

# Interactive Visualization

A live version of the interactive application is available through GitHub Pages.

https://maxwhitehouse.github.io/472_Final/

---

# Reproducibility

All figures reported in the manuscript are generated directly from the simulation framework contained within this repository.

The repository is organized so that the complete workflow—from simulation through figure generation and interactive visualization—can be reproduced from source.

---

# Future Work

Potential extensions include:

- Parcel-level adjacency networks
- Dynamic and repeated games
- Agent-based wildfire simulation
- Insurance market interactions
- Parcel-level GIS calibration
- Integration with wildfire fuel datasets
- Empirical validation using observed rebuilding behavior

---

# License

The source code contained in this repository is licensed under the MIT License.

The accompanying manuscript and documentation remain © Max Whitehouse.

---

# Acknowledgments

Advisor:

**Dr. John Woodill**

(https://johnwoodill.com/)
---

# Author

**Max Whitehouse**

B.S. Geography & Geospatial Science  
Minor in Economics

Oregon State University

Research interests include:

- Law & Economics
- Game Theory
- Environmental Economics
- GIS & Spatial Analysis
- Wildfire Policy
- Climate Adaptation


No installation is required beyond a modern web browser.
