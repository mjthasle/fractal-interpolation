# fractal-interpolation
Implementing Fractal Interpolation Functions for Large Datasets in Python

Fractal interpolation functions (FIFs) were introduced by Michael Barnsley in a 1986 paper as an application of dynamics
and fractals to data analysis. Subsequent years saw a wealth of exploration into FIFs; one in
particular is a 2020 paper by Sebastian Raubitzek and Thomas Neubauer as they measure the effectiveness of FIFs to generate
a more fine-grained time series out of insufficient datasets with the intent of improving machine learning models. The moral
is that fractal interpolation functions are generated through dynamical systems known as iterated function systems (IFSs), and
with their resulting self-similar nature, the interpolated data captures finer details that more traditional interpolation
methods (such as polynomials) may miss.

The goal in this project is to build a means of visualizing fractal interpolation functions when applied to a given dataset.
Given the fact that the functions will be constructed via IFSs, it is likely that tools built in the repository IFS-Python
will be useful.