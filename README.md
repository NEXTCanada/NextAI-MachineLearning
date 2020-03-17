# NextAI-MachineLearning

Materials for the NextAI Technical Stream Course on Machine Learning.

## Pre-requisite material

You are encouraged to review the following topics in advance of the Machine Learning course. It's common to be rusty on these subjects, especially if you have been out of school for a while.

I've provided suggested readings from the new textbook [Mathematics for Machine Learning](https://mml-book.github.io/) (MML) by Marc Peter Deisenroth, A. Aldo Faisal, and Cheng Soon Ong. The pdf version of this textbook is freely available online.

I've also provided supplementary Jupyter Notebooks (via Google Colaboratory) that contain Python-based examples and exercises related to the review topics. More information on running the notebooks is provided below.

|             Topic             | Readings from MML                                                                                                                                                                                                                                                                                                                                                                                                            | Jupyter Notebooks                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|:-----------------------------:|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Introduction                  | - Foreword<br>- 1 Introduction & Motivation<br>- 1.1 Finding Words for Intuitions<br>- 1.2 Two Ways to Read This Book<br>- 1.3 Exercises and Feedback                                                                                                                                                                                                                                                                        | [1. Scientific Python](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/01%20-%20ScientificPython.ipynb)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Linear Algebra                | - 2 Linear Algebra<br>- 2.1 Systems of Linear Equations<br>- 2.2 Matrices<br>- 2.3 Solving Systems of Linear Equations<br>- 2.4 Vector Spaces<br>- 2.5 Linear Independence<br>- 2.6 Basis and Rank<br>- 2.7 Linear Mappings<br>- 2.8 Affine Spaces                                                                                                                                                                           | - [2a. Vectors and Matrices](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/02a%20-%20VectorsAndMatrices.ipynb)<br>- [2b. Solving Systems of Linear Equations](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/02b%20-%20SolvingSystemsOfLinearEquations.ipynb)<br>- [2c. Linear Independence](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/<br>02c%20-%20LinearIndependence.ipynb)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Analytic Geometry             | - 3 Analytic Geometry<br>- 3.1 Norms<br>- 3.2 Inner Products<br>- 3.3 Lengths and Distances<br>- 3.4 Angles and Orthogonality<br>- 3.5 Orthonormal Basis<br>- 3.6 Orthogonal Complement (*Optional*)<br>- 3.7 Inner Product of Functions (*Optional*)<br>- 3.8 Orthogonal Projections<br>- 3.9 Rotations                                                                                                                     | - [3a. Analytic Geometry](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/03a%20-%20AnalyticGeometry.ipynb)<br>- [3b. Orthogonality](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/03b%20-%20Orthogonality.ipynb)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Matrix Decompositions         | - 4 Matrix Decompositions<br>- 4.1 Determinant and Trace<br>- 4.2 Eigenvalues and Eigenvectors<br>- 4.3 Cholesky Decomposition<br>- 4.4 Eigendecomposition and Diagonalization<br>- 4.5 Singular Value Decomposition<br>- 4.6 Matrix Approximation<br>- 4.7 Matrix Phylogeny                                                                                                                                                 | - [4a. Determinant and Trace](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/04a%20-%20DeterminantAndTrace.ipynb)<br>- [4b. Eigenvalues and Eigenvectors](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/04b%20-%20EigenvaluesAndEigenvectors.ipynb)<br>- [4c. Cholesky Decomposition](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/04c%20-%20CholeskyDecomposition.ipynb)<br>- [4d. Eigendecomposition and Diagonalization](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/04d%20-%20EigendecompositionAndDiagonalization.ipynb)<br>- [4e. Singular Value Decomposition](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/)<br>- [4f. Matrix Approximation](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/04f%20-%20MatrixApproximation.ipynb) |
| Vector Calculus               | - 5 Vector Calculus<br>- 5.1 Differentiation of Univariate Functions<br>- 5.2 Partial Differentiation and Gradients<br>- 5.3 Gradients of Vector-Valued Functions<br>- 5.4 Gradients of Matrices<br>- 5.5 Useful Identities for Computing Gradients<br>- 5.6 Backpropagation and Automatic Differentiation<br>- 5.7 Higher-Order Derivatives (*Optional*)<br>- 5.8 Linearization and Multivariate Taylor Series (*Optional*) | - [5a. Derivatives, Partial Derivatives, and Gradients](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/05a%20-%20DerivativesPartialDerivativesAndGradients.ipynb)<br>- [5b. Automatic Differentiation](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/05b%20-%20AutomaticDifferentiation.ipynb)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Probability and Distributions | - 6 Probability and Distributions<br>- 6.1 Construction of a Probability Space<br>- 6.2 Discrete and Continuous Probabilities<br>- 6.3 Sum Rule, Product Rule, and Bayes’ Theorem<br>- 6.4 Summary Statistics and Independence<br>- 6.5 Gaussian Distribution<br>- 6.6 Conjugacy and the Exponential Family (*Optional*)<br>- 6.7 Change of Variables/Inverse Transform (*Optional*)                                         | - [6a. Discrete and Continuous Probabilities](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/06a%20-%20DiscreteAndContinuousProbabilities.ipynb)<br>- [6b. Summary Statistics and Independence](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/06b%20-%20SummaryStatisticsAndIndependence.ipynb)<br>- [6c. The Gaussian and its Longer-tailed Cousins](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/06c%20-%20GaussianDistribution.ipynb)                                                                                                                                                                                                                                                                                                                                                                                                                              |
| Continuous Optimization       | - 7 Continuous Optimization<br>- 7.1 Optimization using Gradient Descent<br>- 7.2 Constrained Optimization and Lagrange Multipliers<br>- 7.3 Convex Optimization                                                                                                                                                                                                                                                             | - [7a. Unconstrained Optimization](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/07a%20-%20UnconstrainedOptimization.ipynb)<br>- [7b. Constrained Optimization](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/07b%20-%20ConstrainedOptimization.ipynb)<br>- [7c. Black-box Function Optimization](https://colab.research.google.com/github/NEXTCanada/NextAI-MachineLearning/blob/master/07c%20-%20BlackBoxOptimization.ipynb)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |

## In-course material

Once the course begins, this site will be updated with supporting material.

## Python

Python is established as a leading choice in scientific computing, and in
particular, in machine learning. Compared to its competitors (e.g. Matlab), it’s
open-source and free! Thanks to a stable numerical base called Numpy which can
take advantage of low-level accelerated libraries like the Intel Math Kernel
Library (Intel MKL), one can get C-like speeds but with far less programming
overhead than compiled languages.

We’ll be using Python for examples in this course.

## Scientific Python

The so-called "scientific Python" suite consists of a number of tools, including
but not limited to:

* NumPy: fundamental package for scientific computing, array data structures and
  operations.
* SciPy: various indispensable tools for math, science, and engineering (depends
  on NumPy).
* Matplotlib: easy plotting and visualization, MatLab-style.
* IPython: MatLab-like interactive shell.
* Jupyter: an open-source web application that allows you to create and share documents that contain live code, equations, visualizations, and narrative text.

## Running the Notebooks

Pre-requisite material and in-course examples will be delivered as Jupyter notebooks. I have make these available through Colaboratory: a free Jupyter notebook environment that requires no setup and runs entirely in the cloud.

I recommend that you visit the [Welcome to Colaboratory!](https://colab.research.google.com/notebooks/welcome.ipynb) notebook to get a feel for how this works.

To run a notebook in Collaboratory, all you need to do is click on one of the links below. By default, the notebooks will open with read-only privileges, so you will need to make a copy in order to save your changes.

## Local install (optional)

Though it is not necessary for this course to install Python on your personal computer, if you wish to do so, I recommend using an off-the-shelf distribution that comes with all the packages described above. Continuum Analytics' [Anaconda](https://docs.anaconda.com/anaconda/install/) has everything we need (and more) for this course. It's cross-platform and completely free for basic use.

### Anaconda environment setup

If you choose to download the notebooks and run them on your computer instead of running them in Collaboratory, you can use the environment file provided to simplify setup. The recommended setup procedure is as follows:

1. Download and install [Anaconda](https://www.anaconda.com/distribution/) (Python 3.7 version)
2. Read about
   [Managing environments](http://conda.pydata.org/docs/using/envs.html)
3. Examine the YAML environment file `environment.yml` which contains
   dependencies for the course (and examine it in a text editor so you see
   what's going on)
4. Create a new environment based on the YAML file:
   ```
    conda env create -f environment.yml
    ```
5. Activate your new Python environment:
   ```
    source activate nextai
    ```
6. Start jupyter from this directory:
   ```
   jupyter notebook
   ```
