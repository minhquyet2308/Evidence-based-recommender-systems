# Evidence-based-recommender-systems
The implementation of the evidence-based recommender systems (ERS) for high-entropy alloys (HEAs) contains source codes in Python programming language and demo data set of the work.

# Overview

The ERS is a comprehensive independence testing projects including source code of the recommender system, testing python notebooks and small data sets to demo the implementation. These tests contain a basic example to show the commender system's usage and an example to explain the method to evaluate the recommender system using an experiment with k-folds cross-validation.

# Repo Contents

* [code](code): ipython notebook example
* [code/ers](code/ers): python source code of the recommender system
* [data](data): demo data set of the project
* [output](output): output files contain ranking indices of HEAs in test set of each cross-validation and a figure show the distribution of the ranking indices

# System Requirements

## Hardware Requirements

The project contains a simple version of the system deployed in standard computer. However, it requires high computation cost and is time-consuming

## Software requirements

### OS Requirements

This package is supported for *macOS* and *Linux*. The package has been tested on the following systems:

* macOS: Mojave (10.14.6)
* Linux: CentOS 7

### Python Dependencies

The project mainly depends on the Python scientific stack

* scikit-learn
* scipy
* pandas
* numpy
* notebook
* matplotlib
* seaborn

The list of requirement package and their version are shown in details in the file [requirements.txt](requirements.txt)