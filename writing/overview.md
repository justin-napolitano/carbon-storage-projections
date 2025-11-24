---
slug: github-carbon-storage-projections-writing-overview
id: github-carbon-storage-projections-writing-overview
title: 'Carbon Storage Projections: Analyzing CO2 Shipping Costs'
repo: justin-napolitano/carbon-storage-projections
githubUrl: https://github.com/justin-napolitano/carbon-storage-projections
generatedAt: '2025-11-24T17:08:57.716Z'
source: github-auto
summary: >-
  I’ve been diving into the logistics of carbon dioxide shipping with my GitHub
  project,
  [carbon-storage-projections](https://github.com/justin-napolitano/carbon-storage-projections).
  This repo is a collection of Jupyter notebooks dedicated to understanding the
  economic feasibility and cost projections for shipping carbon dioxide from
  Europe to ports in the United States. The goal? To shed light on the costs and
  resources needed to establish a robust carbon shipping infrastructure.
tags: []
seoPrimaryKeyword: ''
seoSecondaryKeywords: []
seoOptimized: false
topicFamily: null
topicFamilyConfidence: null
kind: writing
entryLayout: writing
showInProjects: false
showInNotes: false
showInWriting: true
showInLogs: false
---

I’ve been diving into the logistics of carbon dioxide shipping with my GitHub project, [carbon-storage-projections](https://github.com/justin-napolitano/carbon-storage-projections). This repo is a collection of Jupyter notebooks dedicated to understanding the economic feasibility and cost projections for shipping carbon dioxide from Europe to ports in the United States. The goal? To shed light on the costs and resources needed to establish a robust carbon shipping infrastructure.

## Why This Project Exists

Climate change is one of our biggest challenges, and finding effective ways to manage carbon emissions is critical. This project aims to provide a data-driven look at how feasible it is to transport CO2 across the Atlantic. By analyzing shipping costs and logistics, I hope to contribute to ongoing discussions about carbon management and potential solutions.

## Key Design Decisions

I went with Monte Carlo simulations to model various shipping variables. Here are some factors that make this approach compelling:

- **Dynamic Modeling**: The Monte Carlo method allows for an adaptive analysis of uncertainties in shipping costs.
- **Comprehensive Insights**: The simulations can incorporate factors like distance, capacity, and trip duration, giving a well-rounded view of logistics.

Breaking down the modeling provided a structured way to tackle complex problems. I also made sure to include visualizations and markdown reports, which help make the data more digestible.

## Tech Stack

Here’s what I used to bring the project to life:

- **Jupyter Notebook**: Perfect for interactive analysis and visualizations.
- **Python**: The backbone of my data processing and simulation.
- **Markdown**: Used for documentation and detailed reporting.
- **Key Libraries**:
  - `numpy`: For numerical operations.
  - `pandas`: To manage and manipulate data.
  - `matplotlib`: For creating robust visualizations.
  - `scipy`: To help with statistical calculations.

## Features

The main features of this repo include:

- **Monte Carlo Simulation**: Helps analyze dynamic variables in shipping.
- **Cost Analysis**: Detailed breakdowns of CO2 transport costs across the Atlantic.
- **Feasibility Studies**: Evaluates potential carbon shipping infrastructures.
- **Visual Reports**: Each analysis comes with visualizations to present findings clearly.

## Getting Started

If you want to dive into this project, here’s how to get set up:

### Prerequisites

- Python 3.7 or higher
- Jupyter Notebook installed

### Installation Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/justin-napolitano/carbon-storage-projections.git
   cd carbon-storage-projections
   ```
   
2. **(Optional) Create a virtual environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Use `venv\Scripts\activate` on Windows
   ```

3. **Install required packages**:
   ```bash
   pip install numpy pandas matplotlib scipy
   ```

### Running the Notebooks

To get started with the analyses, launch Jupyter Notebook:

```bash
jupyter notebook
```

Once you're in, you can explore various notebooks like:

- `shipping_projections.ipynb`: Monte Carlo projection of shipping costs.
- `shipping_carbon_feasibility.ipynb`: Feasibility study of shipping carbon.
- `carbon-storage-projects.ipynb`: Related carbon storage projects.
- `europe_ports.ipynb`: Data and analysis on European ports.

## Project Structure

Here's a quick glance at how the repo is organized:

```
carbon-storage-projections/
├── carbon-storage-projects.ipynb
├── europe_ports.ipynb
├── histogram.png
├── shipping_carbon_feasibility.ipynb
├── shipping_carbon_feasibility.md
├── shipping_carbon_feasibility_files/
├── shipping_projections.ipynb
├── shipping_projections.md
├── shipping_projections_files/
├── README.md
```

Each notebook contains detailed analyses, and supplementary files provide more context.

## Future Work / Roadmap

I've got several ideas for enhancing this project in the future:

- **Refine Cost Models**: I want to incorporate more accurate and updated data sources to make the simulations even more reliable.
- **Expand Simulation Parameters**: Additional shipping variables could provide a deeper analysis of feasibility.
- **Automated Testing**: I plan to implement tests to validate simulation outputs.
- **Interactive Dashboards**: Visualization dashboards would make exploratory analysis easy and user-friendly.
- **Broader Geographic Analysis**: It’d be cool to extend this research to other routes and scenarios involving carbon storage.

## Stay Updated

I’m always pushing to enhance this project and would love to share updates. You can follow along on social media—I'm on Mastodon, Bluesky, and Twitter/X. Keep an eye out for what’s coming next in the world of carbon shipping logistics!

So, whether you're interested in carbon management, logistics, or data analysis, I invite you to check out the repo, experiment with the notebooks, and let me know your thoughts!
