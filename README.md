# GEPSO
Code used for the article "Gradient Enhanced Particle Swarm Optimization Algorithm"

📁 Folder Structure

Matlab_Code/
This folder contains all the key MATLAB scripts required to run the GE-PSO algorithm:

| File                 | Description 
|----------------------|
| `testFunPD.mlx`      | Defines the **dynamic simulation** function used as the objective for optimization. 
| `PSO_J.mlx`          | Implements the **Gradient-Enhanced PSO algorithm**, calling `testFunPD` to evaluate each particle's fitness. 
| `PSO_Statistics.mlx` | Runs **multiple GE-PSO simulations**, compiles **statistical results**, and generates **visualizations** of both the optimization process and dynamic system behavior.
---

🚀 How to Run

1. Open MATLAB.
2. Navigate to the Matlab_Code/ directory.
3. Run the main analysis script:
    
    PSO_Statistics.mlx
    

This script will:
- Execute the GE-PSO algorithm multiple times.
- Collect and display statistical results (mean, best, worst).
- Plot swarm behavior.
- Plot system dynamics.
