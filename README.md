
Health Economics R Packages
===========================

A guide to some R packages that we know about for health economic analysis.

[Click here to suggest packages.](https://github.com/n8thangreen/health_economics_R_packages/edit/master/README.Rmd)

Overview
--------

The packages are generally in one of two groups. Either they are specifically designed to perform (some part of) a cost-effectiveness analysis or they are more generic and can be applied to this context.

1.  [Cost-effectiveness packages](#cost-effectiveness-analysis)

1.  Generic packages
    1.  [Decision trees](#decision-trees) 
    2.  [Multistate/micro-simulation models](#multistatemicrosimulation-models)
    3.  [Optimal decision process](#optimal-decision-processes)
    4.  [Visualisation](#visualisation)
    5.  [Data](#data)
    6.  [Miscellaneous](#miscellaneous)

Below we list the most useful R packages that we know of for each area.


Cost-effectiveness analysis
---------------------------

-   [BCEA](https://cran.r-project.org/web/packages/BCEA/index.html) - Bayesian Cost Effectiveness Analysis
-   [DALY](https://cran.r-project.org/web/packages/DALY/index.html) - The DALY Calculator - Graphical User Interface for Probabilistic DALY Calculation in R
-   [heemod](https://cran.r-project.org/web/packages/heemod/index.html) - Models for Health Economic Evaluation
-   [iSQoL2]() - Integration of Survival with QoL or Cost
-   [radiant](http://vnijs.github.io/radiant/) - Business Analytics using R and Shiny
-   [QoLR](https://cran.r-project.org/web/packages/QoLR/index.html) - Analysis of Health-Related Quality of Life in Oncology
-   [PROscorer](https://cran.rstudio.com/web/packages/PROscorer/index.html) - Functions to Score Commonly-Used Patient-Reported Outcome (PRO) Measures and Other Psychometric Instruments
-   [ArvoRe](http://arvore.r-forge.r-project.org/) - Cost-effectiveness Analysis (CEA) implementation for R oriented to compute problems that involve simple decision tree models and Markov models. It offer a graphic user interface (GUI) developed in Tcl/Tk. This graphical interface simplifies the decision tree creation task and its manipulation, such as, nodes addition, probability values definition, node kind configuration, etc.


Decision trees
--------------

These packages help you build and navigate tree-like objects.

-   [data.tree](https://cran.r-project.org/web/packages/data.tree/index.html) - General Purpose Hierarchical Data Structure
-   [igraph](https://cran.r-project.org/web/packages/igraph/index.html) - Network Analysis and Visualization
-   [jsonlite](https://cran.r-project.org/web/packages/jsonlite/index.html) - A Robust, High Performance JSON Parser and Generator for R
-   [rjson](https://cran.r-project.org/web/packages/rjson/index.html) - JSON for R
-   [jsonvalidate](https://github.com/hadley/dplyr) - Validate 'JSON'


Multistate/microsimulation models
----------------------------------

The related area of survival analysis has its own [CRAN Task View: Survival Analysis](https://cran.r-project.org/web/views/Survival.html).
This also has a multistate models section and a Simulation section with useful packages.
These packages help you simulate populations at individual or group levels.

Some package not included:

-   [ggm](https://cran.r-project.org/web/packages/ggm/index.html) - Functions for graphical Markov models
-   [rakeR](https://cran.r-project.org/web/packages/rakeR/index.html) - Easy Spatial Microsimulation (Raking) in R



Optimal decision processes
--------------------------

Packages for optimal control, dynamic programming or maximum utility theory would be useful. There is already the specific [CRAN Task View: Optimization and Mathematical Programming](https://cran.r-project.org/web/views/Optimization.html).

Of note, and not included in the Task View is the package

-   [MDPtoolbox](https://cran.r-project.org/web/packages/MDPtoolbox/index.html) - Markov Decision Processes Toolbox


Visualisation
-------------

These packages make it easier to program with the R language.

-   [diagram](https://cran.r-project.org/web/packages/diagram/index.html) - Functions for visualising simple graphs (networks), plotting flow diagrams
-   [DiagrammeR](https://cran.r-project.org/web/packages/DiagrammeR/index.html) - Create Graph Diagrams and Flowcharts Using R


Data
----

These packages contain data sets to use as training data or toy examples.

-   [rgho](https://github.com/hadley/babynames) - Access WHO Global Health Observatory Data from R


Miscellaneous
-------------

- [demography](https://www.rdocumentation.org/packages/demography/versions/1.20) - Forecasting Mortality, Fertility, Migration and Population Data


You can learn more about packages in R with the [CRAN task views](https://cran.r-project.org/web/views/).
