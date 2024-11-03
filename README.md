# agkrish-assignment-6
# CS506 Assignment 6 - Linear Regression

This project is part of CS506, exploring how randomness influences linear regression results when there is no actual relationship between two variables \(X\) and \(Y\). The goal is to create an interactive webpage that allows users to modify parameters such as sample size, noise, and number of simulations. The user can observe how these changes affect the slope and intercept of a regression model and visualize the results through scatter plots and histograms.

## Project Overview

The interactive webpage allows users to:
- Input parameters such as:
  - **Sample Size (N)**: Number of data points in the dataset.
  - **Mean (\(\mu\))**: Mean of the normal error term added to \(Y\).
  - **Variance (\(\sigma^2\))**: Variance of the normal error term.
  - **Number of Simulations (S)**: Number of datasets to simulate.
- Generate:
  1. **Scatter Plot**: Showing the generated random dataset and the fitted regression line (where there is no real relationship between \(X\) and \(Y\)).
  2. **Histograms**: Overlapping histograms of the slopes and intercepts from the simulated datasets, with the first dataset’s slope and intercept highlighted.
  3. **Proportions of More Extreme Values**: Showing the proportion of slopes and intercepts more extreme than those in the first dataset.

## Demo Video

A short 1-2 minute demo video of the project can be found here:  
[![Demo Video][(https://img.youtube.com/vi/YourVideoIDHere/0.jpg)](https://youtu.be/YourVideoIDHere)
](https://youtu.be/CaqZ5Tqk5qo)
In the demo, I explain the results of different simulations, show the impact of changing parameters like sample size and noise level, and discuss how randomness influences the fitted regression line.

## Getting Started

### Prerequisites

To run this project, you need to have Python 3.x and the following Python packages installed:
- `Flask`
- `matplotlib`
- `numpy`
- `scikit-learn`
  
git clone https://github.com/yourusername/linear-regression-assignment.git
cd linear-regression-assignment

To install the required packages, use the following command:

```bash
pip install -r requirements.txt
```
Run the flask app

```bash
python app.py
