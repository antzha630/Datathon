MLDS Datahack 2025 Project

Overview
This repository contains the code, data, and results for our participation in the MLDS Datahack 2025, where we developed machine learning models to forecast wind speeds and optimize insurance pricing strategies for the simulated city GANopolis.

Project Objectives
Wind Speed Forecasting: Predict wind speeds for GANopolis using SARIMA and random walk models.

Insurance Pricing Optimization: Translate wind speed forecasts into damage predictions and optimize insurance prices to maximize profits.

Repository Contents
code.py: Python scripts for data preprocessing, model development (SARIMA and random walk), forecasting, and visualization.

submission.csv: Final predictions and insurance prices submitted for the competition.

slides.pptx: Presentation summarizing our approach, findings, and recommendations.

Event Data Files (event_1.csv, event_2.csv, etc.): Simulated event data used for forecasting.

Key Features
SARIMA Model: Achieved an MSE of 0.08 for wind speed forecasting by incorporating trend and seasonal patterns.

Exponential Random Walk Model: Used to predict damages with an MSE of 0.09.

Interactive Pricing Function: Implemented an exponential pricing formula to optimize insurance prices based on predicted wind speeds.
