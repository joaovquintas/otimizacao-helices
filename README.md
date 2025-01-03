
# Propeller Optimization with Genetic Algorithms

This repository contains the code and files necessary to optimize propellers using genetic algorithms and the QPROP tool.

## Directory Structure

- inputFiles
  - APC12x6.txt
  - propdrive2.txt
  - results12x6PY.txt
  - solar1run.txt
- optimization.ipynb
- qcon.def
- qprop.exe

## Dependencies

The required libraries are:

- numpy
- matplotlib
- deap

Install the dependencies using:

```bash
pip install numpy matplotlib deap
```

## How to Run

### Step 1: Propeller Optimization

1. Open the `optimization.ipynb` file in a Jupyter Notebook environment.
2. Run all the cells to perform the propeller optimization and generate comparison plots.

### Step 2: Visualizing the Results

The plots comparing the performance data of the original and optimized propellers will be generated at the end of the notebook execution.

## File Descriptions

- **inputFiles/APC12x6.txt**: Input file with data for the original propeller.
- **inputFiles/propdrive2.txt**: Motor configuration for QPROP.
- **inputFiles/results12x6PY.txt**: Performance results for the original propeller.
- **inputFiles/solar1run.txt**: Simulation configuration for QPROP.
- **optimization.ipynb**: Notebook containing the optimization and visualization code.
- **qcon.def**: Configuration file required for QPROP.
- **qprop.exe**: QPROP executable.

## Features

### Genetic Algorithm

The notebook includes the configuration and execution of the genetic algorithm, which optimizes the number of blades, the chord, and the twist angle of the propeller to maximize propulsive efficiency.

### Visualizing the Results

The notebook also contains code to generate graphs comparing the original and optimized propellers in terms of propulsive efficiency, shaft power, thrust, torque, and overall efficiency.

## Author

- João Vitor Quintas dos Santos

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
