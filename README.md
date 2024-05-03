# Research-Method
# Environmental Impact of Diets

This repository contains the code and interactive visualization developed as part of the coursework for analyzing the environmental impact of different diets—vegan, vegetarian, fish-based, and meat-based—on parameters such as greenhouse gas emissions, land use, water use, eutrophication, and biodiversity loss.

## Overview

The project uses data from the EPIC-Oxford cohort to analyze dietary impacts on the environment. The key focus is to compare the environmental effects of various diets and provide a visual representation through an interactive treemap visualization.

## Repository Structure

- `src/` - Contains all source codes used for the analysis.
- `data/` - Contains the datasets used in the analysis.
- `docs/` - Contains the interactive treemap visualization and additional documentation.
- `README.md` - Provides an overview and guidance on how to use the repository contents.

## Interactive Treemap Visualization

The interactive treemap is built using Plotly and provides a detailed view of greenhouse gas emissions across different diets, segregated by age group and sex. This visualization helps in understanding which diet groups contribute most to environmental degradation.

### How to View

- Navigate to the `docs/` directory.
- Open the `interactive_treemap.html` file in a web browser to view the visualization.
- Interact with the treemap by hovering over different sections to see detailed emissions data.

## Source Code

The source code used for analysis and generating the treemap is located in the `src/` directory. Here's what each file does:

- `data_processing.py` - Script for cleaning and preparing the data.
- `visualization.py` - Script for generating the interactive treemap visualization.

### Requirements

- Python 3.x
- Plotly
- Pandas
- Numpy

To install the necessary Python packages, run the following command:

```bash
pip install plotly pandas numpy

Usage
To run the scripts, navigate to the src/ directory and execute the following
python visualization.py



