# Presentations

## WTC-2019

Here is the Markdown version 
-- made with [M2MD](https://github.com/kubaPod/M2MD) -- 
of the presentation notebook:
- ["Anomalies, breaks, and outliers detection in time series"](./WTC-2019/Anomalies-breaks-and-outliers-detection-in-time-series.md).

Here is the abstract:

>In this presentation we show, explain, and compare methods for finding anomalies, breaks, and outliers in time series. 
We are interested in finding anomalies in both a single time series and a collection of time series.

>We (mostly) employ non-parametric methods. First, we look at some motivational examples from well known datasets.
Then we look into definitions of anomalies and definitions for measuring success of time series anomaly detection. 

>For a single time series we apply both WL built-in algorithms and additional, specialized algorithms. 
>We discuss in more detail algorithms based on K-Nearest Neighbors (KNN), Dimension Reduction, Linear Regression, Quantile Regression, Prefix Trees.

>For collections of time series we discuss: transformations into uniform representations, 
>simple outlier finding based on variables distributions, anomalous trends finding, anomalies finding with KNN, and other related algorithms.

>We are going to discuss how anomalies finding helps in producing faithful simulations of multi-variable datasets.

>Concrete, real life time series are used in the examples.

>See the related dedicated 
>[MathematicaVsR](https://github.com/antononcube/MathematicaVsR) 
>project 
>["Time series anomalies, breaks, and outliers detection"](https://github.com/antononcube/MathematicaVsR/tree/master/Projects/TimeSeriesAnomaliesBreaksAndOutliersDetection).

## UseR!-2020

Here is the (extended) abstract of the *proposed* presentation:

- ["How to simplify Machine learning workflows specifications?"](https://htmlpreview.github.io/?https://github.com/antononcube/SimplifiedMachineLearningWorkflows-book/blob/master/Presentations/UseR!-2020/How-to-simplify-ML-workflows-specifications.nb.html). 

Versions:
[HTML](https://htmlpreview.github.io/?https://github.com/antononcube/SimplifiedMachineLearningWorkflows-book/blob/master/Presentations/UseR!-2020/How-to-simplify-ML-workflows-specifications.nb.html), 
[Rmd](./UseR!-2020/How-to-simplify-ML-workflows-specifications.Rmd).
 
Here is the *submitted* abstract:

> In this presentation we discuss a systematic approach of software development
that gives us the ability to rapidly specify Machine Learning (ML) computations
using both programming Domain Specific Languages (DSL's) and natural language commands.
We present in detail the selection of programming paradigms, languages, and packages.

>A central topic of the presentation is the transformation of sequences of natural 
commands into corresponding DSL pipelines for ML computations. 

>We use monadic programming and code generation for implementation of ML packages.
We use Raku (Perl 6) for grammar specifications, parsers generation, and interpreters.

>Numerous examples are used based on ML packages written in R
and English-based grammar rules. We look into code generation 
of ML workflows for supervised learning, time series analysis, latent semantic analysis, 
and recommendations. We show how with the same natural commands pipelines in other
programming languages can be generated.

>Finally we discuss the extensions of the presented approach to (1) handling wrong commands and
spelling mistakes, (2) using multiple natural languages, and (3) making conversational agents.

