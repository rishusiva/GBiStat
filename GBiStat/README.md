# GBiStat package

A python package to assist programmers with data analysis.

This package could be used to plot :
* `Binomial Distribution` of the dataset
* probability density function of the `binomial distribution` 
* `Gaussian Distribution` of the dataset
* normalized histogram of the data and probability density function of the `gaussian distribution` along the same range


Various mathematical operations can also be done:

### Gaussian Distribution:
* mean
* standard deviation
* probability density function
* add 2 gaussian distributions 
* characteristics of gaussian instance

### Binomial Distribution:
* mean
* standard deviation
* calculate p and n of the dataset
* probability density function
* add 2 binomial distributions with equal p
* characteristics of binomial instance


# Files

## __init__.py

used to call the Gaussian and Binomial functions directly.

## BinomialDistribution.py

Used to read the file containing the data and perform all the statistical operations related to the binomial distribution:
* mean
* standard deviation
* calculate p and n of the dataset
* probability density function
* add 2 binomial distributions with equal p
* characteristics of binomial instance
* plot histogram of the instance variable data 
* plot probability density function

## Gaussian Distribution.py

Used to read the file containing the data and perform all the statistical operations related to the gaussian distribution:
* standard deviation
* probability density function
* add 2 gaussian distributions 
* characteristics of gaussian instance
* plot histogram of instance variable data
* plot probability density function
* plot the normalized histogram of the data and a plot of the probability density function along the same range

## license.txt

Contains the MIT License .

## setup.cfg

a configuration file for the users to edit to override the original setup file if necessary.


# Installation

```
pip install GBiStat

```
