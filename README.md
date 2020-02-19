# Machine Learning Tutorial Session

## Introduction

This is a set of tutorials for the Machine Learning Hands-on Advanced Tutorial Session (HATS). They are intended to show you how to build machine learning models in python (`Keras`/`TensorFlow`) and use them in your `ROOT`-based analyses. We will build event-level classifiers for differentiating VBF Higgs and standard model background 4 muon events and jet-level classifiers for differentiating boosted W boson jets from QCD jets.

## Main notebooks in this tutorial

 0. [`a-dataset-and-plot.ipynb`](a-dataset-and-plot.ipynb): reading/writing datasets from `ROOT` files with `uproot` and plotting with `matplotlib`
 1. [`b-dense.ipynb`](b-dense.ipynb): building, training, and evaluating a fully connected (dense) neural network in `Keras`
 2. [`b.1-dense-pytorch.ipynb`](b.1-dense-pytorch.ipynb): building, training, and evaluating a fully connected (dense) neural network in `PyTorch`
 3. [`b.2-dense-bayesian-optimization.ipynb`](b.2-dense-bayesian-optimization.ipynb): building, training, and evaluating a fully connected (dense) neural network in `Keras` and exploring hyperparameters
 4. [`c-conv2d.ipynb`](c-conv2d.ipynb): preprocessing, building, training, and evaluating a 2D convolutional neural network in `Keras` 

## Setup

There are multiple ways to run through this tutorial with varying levels of setup required.

### Jupyter Hub

In this setup, environment and data files have already been set up for you on available hardware.  At Fermilab, to access, use the link: `https://analytics-hub.fnal.gov:8080/` and sign in using your services account.  You need to be granteed the cluster permissions first.

### Plain Miniconda3 setup

We will be setting up the environment using [Miniconda](https://docs.conda.io/en/latest/miniconda.html) wity Python3.  This is wrapped in a [Docker](https://www.docker.com/) container for easy deployment.  

```
# currently it's setup for Mac, change the file if you want to run on Linux
source install_miniconda3.sh
# setup conda environmeent and install needed packages
source setup.sh
```

### Docker setup
_On its way -- need some help here still_

### Binder

You can launch notebooks in Binder for quick tests, but note this is not for resource-intensive computing:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FNAL-AI-Project/machine-learning-tutorial/master)

## Links

The accompanying lecture is [here](https://www.dropbox.com/s/z5b5elnpqahfrjz/MLTutorial_2020_V1.pdf?dl=0)

