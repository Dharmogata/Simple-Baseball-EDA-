
# Overview

This repo contains the projects for the Baseball analytics from simple baseball-EDA for NL cy young conteders pitching patterns strategy to MLB and KBO winning odds prediction model.

---




## Dataset
#### KBO
You can download the full training set  I used [here](https://www.koreabaseball.com)  

#### MLB
You can download the full training set  I used [here](https://www.mlb.mlb.com/stats)  


## Software Requirements
If using Linux or Mac, you can use [this conda environment file](lane_environment.yml). In the command line, use `conda env create -f lane_environment.yml` and then `source activate lane_environment` to use the environment. This is a slightly modified environment from that used in Term of the Udacity SDCND. Please see the note on moviepy below.

Alternatively, you can use the following:
* Python 3.5 or higher. Most of the included code also works in Python 2.7, although the pickle files used for the training images and labels are encoded for use in Python 3 and would need to be loaded and restructured to work in Python 2.7. I would suggest downloading with Anaconda as you will get some of the below

* seaborn
* matplotlib
* moviepy
* numpy+mkl
* scikit-learn
* scipy

**Note: Depending on which versions of the above are downloaded, there may be an issue in moviepy when trying to generate the video file from `draw_detected_lanes.py`. If so, please navigate to the following on your computer (if using Anaconda): `Anaconda3/Lib/site-packages/moviepy/audio/io/readers.py`, and go to line 122, which should be changed to `reshape((int(len(result)/self.nchannels),`, i.e. adding to change the result of the division to an integer. I will also add a link to a conda environment in the near future in case that's easier.**
