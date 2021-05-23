# Exploring-the-Evolution-of-Tensorflow

Exploring the Evolution of Tensorflow with github. 

![Alt Text](https://github.com/aayanmaity/Exploring-the-Evolution-of-Tensorflow/blob/main/dataset/tensorflow_new.png)

## Project 

Version control repositories like CVS, Subversion or Git can be a real gold mine for software developers. They contain every change to the source code including the date (the "when"), the responsible developer (the "who"), as well as a little message that describes the intention (the "what") of a change.

In this notebook, we will analyze the evolution of `Tensorflow`.

Tensorflow is one of the widely used libraries for implementing Machine learning and Deep Learning algorithms involving large number of mathematical operations. Tensorflow was developed by Google and it’s one of the most popular Machine Learning libraries on GitHub. Our dataset at hand contains the history of tensorflow development of 5 years (late 2015 - mid 2021). We get some insights into the work of the development efforts by -

* Identifying the TOP 10 contributors.
* Visualizing the commits over the years.

## Data Collection 

The dataset was created by using the command `git log --encoding=latin-1 --pretty="%at#%aN"` in May 2021. The `latin-1` encoded text output was saved in a header-less CSV file. In this file, each row is a commit entry with the following information:

* `timestamp`: the time of the commit as a UNIX timestamp in seconds since 1970-01-01 00:00:00 (Git log placeholder `"%at"`)
* `author`: the name of the author that performed the commit (Git log placeholder `"%aN"`)

The columns are separated by the number sign `#`. 

The complete dataset is in the datasets/ directory. It is a csv file named `Tensorflowhistory.csv`.

## Tools used:

Code: Python Version: 3.7

For data wrangling and visualization: Pandas

## Tasks:

* Identifying the TOP 10 contributors.
* Visualizing the commits over the years.

