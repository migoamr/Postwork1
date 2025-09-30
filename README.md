Bacterial Growth Simulation
Overview
Simulates bacterial population growth using exponential and logistic models. Exports all data to CSV for analysis.

Quick Start
python
# Run in Jupyter Notebook
# All results save to 'bacterial_growth_results/' folder
Output Files
CSV Data: Time series, summary stats, model comparisons

Plots: Growth curves (linear & log scales)

Metadata: Simulation parameters

Key Features
Exponential growth: N(t) = N₀ * exp(r * t)

Logistic growth with carrying capacity

Multiple growth rate comparison

Automatic CSV export

Doubling time calculations

Models
Exponential: Unlimited growth under ideal conditions

Logistic: Realistic growth with population limits

Parameters (Customizable)
python
N0 = 100      # Initial population
r = [0.2, 0.5, 0.8, 1.2]  # Growth rates
t_max = 10    # Simulation time (hours)
K = 10000     # Carrying capacity
Requirements
bash
pip install numpy matplotlib pandas jupyter
Run the notebook and check the bacterial_growth_results folder for all outputs.
