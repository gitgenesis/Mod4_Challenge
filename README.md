# Mod4_Challenge
Columbia Bootcamp Module 4 Challenge

# Analyzing Portfolio Risk and Return

This program is designed to evaluate four new investment options for inclusion in the client portfolios for our imagined FinTech investing platform. The purpose of the program is to take a large collated data set and make sense of what we can glean from that data. This includes consdering returns, risk facors, sensitivty to the market in general. Through this program we are able to pare down our choices to the most suitable, dive deeper upon those options, and ultimately recommend which fund we feel would be most suitable to be added to our investing platform.

For additional reference, whale_navs.csv covers the window from October 2014 through September 10th of 2020 for the four funds and market index, listing the daily closing prices as the tracked factor. This data file is located within the Resources sub-folder, and is the data we are currently using for analysis.

---

## Technologies

Within this program, we will make use of the following external python modules:
  -- pandas
  -- matplotlib
  -- Pathlib
  -- Numpy
  
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

At the beginning the *risk_return_analysis.ipynb* file the technologies are calling in with this code:

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