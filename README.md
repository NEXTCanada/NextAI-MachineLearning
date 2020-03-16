# NextAI-MachineLearning

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/NEXTCanada/NextAI-MachineLearning/master)

Materials for the NextAI Technical Stream Course on Machine Learning.

Notebooks 1 - 4 cover pre-requisite material and are intended to be reviewed
before immersion week.

Notebooks 5 - 8 will be covered during immersion week.

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

* Numpy: fundamental package for scientific computing, array data structures and
  operations
* Scipy: various indispensable tools for math, science, and engineering (depends
  on Numpy)
* Matplotlib: easy plotting and visualization, Matlab-style
* IPython: Matlab-like interactive shell

Building these libraries on your own is often a hassle, so we recommend using an
off-the-shelf distribution. Continuum Analytics' [Anaconda] has everything we
need (and more) for this class. It's cross-platform and completely free for
basic use. This will be our recommended way of installing Python and the
required libraries for the course.

## Running the Notebooks

The easiest way to run the notebooks is to click on the "launch binder" button at the top of this page.

Alternatively, you can download and run the notebooks on your own computer. In this case, the recommended setup procedure is as follows:

1. Download and install [Anaconda] (Python 3.7 version)
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

[Anaconda]: https://docs.continuum.io/anaconda/
