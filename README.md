# Bayesian Data Analysis - Python/PyMC

This repository contains Python/PyMC code designed as an introduction for those familiar with introductory statistical concepts, likely from a null hypothesis significance testing (NHST) perspective.  The code began life as a python implementation of models/figures from the book _Doing Bayesian Data Analysis: A Tutorial with R, JAGS, and Stan_, Second Edition, by John Kruschke (2015), but has meandered a bit since then.  Given the age of that book and the ever-advancing development of PyMC (and Bayesian modeling more generally), attempting to faithfully reproduce the book's models has seemed less and less useful.  It is hoped that any discrepancies between the models found here and those originally specified in the book represent progress.

The datasets used in this repository have been retrieved from [the book's website](https://sites.google.com/site/doingbayesiandataanalysis/).  Note that, this repository is not a standalone tutorial and will be far more helpful with guidance (e.g., Kruschke's book).  Questions, suggestions for improvement, and/or help with further development of the notebooks are always welcome!

### Notebooks

<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%205.ipynb'>Chapter 5 - Bayes' Rule</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%206.ipynb'>Chapter 6 - Inferring a Binomial Probability via Exact Mathematical Analysis</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%207.ipynb'>Chapter 7 - Markov Chain Monte Carlo</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%209.ipynb'>Chapter 9 - Hierarchical Models</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%2010.ipynb'>Chapter 10 - Model Comparison and Hierarchical Modelling</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%2016.ipynb'>Chapter 16 - Metric-Predicted Variable on One or Two Groups</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%2017.ipynb'>Chapter 17 - Metric-Predicted Variable with One Metric Predictor</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%2018.ipynb'>Chapter 18 - Metric Predicted Variable with Multiple Metric Predictors</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%2019.ipynb'>Chapter 19 - Metric Predicted Variable with One Nominal Predictor</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%2020.ipynb'>Chapter 20 - Metric Predicted Variable with Multiple Nominal Predictor</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%2021.ipynb'>Chapter 21 - Dichotomous Predicted Variable</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%2022.ipynb'>Chapter 22 - Nominal Predicted Variable</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%2023.ipynb'>Chapter 23 - Ordinal Predicted Variable</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/Chapter%2024.ipynb'>Chapter 24 - Count Predicted Variable</A><BR>
<P>
Other notebooks:<BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/ppc.ipynb'>Posterior Predictive Checking</A><BR>
<A href='http://nbviewer.jupyter.org/github/cluhmann/DBDA-python/blob/master/Notebooks/bayes-factors.ipynb'>Bayes' Factors</A><BR>
<P>

Libraries used/required:

 - pymc
 - arviz
 - pandas
 - numpy
 - scipy
 - matplotlib
 - seaborn

### Related References:
Kruschke, J.K. (2015), <I>Doing Bayesian Data Analysis: A Tutorial with R, JAGS, and Stan</I>, Second Edition, Academic Press / Elsevier, https://sites.google.com/site/doingbayesiandataanalysis/
<P>
Kruschke, J.K. & Liddell, T.M. (2017), <I>The Bayesian New Statistics: Hypothesis testing, estimation, meta-analysis, and power analysis from a Bayesian perspective</I>, Psychonomic Bulletin & Review, http://dx.doi.org/10.3758/s13423-016-1221-4
<P>
Kruschke, J.K. & Liddell, T.M. (2017), <I>Bayesian data analysis for newcomers</I>, Psychonomic Bulletin & Review, http://dx.doi.org/10.3758/s13423-017-1272-1
<P>
Salvatier J, Wiecki TV, Fonnesbeck C. (2016), <I>Probabilistic programming in Python using PyMC3</I>, PeerJ Computer Science 2:e55, https://doi.org/10.7717/peerj-cs.55 <BR>
PyMC3 - http://pymc-devs.github.io/pymc3/

### Note:
The repository below contains python code for the first edition of the book. The code in that repository is a much more direct implementation of the R/JAGS code from the book than you will find here.

https://github.com/aloctavodia/Doing_bayesian_data_analysis
