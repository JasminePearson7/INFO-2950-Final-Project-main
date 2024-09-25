# INFO 2950 Final Project
 Bayne, Joos, Pearson Final Project INFO 2950

-- The original owner of the repository was unable to make it public, so I took the files and made it public here! If you are here to observe our project, I would suggest downloading everything and saving in a folder named "INFO-2950-Final-Project-main", then either use VS.Code or Jupyter to browse our project after importing the packages listed below!

import requests
from bs4 import BeautifulSoup

pandas as pd
import numpy as np
import time

import matplotlib.pyplot as plt
import seaborn as sns
import datetime

from sklearn.linear_model import LinearRegression, LogisticRegression
from sklearn.model_selection import train_test_split, KFold, cross_val_score
from sklearn.impute import SimpleImputer, SimpleImputer
from sklearn.compose import ColumnTransformer

import statsmodels.api as sm
import statsmodels.formula.api as smf

import duckdb

import plotly.express as px
import plotly.graph_objects as go

import re
from scipy.stats import pearsonr


