# Machine Learning


-------------------

[TOC]

## Intro
-------------------

### Components
1. Pattern (Y)
2. Formula (N)
3. Data (Must)

### ML == Reverse
*  Viewers & Movies --> ratings; &nbsp&nbsp&nbsp&nbsp    ratings -<sup style="text-decoration:underline; font-weight:bold"> ML</sup>-> viewers & movies
*  Customer application -<sup style="text-decoration:underline; font-weight:bold"> ML</sup>-> good/bad customer (x,y) x-->y
    *  Learning Algorithm
    *  Hypothesis Set

### Types
1. Supervised (labeled)
- given the input & correct output (answer)
- Regression, Classification
- 如：刷题

2. Unsupervised (unlabeled)
- given the input, but no output
- Clustering
- 如：车上公放德语学德语 

3. Semi-Supervised
- 有标签数据的标签不是确定的，类似于：肯定不是xxx，很可能是yyy

4. Reinforcement
-  given the input & some output, <b>grade for this output
-  玩游戏


## Deep Learning
-------------------
> Find functions

Tools: Keras

### steps
1. Define a set of functions --- Neural Network
- Inputs, hidden layer (functions), output

2. Goodness of Function
- lots of training data

3. Pick the best function
- find the network parameters to minimize total loss L (different between output and target) 

### Why
If deep -> modularization, it can be trained by little data (some parts)
