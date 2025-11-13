# Kaya Identity, CO₂ Emissions Decomposition and Predictive Modelling

## Overview

This project analyzes the drivers of global CO₂ emissions using the Kaya Identity and the Log-Mean Divisia Index (LMDI). The goal is to break down historical emissions into their underlying components and then run simple predictive experiments by varying carbon-intensity trends.

The workflow includes:
- Cleaning and merging global datasets
- LMDI decomposition of population, GDP per capita, energy intensity, and carbon intensity
- Computing long-run average growth rates
- Modelling future emissions by adjusting carbon-intensity trends
- Visualising historical and simulated behaviours

## Motivation

CO₂ emissions are determined by four structural factors:
- **Population**
- **GDP per capita**
- **Energy intensity** (energy per unit of GDP)
- **Carbon intensity** (CO₂ per unit of energy)

Historically, carbon intensity improves very slowly, yet it is crucial for achieving climate targets. This project aims to quantify each factor's influence and determine how much carbon intensity must improve moving forward.

## Key Questions

- Which factor contributes the most to emissions growth?
- Has energy intensity improved fast enough to offset economic expansion?
- What carbon-intensity trend is required to meet future climate goals?
- Are historical trajectories remotely sufficient?

## Methodology

### 1. Data Acquisition
Global datasets (GDP, population, substituted energy, CO₂ emissions) are merged on year and cleaned for consistency.

### 2. LMDI Decomposition
For each 10-year interval, the following effects are computed using LMDI, allowing a clean attribution of historical CO₂ changes:
- Population effect
- GDP per capita effect
- Energy intensity effect
- Carbon intensity effect

### 3. Growth Rate Estimation
Each Kaya component's long-run growth rate is estimated and used for scenario modelling.

### 4. Carbon-Intensity Scenarios
Population, GDP per capita, and energy intensity are kept on historical trend. Carbon intensity is varied to determine the required improvement rate to hit climate targets.

## Results (Summary)

- **GDP per capita** is the dominant positive driver of CO₂ increases
- **Energy intensity** improves over time but not enough to offset growth
- **Carbon intensity** is the slowest-improving factor and a major bottleneck

Scenario modelling shows that meeting ambitious climate targets requires carbon intensity to decline significantly faster than historical averages.
