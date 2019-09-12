
# Overview

This repo contains the projects for the Baseball analytics from simple baseball-EDA for NL cy young conteders pitching patterns strategy to MLB and KBO winning odds prediction model.

---




## Dataset
#### KBO
You can download the full training set  I used [here](https://www.koreabaseball.com)  

#### MLB
You can download the full training set  I used [here](https://www.mlb.mlb.com/stats)  


## Software Requirements
If using Linux or Mac, you can use [this conda environment file](lane_environment.yml). In the command line, use `conda env create -f lane_environment.yml` and then `source activate lane_environment` to use the environment. 

Alternatively, you can use the following:
* Python 3.5 or higher. Most of the included code also works in Python 2.7, although the pickle files used for the training images and labels are encoded for use in Python 3 and would need to be loaded and restructured to work in Python 2.7. I would suggest downloading with Anaconda as you will get some of the below

* seaborn
* matplotlib
* moviepy
* numpy+mkl
* scikit-learn
* scipy

