# PFDA-Assignment
Programming for Data Analysis

**Software Used**
This project was done on Jupyter Notebooks using Python 3.11.15. on the editor Visual Studio Code V 1.75.1. It was used to produce both the code and this README.md file.

The dataset is available from the machine learning repository [Kwaggle](https://www.kaggle.com/datasets/saife245/english-premier-league)
It provides an individual dataset for each year of the Premier League from 2000/01-2019/20. However it also has a singular dataset called [final_dataset.csv](https://github.com/Kevin002023/PFDA-Assignment/blob/main/Premier_league_stats/Datasets/final_dataset.csv) which is an amalgamation of all season. This is the one used for this project.

The packages I used are;

````
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np
from IPython.display import Markdown as md

````
Pandas allows you to manipulate the dataset as a dataframe. It was used to import the dataset, set up a dataframe, validate the values and then for aggregation and grouping of specific variables. I made extensive use of the Pandas documentation which can be found [here](https://pandas.pydata.org/pandas-docs/stable/getting_started/index.html)

NumPy was used for mathematical operations and when working with arrays/matrices. Its documentation can be found [here](https://numpy.org/doc/stable/)

Matplotlib is an extension of NumPy and was used to present the data in plots. Its documentation is [here](https://matplotlib.org/stable/index.html)


The Markdown extension within the IPython package was used in order to display the value of variables within markdown cells. Jupyter notebook does not have this functionality at this time. The extension facilitates this. 