# repotest

This is a test

[![Travis](https://travis-ci.org/chaireBioNorth/repo-test.svg?branch=master)](https://travis-ci.org/chaireBioNorth/repo-test)

# Installation

To install the package **repotest** from GitHub, first install the package [**devtools**](http://cran.r-project.org/web/packages/devtools/index.html) from the CRAN.

```r
# Install the < devtools > package
install.packages("devtools", dependencies = TRUE)

# Load the < devtools > package
library(devtools)

```

Then install the **repotest** package:

```r
# Install the < repotest > package from GitHub
devtools::install_github("chaireBioNorth/repotest", build_vignettes = TRUE)

# Load the < repotest > package
library(repotest)
```

# Usage

```r
hello("Hello world!")
```
