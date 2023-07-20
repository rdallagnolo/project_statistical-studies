# Python Statistics Fundamentals: How to Describe Your Data

An article from [Real Python](https://realpython.com/python-statistics/)


In the era of big data and artificial intelligence, data science and machine learning have become essential in many fields of science and technology. A necessary aspect of working with data is the ability to describe, summarize, and represent data visually. Python statistics libraries are comprehensive, popular, and widely used tools that will assist you in working with data.

In this tutorial, you’ll learn:

> * What numerical quantities you can use to describe and summarize your datasets<br>
> * How to calculate descriptive statistics in pure Python<br>
> * How to get descriptive statistics with available Python libraries<br>
> * How to visualize your datasets

## Understanding Descriptive Statistics

Descriptive statistics is about describing and summarizing data. It uses two main approaches:

> * The quantitative approach describes and summarizes data numerically.<br>
> * The visual approach illustrates data with charts, plots, histograms, and other graphs.<br>


You can apply descriptive statistics to one or many datasets or variables. When you describe and summarize a single variable, you’re performing `univariate analysis`. When you search for statistical relationships among a pair of variables, you’re doing a `bivariate analysis`. Similarly, a `multivariate analysis`` is concerned with multiple variables at once.

## Types of Measures

In this tutorial, you’ll learn about the following types of measures in descriptive statistics:

> * Central tendency tells you about the centers of the data. Useful measures include the mean, median, and mode.<br>
> * Variability tells you about the spread of the data. Useful measures include variance and standard deviation.<br>
> * Correlation or joint variability tells you about the relation between a pair of variables in a dataset. Useful measures include covariance and the correlation coefficient.<br>

You’ll learn how to understand and calculate these measures with Python.

## Population and Samples

In statistics, the population is a set of all elements or items that you’re interested in. Populations are often vast, which makes them inappropriate for collecting and analyzing data. That’s why statisticians usually try to make some conclusions about a population by choosing and examining a representative subset of that population.

This subset of a population is called a `sample`. Ideally, the sample should preserve the essential statistical features of the population to a satisfactory extent. That way, you’ll be able to use the sample to glean conclusions about the population.

## Outliers

An outlier is a data point that differs significantly from the majority of the data taken from a sample or population. There are many possible causes of outliers, but here are a few to start you off:

> * Natural variation in data
> * Change in the behavior of the observed system
> * Errors in data collection

Data collection errors are a particularly prominent cause of outliers. For example, the limitations of measurement instruments or procedures can mean that the correct data is simply not obtainable. Other errors can be caused by miscalculations, data contamination, human error, and more.

There isn’t a precise mathematical definition of outliers. You have to rely on experience, knowledge about the subject of interest, and common sense to determine if a data point is an outlier and how to handle it.

