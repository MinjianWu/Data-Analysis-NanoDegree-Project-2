# Data-Analysis-NanoDegree-Project-2
Investigate US Gun Registration Data

The report will investigate the gun registration data in the US recorded by the FBI over the period of 1998 to 2017. The data will ba analysed in parallel with the US state-level census data, although most variables in the latter only have a maximum of two data points per state.

The gun data comes from the FBI's NICS (National Instant Criminal Background Check System). The NICS is leveraged to determine whether a prospective buyer is eligible to buy firearms or explosives. Gun shops call into this system to ensure that each customer does not have a criminal record or isn’t otherwise ineligible to make a purchase.

To gain insights from the datasets, we will ask the following questions and we will clean and analyse our data to try to answer them in the end of the report:

- Which states have been most profilic in gun numbers over the years?

- What census data are most associated with high gun per capita?

- What features are most associated with the highest profile state in guns?

Python packages utilised in this study:

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

from matplotlib.ticker import FormatStrFormatter

import seaborn as sns

import folium

from scipy.interpolate import InterpolatedUnivariateSpline

from scipy import stats

import statsmodels.stats.api as sms

import ssl

from urllib.request import urlopen

import json

from sklearn import preprocessing

from sklearn.metrics import mean_squared_error
