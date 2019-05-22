
# Welcome to my Statistics Calculator! :octocat:

## To Do's
- make a website for the calculator
- use cmake to launch
- Extensively test the calculator using the [doctest](https://github.com/onqtam/doctest) testing framework

## Third-Party 
- [termcolor](https://github.com/marinov98/termcolor)

## Requirements 
- **CMake 3.12** or newer
- **C++14** or newer

## Table of Contents
  1. [Goals](#Goals)
  2. [Functionality](#Functionality)
  3. [How To Use](#How-To-Use)

## Goals
- Create a simple calculator that can calculate almost anything you throw at it from your intro to statistics class
- Provide an easy to follow interface 
- Allow users to have all in one program that does everything instead of having them search online for different types of statistic calculators

## Functionality 

### Contains Its own [Formula Sheet](https://github.com/marinov98/Statistical_Calculator/blob/master/src/formulas.txt)!

### Basics: 
- mean, median, mode, range
- Sample/Population standard deviation & variance
- Min and Max
- Percentiles
- Interquartile range
- Outliers

#### Showcase:
![basics](https://user-images.githubusercontent.com/33673401/58147734-f9534c80-7c29-11e9-8a05-96f84acfeffa.png)


### Hypothesis Testing (Advanced)
- calculate z-score and t-score
- one/two sample **t** and **z** tests
  - proportions, pair, difference 
- Chi-square test

### Confidence intervals (Advanced)
- Sampling Distribution
- z/t confidence intervals
  - proportion, sample
  - multple z-critical values
  
### Correlation Coefficient
- correlation coefficient
- slope, y-intercept
- line of best fit

#### Showcase:
![cc](https://github.com/marinov98/Statistical_Calculator/edit/master/basics.png)

## How-To-Use
- clone this repository
- cd into  Statistical_Calculator
- run ```make``` then ```make run```

## Regarding CMake
- right now it is best to compile with the Makefile I made for the project
- The Cmake works just as well
