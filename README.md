README-BioMonTools_Shiny
================

<!-- README.md is generated from README.Rmd. Please edit that file -->

    #> Last Update: 2025-09-09 10:15:34.517741

# BioMonTools_Shiny

Shiny application for BioMonTools package

# Badges

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/leppott/BioMonTools_Shiny/graphs/commit-activity)

[![Lifecycle](https://img.shields.io/badge/lifecycle-stable-green.svg)](https://www.tidyverse.org/lifecycle/#stable)

[![License:
MIT](https://img.shields.io/badge/license-MIT-blue.svg)](https://cran.r-project.org/web/licenses/MIT)

[![GitHub
issues](https://img.shields.io/github/issues/leppott//BioMonTools_Shiny.svg)](https://GitHub.com/leppott//BioMonTools_Shiny/issues/)

[![GitHub
release](https://img.shields.io/github/release/leppott/BioMonTools_Shiny.svg)](https://GitHub.com/leppott/BioMonTools_Shiny/releases/)
[![Github all
releases](https://img.shields.io/github/downloads/leppott/BioMonTools_Shiny/total.svg)](https://GitHub.com/leppott/BioMonTools_Shiny/releases/)

# Installation

To install the current version of the code from GitHub use the example
below.

``` r
if(!require(remotes)){install.packages("remotes")}  #install if needed
remotes::install_github("leppott/BioMonTools_Shiny")
```

# Purpose

Provide Shiny interface for BioMonTools package.

# Issues

<https://github.com/leppott/BioMonTools_Shiny/issues>

# Documentation

None at this time. Shiny app only.

# Shiny App

A Shiny app is included in the package.

The online version is hosted at
<https://tetratech-wtr-wne.shinyapps.io/BioMonTools>

The Shiny app can be run from R console using the shiny package without
installing the package.

``` r
if(!require(shiny)){install.packages("shiny")}
shiny::runGitHub(repo = "BioMonTools_Shiny"
                , username = "leppott"
                , ref = "main"
                , subdir = "apps/BioMonTools")
```
