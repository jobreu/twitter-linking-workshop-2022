# Jupyter notebooks containing examples of how to collect Twitter data with R, Python, and the command-line interface (CLI)

This repository contains a set of interactive [*Jupyter Notebooks*](https://jupyter.org/) that allow you to try out some data collection tools for Twitter without the need to install anything on your own computer.

**To access the notebooks simply click the "Launch Binder" button below.** 
This will open a [Jupyter Lab environment](https://jupyterlab.readthedocs.io/en/stable/) in your browser (**NB**: This might take a moment to load).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jobreu/twitter-linking-workshop-2022/main?urlpath=lab)

If you have not worked with *Jupyter Notebooks* before, you can check out how to use them by opening the `jupyter_intro.ipynb` file in the *Jupyter Lab environment* that will open in your browser. Otherwise, you can launch one of the other notebooks (i.e, open one of the `.ipynb` files by double-clicking it in the explorer view on the left-hand side) to try out the `R` package [`academictwitteR`](https://github.com/cjbarrie/academictwitteR), the `Python` library [`tweepy`](https://github.com/tweepy/tweepy), and the command-line interface (CLI) tool [`twarc`](https://twarc-project.readthedocs.io/en/latest/).

## Important Notes

To use the Twitter data collection notebooks contained in this repository, you need a [bearer token](https://developer.twitter.com/en/docs/authentication/oauth-2-0/bearer-tokens) which you can obtain if you have [academic research access](https://developer.twitter.com/en/solutions/academic-research/products-for-researchers) to the *Twitter* v2 API. You can find detailed instructions on how to do that in the [documentation for the `twarc` CLI tool/`Python` library](https://twarc-project.readthedocs.io/en/latest/twitter-developer-access/) and this [vignette for the `R` package `academictwitteR`](https://cran.r-project.org/web/packages/academictwitteR/vignettes/academictwitteR-auth.html).

Any changes you make in the notebooks are not persistent and will be lost at the end of your user session. If you want to keep the changes you made, you can download the files and continue to use them locally. 

**IMPORTANT**: The *Jupyter Lab environment* that you can access via the "Launch Binder" button is only meant for demonstration purposes. It should not be used for actually collecting data. If you want to use (code from) the notebooks to collect your own data, please download the notebook(s) and run them locally on your machine (or your own server). The easiest way to run and create *Jupyter Notebooks* on your local machine is installing and using [*Anaconda*](https://www.anaconda.com/products/individual).

To save the entire contents of this *GitHub* repository locally, you can click the green *Code* button on this page and then select *Download ZIP* (if you work with `Git` or *GitHub*, you can, of course, also just clone or fork the repository).

## Technical Note

To provide the interactive *Jupyter Notebooks* this repository uses the [`BinderHub`](https://binderhub.readthedocs.io/en/latest/) deployment [*mybinder.org*](https://mybinder.org/).