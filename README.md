# District Heating Network Optimization

Project developed at **KTH Royal Institute of Technology** within the course *Practical Optimization of Energy Networks*.

## Overview

This project investigates the design and optimization of a **district heating network** and its integration with a broader energy system model.

The analysis combines **network optimization** with **heat-generation dispatch**, considering:

- Multiple heat consumers and producers
- Different pipe sizes and network configurations
- Thermal distribution losses
- Heat-generation technologies
- Operating and investment costs
- CO₂ emission costs

The project uses **DHNx** for district heating network optimization and **oemof.solph** for energy system modeling and dispatch optimization.

## Methodology

The project is divided into five main steps.

### Step 1 – Base District Heating Network

- Model a district heating network with five consumers and two heat producers
- Evaluate different pipe types
- Optimize network topology and pipe selection
- Consider investment costs, operational costs, capacities, and thermal losses

### Step 2 – Network Expansion

- Expand the system to ten consumers and five heat producers
- Introduce additional pipe diameters
- Include a heat pump among the generation technologies
- Evaluate how system scale affects network topology, costs, losses, and producer utilization

### Step 3 – Energy System Optimization

- Model the five heat producers in **oemof.solph**
- Aggregate heat demand from the consumer profiles
- Define technical and economic parameters for each technology
- Optimize heat-generation dispatch to meet total demand

### Step 4 – DHNx and oemof Integration

- Integrate the district heating network with the energy system model
- Add network thermal losses to the aggregated heat demand
- Re-optimize heat-generation dispatch considering distribution losses
- Evaluate the effect of network losses on generation requirements and system operation

### Step 5 – Environmental Optimization

- Extend the energy system model with **CO₂ emission costs**
- Compare:
  - total operating cost + emission cost
  - emission-cost-only scenarios
- Analyze the trade-off between economic and environmental dispatch

The five-step structure follows the project specification directly.

## Repository Structure

The repository is organized into **different folders and Jupyter Notebooks corresponding to the individual project steps**.

Each step contains the relevant:

- Python notebooks
- Input data
- Model configuration files
- Generated figures
- Intermediate and final outputs

The step-by-step organization makes it possible to follow the development from the initial district heating network model to the integrated energy-system and environmental optimization analyses.

The **main outcomes and comparisons** can be found in the **final PDF presentation** included in the repository.

## Tools and Methods

**Python · Jupyter Notebook · DHNx · oemof.solph · District Heating Optimization · Energy System Modeling · Heat Generation Dispatch · Thermal Loss Analysis · Techno-Economic Optimization · CO₂ Cost Modeling**

## Project Material

The repository contains:

- Step-specific folders and Jupyter Notebooks
- District heating network input data
- Heat-demand profiles
- Energy-system model inputs
- Optimization outputs and figures
- Final PDF presentation with the main project outcomes

## License

Copyright © 2025. All rights reserved.

This repository is made publicly available for **portfolio and academic viewing purposes only**. No permission is granted to copy, modify, distribute, or reuse the original code, analyses, models, presentations, or other materials developed by the project authors without prior written permission.

Third-party datasets, software libraries, input data, and externally sourced materials remain subject to the rights, licenses and restrictions of their respective owners.

## Author

**Michelangelo Inzerilli**  
EIT InnoEnergy, KTH Royal Institute of Technology and Universitat Politècnica de Catalunya