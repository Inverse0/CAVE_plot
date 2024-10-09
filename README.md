# CAVE: Concurrency-Aware Graph Processing on SSDs

This repository hosts the plotting code used in the paper "CAVE: Concurrency-Aware Graph Processing on SSDs".

## Repository Structure

- `data/`: Stores the raw results from experiments.
- `plot/`: Directory where generated plots are saved after running the notebooks.
- `Notebook files`: Contains Jupyter notebooks for generating plots based on the experiment data.

## Usage
- Modify the `graph` parameter within the notebooks to alter the device or graph used in the experiment analyses. More details are provided within each notebook.
- Run the notebook. If you encounter any formatting issues (such as font size), rerun the last cell to produce the correct plot.

## Requirements
- matplotlib
- numpy
- pandas

These packages are necessary for running the notebooks. Ensure they are installed in your environment before proceeding with the usage instructions.
