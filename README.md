# VERTEX - Vibration Education Research Table Experiment

## Overview

This repository contains materials for the VERTEX project, a vibration education research table experiment. The workspace includes data files collected from vibration tests and the Arduino/embedded code used to interface with the experiment hardware.

## Repository Structure

- `VERTEX.ipynb` - Jupyter notebook for analysis, visualization, and experimentation with vibration data.
- `data/` - Dataset files from various tests and experiments.
- `vertex_code/vertex_code.ino` - Arduino sketch for controlling or acquiring data from the vibration table hardware.

## Data Files

The `data` folder contains several CSV files with experiment results, such as:

- `flicktest.csv`
- `flicktest2.csv`
- `shaketest.csv`
- `shaketestx.csv`
- `titanic3.csv`
- `output.csv`
- Multiple `withola*.csv` datasets

## Getting Started

1. Open `VERTEX.ipynb` in Jupyter Notebook or JupyterLab.
2. Review the data files in the `data/` directory.
3. Use the notebook to explore the vibration datasets and run analysis.

## Embedded Code

The `vertex_code/vertex_code.ino` file contains the Arduino sketch for the experiment. Use the Arduino IDE or compatible tools to upload this sketch to the vibration table controller hardware.

