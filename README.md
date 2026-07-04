# Rebuilding After Wildfire: Externalities, Strategy, and the Compliance Problem in Maui
A game-theoretic analysis of post-wildfire rebuilding decisions in Lahaina, Maui, combining spatial externalities, Monte Carlo simulation, and an interactive GIS visualization to examine how compliance costs, wildfire risk, and policy incentives shape resilient recovery.

# Research Question
Under what conditions do homeowners comply with wildfire-resilient rebuilding standards, and how do compliance costs, enforcement mechanisms, and spatial spillovers affect equilibrium rebuilding outcomes?

# Methods
The analysis combines several complementary approaches:

Two-player game-theoretic model
Nash equilibrium analysis
Monte Carlo simulation (10,000 draws)
Expected-loss calibration using representative Lahaina housing values
Sensitivity analysis
Interactive GIS visualization using Leaflet.js and Turf.js
Repository Contents
Manuscript

Contains the complete paper submitted for publication, including all figures and references.

**Simulation**
Implements the Monte Carlo simulation used throughout the paper.

The simulation evaluates thousands of possible rebuilding scenarios under varying assumptions regarding:

wildfire probability
compliance costs
mitigation effectiveness
enforcement probability
expected sanctions
behavioral discounting

Outputs include:

Net compliance benefits
Nash equilibrium classifications
Sensitivity analyses
Publication-quality figures
Interactive Model

The interactive application allows users to explore the model spatially by adjusting:

Compliance cost
Wildfire probability
Mitigation effectiveness
Enforcement probability
Expected sanctions

The application visualizes how localized rebuilding decisions influence neighboring parcels through wildfire spillover effects.

Running the Project
Requirements
R

Packages:

tidyverse
ggplot2
dplyr
Web Application

The interactive model is written in:

HTML
CSS
JavaScript
Leaflet.js
Turf.js

No installation is required beyond a modern web browser.
