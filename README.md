\# Water Reservoir Storage Forecasting – Time Series Models



This repository contains an \*\*academic learning project\*\* focused on understanding how \*\*time series forecasting models\*\* are built, trained, and evaluated using real-world data. The project explores multiple statistical, machine learning, and deep learning approaches for predicting daily water reservoir storage levels.



The primary goal of this work is \*\*conceptual clarity and hands-on implementation\*\*, rather than claiming production-grade performance or deployment readiness.



\## Project Motivation



Time series forecasting behaves very differently from traditional supervised learning. This project was created to:



\* Understand how temporal data is structured and processed

\* Learn how different forecasting models interpret time-dependent patterns

\* Compare classical, ML, and deep learning approaches on the same dataset

\* Gain practical experience with model evaluation and error analysis



\## Models Explored



The following models were implemented to study their behavior and limitations:



\* \*\*SARIMAX\*\* – Classical statistical time series model

\* \*\*Prophet\*\* – Decomposition-based forecasting approach

\* \*\*XGBoost\*\* – Tree-based regression with engineered temporal features

\* \*\*LSTM\*\* – Recurrent neural network for sequential data

\* \*\*iTransformer\*\* – Transformer-based architecture for multivariate time series



Each model was trained and evaluated independently to observe how it learns temporal and feature-level patterns.



\## Dataset



\* \*\*Hydrological Data\*\*: Daily reservoir storage values

\* \*\*Meteorological Data\*\*: Temperature, wind speed, and precipitation

\* Data sources include publicly available datasets (Kaggle and NASA POWER)



The datasets were merged by date, cleaned, and converted into a continuous daily time series suitable for forecasting experiments.



\## Methodology (Learning-Oriented)



1\. Understanding the raw time series structure

2\. Handling missing values and date alignment

3\. Feature creation (lags, rolling statistics)

4\. Chronological train–test split

5\. Training different forecasting models

6\. Comparing predictions using standard error metrics



This workflow was followed mainly to understand \*\*why models behave differently\*\*, not to optimize for maximum accuracy.



\## Tools and Libraries Used



\* \*\*Language\*\*: Python

\* \*\*Libraries\*\*:



&nbsp; \* pandas, numpy

&nbsp; \* scikit-learn

&nbsp; \* statsmodels

&nbsp; \* prophet

&nbsp; \* xgboost

&nbsp; \* tensorflow/keras



\## Project Nature



\* Academic / self-learning project

\* Not intended for production or operational use

\* Focused on experimentation and understanding

\* Built to strengthen fundamentals of time series modeling



\## License



This repository is shared for \*\*educational purposes only\*\*.



