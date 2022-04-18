# Mod4_Challenge
Columbia Bootcamp Module 4 Challenge

# Analyzing Portfolio Risk and Return

evaluating four new investment options for inclusion in the client portfolios. Legendary fund and hedge-fund managers run all four selections. (People sometimes refer to these managers as whales because of the large amount of money that they manage). This program help determine the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.

We produce a Jupyter notebook that contains your data preparation, analysis, and visualizations for key risk and return metrics. 
Key elements in this assignment:
- A single DataFrame imported from a CSV file that has a DateTimeIndex.
- A risk analysis of the assets that the DataFrame contains vs. the S&P 500. 
- This analysis include risk-return metrics, including the daily returns, standard deviation, Sharpe ratio, and beta.
- An evaluation of each asset that uses rolling statistics to track the risk-reward behavior over time.

---

# Instructions 
Our quantitative analysis includes the following:

- Performance

- Volatility

- Risk

- Risk-return profile

- Portfolio diversification

---

## Technologies

Within this program, we will make use of the following external python modules:
  - pandas
  - matplotlib
  - Pathlib
  - Numpy
  
  Additionally, this program was created within a python v3.7 build, and its relevant dependencies.

---

## Installation Guide

To utilize this program, within your terminal you will have to install the required libraries. Within your terminal, input the following commands:

```python
pip install pandas
```

```python
pip install matplotlib
```

```python
pip install pathlib
```

```python
pip install numpy
```

Call *risk_return_analysis.ipynb*  with this code:

```
import pandas as pd
from pathlib import Path
import numpy as np
%matplotlib inline
```

---

## Usage

To operate this program, open up your terminal of choice and navigate to the directory in which you have downloaded the files within this repository. Open Jupyter Lab with the command: 

```python
jupyter lab
```  

This should open jupyter lab to the filepath in which you have the repo file, and you simply need double click the *risk_return_analysis.ipynb* file to open it. Upon opening, select the menu button with two right facing arrows at the top of the notebook, which will run the entire file. It will ask you to confirm you wish to restart the file, to which you will confirm. Wait a few moments for the program to operate as intended, and peruse the resulting data at your leisure. If you wish, simply skip to the end for my analysis of the preceding information. 

---

## Contributors

Drissa Compaore email: misterdrissa@gmail.com

## License

This code is created for educational purposes, and it usage therein has no commerical application. It is designated as free-use thusly, and shall remain as such.
