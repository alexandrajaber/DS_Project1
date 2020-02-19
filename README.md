# Wine Review Analysis
A Udacity Data Science NanoDegree Project (1)


## Table of contents

- [Installations](#installations)
- [Project Motivation](#project-motivation)
- [File Description](#file-description)
- [Project Overview](#project-overview)
- [CRISP-DM](#crisp-dm)
- [Licensing, Authors and Acknowledgements](#licensing-authors-and-acknowledgements)


## Installations

Python version: Python 3.7.3

Packages needed:

  - import numpy as np
  - import pandas as pd
  - import matplotlib.pyplot as plt
  - from sklearn.linear_model import LinearRegression
  - from sklearn.model_selection import train_test_split
  - from sklearn.metrics import r2_score, mean_squared_error
  - import seaborn as sns
  - from sklearn.neighbors import NearestNeighbors
  - from scipy.sparse import csr_matrix
  - from sklearn.decomposition import TruncatedSVD
  - %matplotlib inline


## Project Motivation

For this project, I was interestested in using Wine Reviews data from 2017 to better understand:

  1. Which countries have the highest rated and the lowest rated wines?
  2. Which countries have on average the most expensive and the least expensive wines?
  3. The more expensive the wine the better the rating?  
  4. What variables are top indicators of wine price? (Coming soon...)
 
  
The data was scraped from WineEnthusiast during the week of June 15th, 2017. I have used the data files available on the [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews) Dataset posted and shared by zackthoutt.


## File Description

There is 1 notebook available here to showcase work related to the above questions. The notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title. Markdown cells were used to assist in walking through the thought process for individual steps.


## Project Overview

This project is part of one of the deliverables for the Data Science for Enterprice Nanodegree offered by Udacity. The aim is to explore a random dataset, pose a few business questions and find answers using newly acquired Python skills. I have taken it a step further by incorporating a recommender system that would recommend what wine I should order based on my personal preferences.

You can find more information on my findings on my blog post [here](https://medium.com/@alexandra1895/wine-review-analysis-3b91277d23b5).

## CRISP-DM

#### Business understanding

outline the questions you will answer along with why they are relevant and important

#### Data understanding

provide some stats about your data like mean and std deviations of the different features

#### Data preparation

show how you clean and prepare the data. It is important to document and not just write the code


#### Data modeling

if you created a model this is the section you would put it in or the analysis

#### Results evaluation

conclusion and discussion

## Licensing, Authors and Acknowledgements

Must give credit to [Wine Reviews](https://www.kaggle.com/zynicide/wine-reviews) for the data. You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/zynicide/wine-reviews). Otherwise, feel free to use the code here as you would like!

