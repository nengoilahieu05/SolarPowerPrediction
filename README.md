Project Overview

This project is inspired by the work in
https://github.com/ColasGael/Machine-Learning-for-Solar-Energy-Prediction
, which frames solar energy prediction as a regression problem using temporally mixed data.

However, mixing observations across time breaks the sequential dependency that is fundamental to solar energy generation. Weather dynamics, diurnal cycles, and seasonal patterns are inherently time-dependent, and treating them as independent samples leads to information leakage and unrealistic performance estimates.

To address this limitation, this project reformulates solar energy prediction as a true time-series problem.
All features are handled sequentially, preserving temporal order throughout preprocessing, model training, and evaluation.

The goal of this project is to provide a more realistic and deployment-ready framework for solar energy forecasting by fully respecting the sequential nature of the data.
