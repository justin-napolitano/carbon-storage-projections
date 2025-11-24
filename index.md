---
slug: github-carbon-storage-projections
title: Monte Carlo Simulation of Carbon Dioxide Shipping Costs from Europe to US Ports
repo: justin-napolitano/carbon-storage-projections
githubUrl: https://github.com/justin-napolitano/carbon-storage-projections
generatedAt: '2025-11-23T08:41:07.120972Z'
source: github-auto
summary: >-
  Analysis of shipping CO2 from Europe to US ports using Monte Carlo simulation to model cost
  uncertainties and logistical variables in carbon storage transport.
tags:
  - carbon-storage
  - monte-carlo-simulation
  - co2-transport
  - shipping-costs
  - python
  - climate-mitigation
seoPrimaryKeyword: carbon dioxide shipping cost simulation
seoSecondaryKeywords:
  - monte carlo simulation
  - co2 transport logistics
  - carbon storage projections
seoOptimized: true
topicFamily: datascience
topicFamilyConfidence: 1
topicFamilyNotes: >-
  The post centers on a Monte Carlo simulation for analyzing CO2 shipping costs, involving data
  inputs, probabilistic modeling, Jupyter notebooks, and Python code, which aligns very closely with
  the datascience family's scope including simulations, data analysis, and notebooks.
---

# Carbon Storage Projections: Monte Carlo Simulation of Shipping CO2 from Europe to US Ports

## Motivation

The transportation of carbon dioxide (CO2) from Europe to the United States for storage or industrial use is an emerging area of interest in climate mitigation strategies. Understanding the economic feasibility and cost implications of this shipping process is critical for stakeholders considering infrastructure investments and policy decisions.

This project addresses the lack of transparent, quantitative analysis on the annual cost of shipping CO2 across the Atlantic. It aims to provide a rigorous, reproducible framework to estimate these costs and assess the viability of different port options and shipping configurations.

## Problem Statement

Shipping CO2 involves complex logistics with many dynamic variables, including shipping distances, vessel capacities, port choices, and trip durations. Traditional deterministic models fail to capture the uncertainty inherent in these parameters.

This project uses Monte Carlo simulations to model these uncertainties, producing probabilistic cost projections rather than single-point estimates. This approach allows for better risk assessment and decision-making.

## Implementation Overview

### Data and Inputs

- Port locations in Europe and the US, including distances between them
- Shipping vessel capacities, converted from LNG tanker data to supercritical CO2 equivalents
- Cost of transport per ton, initially fixed but planned to be modeled as a distribution
- Trip durations and round-trip considerations

### Methodology

The core of the project is a Monte Carlo simulation implemented in Python within Jupyter Notebooks. Key features include:

- Random sampling of dynamic variables from normal distributions bounded by realistic minima and maxima
- Modeling of shipping infrastructure capacity based on academic sources (e.g., IEFE – Centre for Research on Energy and Environmental Economics and Policy)
- Correction of previous errors related to unit conversions, demonstrating the importance of transparency and reproducibility

### Notebooks and Reports

- `shipping_projections.ipynb`: Contains the main Monte Carlo simulation projecting annual shipping costs.
- `shipping_carbon_feasibility.ipynb`: Evaluates the feasibility of shipping carbon, revising earlier cost estimates.
- `carbon-storage-projects.ipynb`: Additional analyses related to carbon storage.
- `europe_ports.ipynb`: Data analysis focused on European port characteristics.

Each notebook is accompanied by markdown reports summarizing findings and methodology.

## Technical Details

- Python 3.7+ with libraries such as numpy, pandas, matplotlib, and scipy for statistical modeling and visualization
- Jupyter Notebook environment for interactive development and documentation
- Monte Carlo simulation framework sampling from distributions to capture uncertainty

## Lessons and Observations

- Initial cost estimates were significantly overstated due to a unit conversion error, highlighting the necessity of code transparency and reproducibility.
- Distance within Europe has a marginal effect on shipping cost variance; the major cost driver is the transatlantic crossing.
- Potential US ports closer to the Gulf of Mexico may reduce shipping costs by minimizing Caribbean navigation.

## Practical Use

This project serves as a reference model for engineers and analysts evaluating carbon shipping logistics. It provides a replicable methodology to update assumptions, incorporate new data, and explore different scenarios.

## Future Directions

- Incorporate more granular and dynamic cost data to refine transport cost distributions
- Extend the model to include additional ports and alternative shipping routes
- Develop automated validation tests for simulation outputs
- Create interactive dashboards for stakeholders to explore simulation results

---

This documentation aims to provide a clear, technical reference for returning developers and engineers to understand the project's scope, methodology, and implementation details without extraneous commentary or motivational language.

