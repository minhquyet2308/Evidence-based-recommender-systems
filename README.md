# Evidence-based-recommender-systems
The implementation of the evidence-based recommender systems (ERS) for high-entropy alloys (HEAs) contains source codes in Python programming language and demo data sets of the project.

# Overview

The ERS is a comprehensive independence testing projects including source code of the recommender system, examples using ipython notebooks and small data sets to demo the implementation. These tests contain a basic example to show the commender system's usage and an example to explain the method to evaluate the recommender system using an experiment with k-folds cross-validation.

# Repo Contents

* [code](code): ipython notebook example
* [code/ers](code/ers): python source code of the recommender system
* [data](data): demo data set of the project
* [output](output): output files contain ranking indices of HEAs in test set of each cross-validation and a figure show the distribution of the ranking indices

# System Requirements

## Hardware Requirements

The project contains a simplified version of our proposed recommender system, which are deployed on a standard computer. However, the version requires is time-consuming as the number of data instances or the number of elements increase.

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

# Installation Guide

To install the project, the [Anaconda program](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjjtdOynoDvAhVFE6YKHQWgBDsQFjABegQIBhAD&url=https%3A%2F%2Fdocs.anaconda.com%2Fanaconda%2Finstall%2F&usg=AOvVaw0Y7hdNB3U4QdhBqCbBWwGJ) is required to install in advanced

```
git clone https://github.com/minhquyet2308/Evidence-based-recommender-systems.git
cd Evidence-based-recommender-systems/
conda create --name myenv --file requirements.txt
conda activate myenv
```

# Demo

To run the demo of the project in folder [code](code), we activate the conda environment installed in the previous step and start the jupyter notebook

```
conda activate myenv
cd Evidence-based-recommender-systems
jupyter-notebook
```

Expected output of each example is shown in coressponding ipython file. The runtimes of the [first example](code/basic_example.iynb) and the [second example](code/evaluate_recommendation_performance_using_k_folds) are about 15 minutes.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4557463.svg)](https://doi.org/10.5281/zenodo.4557463)