# Project Overview

The aim of this project is to predict who will win basketball games in the NBA. The project involves web scraping NBA box scores from the 2022 NBA season. The end goal of this project is achieved by training a machine learning model to make predictions on NBA data that has already been collected (such as total games played, teams played, home games played, 3 point percentage, etc.)

This project is based on https://www.youtube.com/watch?v=egTylm6C2is&t=545s

**Project Steps**

* Scrape standings and box score data
* Clean up html with BeautifulSoup
* Parse the box scores to get a DataFrame
* Run feature selection to identify predictors
* Train an ML model
* Compute rolling predictors to improve the model

## Code

You can find the code for this project [here](https://github.com/krzxro/nba-game-predictor/blob/main/game-predictor.ipynb)

File overview:

* `get_data.ipynb` - download the box scores from basketball reference.
* `parse_data.ipynb` - clean the data to get a pandas DataFrame.
* `predict.ipynb` - make predictions using machine learning


# Prerequisites

To complete this project, a good understanding of the following is needed:

* Python syntax, including functions, if statements, and data structures
* Data cleaning
* Pandas syntax
* Using Jupyter notebook


## Installation

Install the following locally:

* JupyerLab
* Python 3.8+
* Python packages
    * pandas
    * scikit-learn
    * beautifulsoup4
    * playwright

## Data

Download the dataset from Basketball Reference.  

* Csv file of box scores [here](https://drive.google.com/uc?export=download&id=1YyNpERG0jqPlpxZvvELaNcMHTiKVpfWe).
