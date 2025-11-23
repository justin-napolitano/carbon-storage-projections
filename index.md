---
slug: "github-carbon-storage-projections"
title: "carbon-storage-projections"
repo: "justin-napolitano/carbon-storage-projections"
githubUrl: "https://github.com/justin-napolitano/carbon-storage-projections"
generatedAt: "2025-11-23T08:19:42.936330Z"
source: "github-auto"
---


# Behind the Scenes of Carbon Storage Projections: Shipping CO2 Across the Atlantic

Hey there! I’m Justin Napolitano, and I want to take you on a little journey through one of my recent projects: modeling the economics and feasibility of shipping carbon dioxide from Europe to the United States. If you’re curious about climate tech, carbon capture, or just love nerding out with Monte Carlo simulations, this post is for you.

## Why I Started This

I’ve always been fascinated by how we can tackle climate change with technology and smart infrastructure. After publishing a report identifying potential US ports suitable for carbon imports, I found myself asking: what’s the actual economic value of shipping CO2 across the Atlantic? Is it feasible? How much could it cost annually?

Turns out, this question is more complex than it seems. Shipping CO2 isn’t just about distance — it involves dynamic variables like shipping capacity, port selection, trip duration, and fluctuating costs. To tackle this, I built a Monte Carlo simulation in Python that models these uncertainties and projects the annual shipping cost.

## What This Project Solves

The core problem here is uncertainty. Traditional cost estimates often use fixed values, which don’t capture the variability in real-world shipping logistics. By simulating a range of possible scenarios, my model helps stakeholders understand the potential economic scale and risks involved in carbon shipping.

This is crucial for policymakers, investors, and engineers who want to design effective carbon storage and transport infrastructure. Knowing the likely cost ranges helps in planning and prioritizing investments.

## How It’s Built

I used Jupyter Notebooks for development and documentation, leveraging Python’s scientific stack. The simulation randomly samples variables from normal distributions bounded by realistic minima and maxima:

- Shipping distances between various European origin ports and US terminal ports
- Shipping capacity of vessels (converted from LNG tanker data to supercritical CO2 equivalents)
- Round-trip shipping durations
- Cost of transport per ton (currently fixed, but planned to be randomized with better data)

The notebooks also include markdown reports explaining methodology, findings, and revisions. Transparency is key — I even published corrections when I found a decimal conversion error that inflated earlier cost estimates.

## Interesting Implementation Details

- **Monte Carlo Simulation**: Instead of a single deterministic output, the model runs thousands of iterations with random inputs to generate a distribution of possible outcomes. This approach better reflects real-world uncertainty.

- **Data Sources**: I adapted LNG shipping capacity data to estimate CO2 transport volumes, which required careful unit conversions and assumptions about supercritical CO2 properties.

- **Port Selection**: The model accounts for variable ports of origin and destination, recognizing that different routes impact costs and feasibility.

- **Error Correction & Transparency**: I discovered a decimal error in distance conversion early on, which led to inflated cost projections. Publishing the code and reports openly allowed me to correct this quickly and maintain credibility.

## Why This Project Matters for My Career

Working on this project has deepened my expertise in environmental economics, data modeling, and transparent scientific communication. It’s a perfect blend of my interests in climate tech and software development.

Moreover, it demonstrates my commitment to rigor and openness — qualities that are essential for meaningful impact in energy and environmental research. Sharing my process and findings publicly not only helps the community but also strengthens my professional portfolio.

If you’re interested, the full project is on GitHub, complete with notebooks and detailed markdown reports. I hope this sparks more conversations and innovations around carbon capture and storage logistics.

Thanks for reading!

— Justin Napolitano