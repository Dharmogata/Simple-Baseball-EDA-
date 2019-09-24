
# Overview

This repo contains the projects for the Baseball analytics from simple baseball-EDA for NL cy young conteders pitching patterns strategy to MLB and KBO winning odds prediction model.

---




## Dataset

#### Statcast

Project description

baseball_scraper is a Python package for baseball data analysis. This package scrapes baseball-reference.com and baseballsavant.com so you don’t have to. So far, the package performs four main tasks: retrieving statcast data, pitching stats, batting stats, and division standings/team records. Data is available at the individual pitch level, as well as aggregated at the season level and over custom time periods.

Status
https://travis-ci.com/spilchen/baseball_scraper.svg?branch=master
Statcast
data include pitch-level features such as Perceived Velocity (PV), Spin Rate (SR), Exit Velocity (EV), pitch X, Y, and Z coordinates, and more. The function `statcast(start_dt, end_dt)` pulls this data from baseballsavant.com.

Pull advanced metrics from Major League Baseball’s Statcast system. Statcast data include pitch-level features such as Perceived Velocity (PV), Spin Rate (SR), Exit Velocity (EV), pitch X, Y, and Z coordinates, and more. The function statcast(start_dt, end_dt) pulls this data from baseballsavant.com.

https://pypi.org/project/baseball-scraper/

#### KBO
You can download the full training set  I used [here](https://www.koreabaseball.com)  

#### MLB
You can download the full training set  I used [here](https://www.mlb.mlb.com/stats)  


## Software Requirements
If using Linux or Mac, you can use [this conda environment file](lane_environment.yml). In the command line, use `conda env create -f lane_environment.yml` and then `source activate lane_environment` to use the environment. 



This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute an [iPython Notebook](http://ipython.org/notebook.html)

We recommend students install [Anaconda](https://www.continuum.io/downloads), a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.



I recommend users install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.
