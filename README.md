# Programming for Data Analysis Project ATU 2023

This repository is my submission for the PROGRAMMING FOR DATA ANALYSIS project 2023 as part of the Higher Diploma in Computing and Data Anyltics at Atlantic Technological University. The repository contains the Jupyter Notebook PFDA-Assignment.ipynb, a folder called Premier_leage_stats where I have downloaded the original dataset I was using to. 

## Project Instruction
- Choose a real-world phenomenon that can be measured and for which you could
collect at least one-hundred data points across at least four different variables.
- Investigate the types of variables involved, their likely distributions, and their
relationships with each other.
- Synthesise/simulate a data set as closely matching their properties as possible.
- Detail your research and implement the simulation in a Jupyter notebook – the
data set itself can simply be displayed in an output cell within the notebook.

## Software Used
This project was done on Jupyter Notebooks using Python 3.11.15. on the editor Visual Studio Code V 1.75.1. It was used to produce both the code and this README.md file.

The original dataset used is available from the machine learning repository [Kwaggle](https://www.kaggle.com/datasets/saife245/english-premier-league)
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

## Contents of Repository
- This Readme file
- PFDA-Assignment.ipynb notebook which contains all of the research, analysis, and synthesis of the new data.
- Premier_league_stats folder containing datasets for each year of the premier league and an overall dataset called final_dataset.csv which was used for this project.
- Images folder, where all graphs are saved to.


## References

References are noted in the section in which they are used and are listed at the end of the notebook. There are some references listed which are not used directly in the notebook but which were used to gain an understanding of the topics involved.