<head>
<link rel="stylesheet" href="//maxcdn.bootstrapcdn.com/font-awesome/4.3.0/css/font-awesome.min.css">
</head>

# PyData Paris 2024

## An update on the latest scikit-learn features

*Abstract*: In this talk, we provide an update on the latest `scikit-learn`
features that have been implemented in versions 1.4 and 1.5. We will
particularly discuss the following features:

- the metadata routing API allowing to pass metadata around estimators;
- the `TunedThresholdClassifierCV` allowing to tuned operational decision through custom metric;
- better support for categorical features and missing values;
- interoperability of array and dataframe.

<a href="https://docs.google.com/presentation/d/18XZcuokdTafTay8HKZzO0KkZnfuL3WkIhrbwjCJsvJc/edit?usp=sharing" class="btn"> <i class="fa fa-file-powerpoint-o"></i> Slides</a>
<a href="https://www.youtube.com/watch?v=PlCn-hqdMLw&ab_channel=PyData" class="btn"> <i class="fa fa-youtube"></i> Videos</a>
<a href="https://github.com/probabl-ai/sklearn-updates-pydata-paris-2024" class="btn"> <i class="fa fa-github"></i> Tutorials repository</a>

# PyConDE & PyData Berlin 2022

## Inspect an try to interpret your `scikit-learn` machine-learning models

*Abstract*: This tutorial is subdivided into three parts. First, we focus on
the family of linear models and present the common pitfalls to be aware of when
interpreting the coefficients of such models. Then, we look at a larger range
of models (e.g. gradient-boosting) and put into practice available inspection
techniques developed in `scikit-learn` to inspect such models. Finally, we
present other tools to interpret models (i.e. `shap`), not currently available
in `scikit-learn`, but widely used in practice.

<a href="https://docs.google.com/presentation/d/1xPf8vN9-pwZkAq28gbghJ9IWaNO4w-ZKO59193BWs34/edit?usp=sharing" class="btn"> <i class="fa fa-file-powerpoint-o"></i> Slides</a>
<a href="https://github.com/glemaitre/pydata_berlin_2022_scikit_learn_tutorial" class="btn"> <i class="fa fa-github"></i> Tutorials repository</a>


# PyLadies Paris 2022

## Inspecting your predictive model in Python

*Abstract*: This presentation intends to present the available tools allowing
to inspect your predictive model in Python. We will first quickly present
what we mean by predictive model and what it implies when one wants to explain
the decision of such a model. We will provide a quick taxonomy of the current
methods intending to explain predictive model. Finally, we will give an
overview of the available tools in `scikit-learn` and `shap`.

<a href="https://docs.google.com/presentation/d/14N8f3wGDG25Yz6mBXDvpsnbzTII_RYR7WsFEXh10H94/edit?usp=sharing" class="btn"> <i class="fa fa-file-powerpoint-o"></i> Slides</a>

# Euler Hermes 2019

## Learning from imbalanced datasets: state of the art

*Abstract*: This presentation gives an overview of the state of the art of
predictive modelling with imbalanced datasets.

<a href="https://docs.google.com/presentation/d/1_JIhDMNG21B4fVU0ceCyQ39ReOqWYGdaVDELn63Ck2Y/edit?usp=sharing" class="btn"> <i class="fa fa-file-powerpoint-o"></i> Slides</a>


# Euroscipy 2019

## Rapid Analytics & Model Prototyping (RAMP)

*Abstract*: We will give an overview of the RAMP framework, which provides a
platform to organize reproducible and transparent data challenges. RAMP
workflow is a python package used to define and formalize the data science
problem to be solved. It can be used as a standalone package and allows a user
to prototype different solutions. In addition to RAMP workflow, a set of
packages have been developed allowing to share and collaborate around the
developer solutions. Therefore, RAMP database provides a database structure to
store the solutions of different users and the performance of these solutions.
RAMP engine is the package to run the user solutions (possibly on the cloud)
and populate the database. Finally, RAMP frontend is the web frontend where
users can upload their solutions and which shows the leaderboard of the
challenge. The project is open-source and can be deployed on any local server.
The framework has been used at the Paris-Saclay Center for Data Science for
setting up and solving about twenty scientific problems, for organizing
collaborative data challenges, for organizing scientific sub-communities around
these events, and for training novice data scientists.


<a href="https://docs.google.com/presentation/d/12wliUZ_A-7l28gjSoSkUe2MUnCEHM2ijNuqA3A1Xq_g/edit?usp=sharing" class="btn"> <i class="fa fa-file-powerpoint-o"></i> Slides</a>
<a href="https://github.com/paris-saclay-cds/ramp-board" class="btn"> <i class="fa fa-github"></i> RAMP board</a>
<a href="https://github.com/paris-saclay-cds/ramp-workflow" class="btn"> <i class="fa fa-github"></i> RAMP workflow</a>

## Introduction to `scikit-learn`: from model fitting to model interpretation


*Abstract*: Our introduction to scikit-learn will be subdivided into 2 parts.
We will give a general introduction to scikit-learn presenting basic concepts
around cross-validation, pipeline estimator, and hyperparameter search. Then,
we will focus on model interpretation presenting the challenges and the
available tools to understand a trained machine-learning model: partial
independence plot, features importance, LIME, shapley values, etc.


<a href="http://ogrisel.github.io/decks/2017_intro_sklearn/#1" class="btn"> <i class="fa fa-file-powerpoint-o"></i> Slides</a>
<a href="https://github.com/lesteve/euroscipy-2019-scikit-learn-tutorial" class="btn"> <i class="fa fa-github"></i> Tutorials repository</a>

# Euroscipy 2018

## Imbalanced-learn: A scikit-learn-contrib to tackle learning from imbalanced data set

*Abstract*: The curse of imbalanced data set refers to data sets in which the
number of samples in one class is less than in others. This issue is often
encountered in real world data sets such as medical imaging applications
(e.g. cancer detection), fraud detection, etc. In such particular condition,
machine learning algorithms learn sub-optimal models which will generally favor
the class having the largest number of samples. In this talk, we review the
different available strategy to learn a statistical model under those specific
condition. Then, we will present `imbalanced-learn` package and the new
features which will be released in the new version 0.4.

<a href="2018_euroscipy" class="btn"> <i class="fa fa-file-powerpoint-o"></i> Slides</a>
<a href="https://github.com/scikit-learn-contrib/imbalanced-learn" class="btn"> <i class="fa fa-github"></i> Package</a>


# CDS Pitching Day 2017

## RAMP on predicting autism from resting-state functional MRI and anatomical MRI

*Abstract*: This talk will present the ongoing preparation of a RAMP aiming at
distinguishing subjects with Autism Spectrum Disorder (ASD) from typical
control subjects. This analysis will use the Autism Brain Imaging Data Exchange
(ABIDE I & II) database and data from Robert Debre Hospital based on R-fMRI and
anatomical MRI. We will particularly focus on presenting the problematic, the
typical pipeline answering this problem, and the current status of this RAMP.
This work is in collaboration with the Pasteur Institute (Neuroanatomy group of
the Unit of Human Genetics and Cognitive Functions).

<a href="2017_CDS_pitching_talk" class="btn"> <i class="fa fa-file-powerpoint-o"></i> Slides</a>

# Euroscipy 2017

## Leverage knowledge from under-represented classes in machine learning: imbalanced-learn release 0.3.0

*Abstract*: The curse of imbalanced data set refers to data sets in which the
number of samples in one class is less than in others. This issue is often
encountered in real world data sets such as medical imaging applications
(e.g. cancer detection), fraud detection, etc. In such particular condition,
machine learning algorithms learn sub-optimal models which will generally favor
the class having the largest number of samples. In this talks, we present the
new feature which are available in the release 0.3.0.

<a href="2017_euroscipy" class="btn"> <i class="fa fa-file-powerpoint-o"></i> Slides</a>
<a href="https://github.com/scikit-learn-contrib/imbalanced-learn" class="btn"> <i class="fa fa-github"></i> Package</a>


# PyParis 2017

## Leverage knowledge from under-represented classes in machine learning: an introduction to imbalanced-learn

*Abstract*: The curse of imbalanced data set refers to data sets in which the
number of samples in one class is less than in others. This issue is often
encountered in real world data sets such as medical imaging applications
(e.g. cancer detection), fraud detection, etc. In such particular condition,
machine learning algorithms learn sub-optimal models which will generally favor
the class having the largest number of samples. In this talk, we will present
the imbalanced-learn package which implement some of the state-of-the-art
algorithms, tackling the class imbalance problem.

<a href="2017_PyParis" class="btn"> <i class="fa fa-file-powerpoint-o"></i> Slides</a>
<a href="https://github.com/scikit-learn-contrib/imbalanced-learn" class="btn"> <i class="fa fa-github"></i> Package</a>
