---
title: Regression and classification tree
author: Jiaming
date: '2018-03-21'
slug: regression-and-classification-tree
categories:
  - programming
  - Statistics
  - statitics notes
tags:
  - Multivariable analysis
  - nonparametric
  - programming
  - regression
  - statistics, linear model, regression, covariance
---

This is just to make the position.
The downloaded version of the "Classification and Regression Trees" is very not clear. So I try to borrow one from university library. Then I will write some notes about this book here.
This may not be fulfill very quick, but I hope so.
Maybe this will be the first time to use the feature of r markdown, the package "rparts" description is implementing the algorithms in that book.

Chap1 The back ground.

1.1 Classifiers as partitions
The classification problem is with a long history and real world background, such as the medical diagnosis problem. We make some measurements on some case or object then predict which class the case is in.
Then the book describe 3 examples. The first one is the analysis of a complex chemical compound by analysis its mass spectra. Measurement is contains one or more chlorine atoms or not. The second example is the days in the Los Angeles. The class is the ozone level(low,moderate or high). Measurement involve temperature, humidity and others. The third example is heart attack study. Measurement X is a 19-dimensional space with age, blood presure,.etc.

Then here is the definition of a classifier:
Def 1.1 A classifier or classification rule is a function d(x) defined on X so that for every x, d(x) is equal to one of the numbers 1,2,...,J. 

That is map from sample space to the class space.
Of course the classifier is not come from nothing, it comes from data. The problem is how to use data to construct a classifier. Then here gives some notation and term about the data.
Learning sample(training set), is the data pair such like $(x_1,j_1)$, $x_1$ is the measurement of all kinds of data, $j_1$ is the indicator of class. This means such case with measurement is located in a class $j_1\in \{1,2,3....,N\}$






