# Pairs Trading Using Cointegration

This repository contains the resources and code necessary to understand and implement a pairs trading strategy using cointegration. The project includes a PowerPoint presentation and a Python notebook to guide you through the concepts and practical implementation.

## Table of Contents

- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)


## Introduction

Pairs trading is a market-neutral trading strategy that involves identifying and exploiting pricing inefficiencies between two correlated assets. This project uses cointegration to identify pairs of assets that have a long-term equilibrium relationship, allowing for more reliable trading signals.

## Project Structure

- `Pairs_Trading_Cointegration.ipynb`: The Jupyter notebook containing the code for the pairs trading strategy.
- `Pairs_Trading_Presentation.pptx`: A PowerPoint presentation explaining the concepts and methodology of the pairs trading strategy using cointegration.

## Dependencies

To run the code in this project, you will need the following Python libraries:

- numpy
- pandas
- statsmodels
- matplotlib
- seaborn

## Usage

Open the Jupyter notebook `Pairs_Trading_Cointegration.ipynb` to explore the code and run the cells step-by-step. The notebook covers the following steps:

1. **Data Collection**: Importing and preparing the data for analysis.
2. **Cointegration Testing**: Performing the Engle-Granger cointegration test to identify cointegrated pairs.
3. **Signal Generation**: Generating trading signals based on the cointegration relationship.
4. **Backtesting**: Evaluating the performance of the pairs trading strategy using historical data.

## Results

The results of the pairs trading strategy, including the performance metrics and visualizations, are documented in the Jupyter notebook. Additionally, the PowerPoint presentation provides a detailed explanation of the methodology and findings.


