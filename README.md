# Adobe-GenSolve-Hackathon

## Overview

This project is designed to address complex curve analysis, including curve regularization, symmetry detection, and completion. Using a combination of mathematical techniques and computational geometry, the tool processes path data from CSV files, regularizes curves into standard shapes, and identifies symmetry properties. Additionally, it generates visual representations in SVG and PNG formats.

## Key Features

- **CSV Data Handling**: Read and interpret curve data from CSV files.
- **Curve Regularization**: Identify and regularize curves into standard geometric shapes (e.g., lines, circles, ellipses, polygons).
- **Symmetry Exploration**: Detect reflection and radial symmetries in curves.
- **Curve Completion**: Complete disconnected or partially incomplete curves.
- **Visual Representation**: Generate and save SVG and PNG visualizations of the curves and symmetries.
- **Evaluation Metrics**: Assess the performance of curve regularization, symmetry detection, and completion.

## Installation

To use this project, ensure you have the following Python packages installed:

- `numpy`
- `matplotlib`
- `scipy`
- `scikit-learn`
- `svgwrite`
- `cairosvg`

You can install the necessary packages using `pip`:

```bash
pip install numpy matplotlib scipy scikit-learn svgwrite cairosvg
