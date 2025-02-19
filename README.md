
[<img src="https://raw.githubusercontent.com/grayknight2/Awesome-R-packages/master/Awesome_R_packages_banner.png" align="center" width="850">](https://www.r-project.org/)

<p align="center">
  <a href="https://stackoverflow.com/questions/tagged/R?sort=votes">
    <img alt="StackOverflow" src="https://img.shields.io/badge/StackOverflow-16,410-orange.svg" />
  </a>
  <a href="https://github.com/search?q=language%3AR&type=Repositories">
    <img alt="Github Repositories" src="https://img.shields.io/badge/Repos-71173-brightgreen.svg" />
  </a>
  <img alt="Entries" src="https://img.shields.io/badge/Items-325-lightgrey.svg" />
  <a href="https://github.com/sindresorhus/awesome">
    <img alt="Awesome" src="https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg" />
  </a>
</p>

[R](https://www.r-project.org/) is a language and environment for statistical computing and graphics.


This is a curated list 📄 of awesome 🌟 R packages 🌟. These are some of the most relevant packages of the R community.

😍 Is your favourite package missing? 😍  Let me know! 🤔

## Some visual examples of what R is able to do - Awesome R packages

<div style="text-align: center"><table><tr>
  
  <td style="text-align: center">
  <a href="https://github.com/dkahle/ggmap">
    <img src="https://raw.githubusercontent.com/dkahle/ggmap/master/tools/README-styling-1.png" width="400"/></a>
  </td>
  
  <td style="text-align: center">
   <a href="https://github.com/tylermorganwall/rayshader">
    <img src="https://github.com/tylermorganwall/rayshader/blob/master/man/figures/smallhobart.gif" width="400"/></a>
  </td>

  <td style="text-align: center">
  <a href="https://github.com/tylermorganwall/rayshader">
    <img src="https://github.com/tylermorganwall/rayshader/blob/master/man/figures/README_ggplots_5-1.png" width="400"/></a>
  </td>
  
</tr></table></div>

<div style="text-align: center"><table><tr>
  
  <td style="text-align: center">
  <a href="https://github.com/djnavarro/brownianbridge">
    <img src="https://raw.githubusercontent.com/djnavarro/brownianbridge/master/bridge5_shadowwake/shadow_wake_files/figure-markdown_github/wake8-1.gif" width="400"/></a>
  </td>
  
  <td style="text-align: center">
   <a href="https://github.com/amrrs/animated_bar_charts_in_R">
    <img src="https://raw.githubusercontent.com/amrrs/animated_bar_charts_in_R/master/gganim.gif" width="400"/></a>
  </td>

  <td style="text-align: center">
  <a href="https://github.com/YinLiLin/R-CMplot">
    <img src="https://raw.githubusercontent.com/YinLiLin/R-CMplot/master/Figure/9.jpg" width="400"/></a>
  </td>
  
</tr></table></div>

# Index

- [IDE](#IDE) 
- [Misc](#Misc)
- [Data import](#Data-import)
- [Dashboards](#Dashboards)
- [Graphics](#Graphics)
- [Finance](#Finance)
- [Functional data](#Functional-data)
- [Regression](#Regression)
- [Optimization]()
- [Spatial statistics](#Spatial-statistics)
- [Web scraping](#Web-scraping)
- [Packages development](#Packages-development)
- [Fun stuff](#Fun-stuff)

More soon...

# IDE

Ok, most of them are no packages, but you also need one.

- [RStudio](https://rstudio.com/products/rstudio/download/). A powerful and productive user interface for R. Works great on Windows, Mac, and Linux.
- [R Commander](https://www.rcommander.com/). A package that provides a basic graphical user interface.
- [RKWard](https://rkward.kde.org/). An extensible IDE/GUI for R.
- [Emacs + ESS](http://ess.r-project.org/). Emacs Speaks Statistics is an add-on package for emacs text editors.
- [Sublime Text + R-Box](https://github.com/randy3k/R-Box/). Add-on package for Sublime Text 2/3.
- [TextMate + r.tmblundle](https://github.com/textmate/r.tmbundle). Add-on package for TextMate 1/2.
- [StatET](). An Eclipse based IDE for R.
- [Microsoft R](). Revolution R would be offered free to academic users and commercial software would focus on big data, large scale multiprocessor functionality.
- [IRkernel](). R kernel for Jupyter.
- [Deducer](). A Menu driven data analysis GUI with a spreadsheet like data editor.
- [Radiant](). A platform-independent browser-based interface for business analytics in R, based on the Shiny.
- [Vim-R](). Vim plugin for R.
- [PyCharm](https://www.jetbrains.com/pycharm/) with [R plugin](https://www.jetbrains.com/help/pycharm/r-plugin-support.html).
- [Nvim-R](). Neovim plugin for R.
- [Jamovi and JASP](). Desktop software for both Bayesian and Frequentist methods, using a UI familiar to SPSS users.
- [Bio7](). An IDE contains tools for model creation, scientific image analysis and statistical analysis for ecological modelling.
- [RTVS](). R Tools for Visual Studio.
- [radian (formerly rtichoke)](). An alternative console for the R program with multiline editing and rich syntax highlight.

# Misc
- [installr](https://cran.r-project.org/web/packages/installr/index.html). Automate the updating of R and install new software.
- [plumber](https://cran.r-project.org/web/packages/plumber/index.html). An API Generator for R.
- [checkpoint](https://cran.r-project.org/web/packages/checkpoint/index.html). Install package versions from a specific date in the past.
- [mailR](https://cran.r-project.org/web/packages/mailR/). A utility to send emails from R.
- [pacman](https://cran.r-project.org/web/packages/pacman/index.html). Tools to more conveniently perform tasks associated with add-on packages. pacman conveniently wraps library and package related functions and names them in an intuitive and consistent fashion. It seeks to combine functionality from lower level functions which can speed up workflow.
- [askpass](https://cran.r-project.org/web/packages/askpass/index.html). Cross-platform utilities for prompting the user for credentials or a passphrase, for example to authenticate with a server or read a protected key.
- [rsconnect](https://cran.r-project.org/web/packages/rsconnect/index.html). Deployment Interface for R Markdown Documents and Shiny Applications.

# Data import
- [readxl](https://cran.r-project.org/web/packages/readxl/). Import excel files into R.
- [readr](https://cran.r-project.org/web/packages/readr/). Provide a fast and friendly way to read rectangular data (like 'csv', 'tsv', and 'fwf'). It is designed to flexibly parse many types of data found in the wild, while still cleanly failing when data unexpectedly changes.
- [datapasta](https://cran.r-project.org/web/packages/datapasta/). RStudio addins and R functions that make copy-pasting vectors and tables to text painless.
- [jsonlite](https://cran.r-project.org/web/packages/jsonlite/). A fast JSON parser and generator optimized for statistical data and the web.

# Dashboards
- [Shiny](https://cran.r-project.org/web/packages/shiny/index.html). Interactive web applications with R. Automatic "reactive" binding between inputs and outputs and extensive prebuilt widgets make it possible to build beautiful, responsive, and powerful applications with minimal effort.
- [flexdashboard](https://cran.r-project.org/web/packages/flexdashboard/index.html). Format for converting an R Markdown document to a grid oriented dashboard. The dashboard flexibly adapts the size of it's components to the containing web page.
- [shinydashboard](https://cran.r-project.org/web/packages/shinydashboard/index.html). Create dashboards with 'Shiny'. This package provides a theme on top of 'Shiny', making it easy to create attractive dashboards.
- [shinythemes](https://cran.r-project.org/web/packages/shinythemes/). Themes for use with Shiny. Includes several Bootstrap themesfrom <http://bootswatch.com/>, which are packaged for use with Shinyapplications.

# Graphics
- [calendR](https://cran.r-project.org/web/packages/calendR/). Contains the function calendR() for creating fully customizable monthly and yearly calendars. In addition, it allows saving the calendars in ready to print A4 format PDF files.
- [ggplot2](https://cran.r-project.org/web/packages/ggplot2/index.html). A system for 'declaratively' creating graphics, based on "The Grammar of Graphics".
- [ggstatsplot](https://cran.r-project.org/web/packages/ggstatsplot/index.html). Extension of 'ggplot2' that creates graphics with details from statistical tests included in the plots themselves. 
- [GGally](https://cran.r-project.org/web/packages/GGally/). Extends 'ggplot2' by adding several functions to reduce the complexity of combining geometric objects with transformed data.
- [ggvis](https://cran.r-project.org/web/packages/ggvis/index.html). An implementation of an interactive grammar of graphics, taking the best parts of 'ggplot2', combining them with the reactive framework of 'shiny' and drawing web graphics using 'vega'.
- [Lattice](https://cran.r-project.org/web/packages/lattice/index.html). Trellis Graphics for R.
- [highcharter](https://cran.r-project.org/web/packages/highcharter). A wrapper for the 'Highcharts' library including shortcut functions to plot R objects.
- [Plotly](https://cran.r-project.org/web/packages/plotly/). Create interactive web graphics from 'ggplot2' graphs and/or a custom interface to the (MIT-licensed) JavaScript library 'plotly.js' inspired by the grammar of graphics.
- [sunburstR](https://cran.r-project.org/web/packages/sunburstR/). Make interactive 'd3.js' sequence sunburst diagrams in R with the convenience and infrastructure of an 'htmlwidget'.
- [r2d3](https://github.com/rstudio/r2d3). Provides a suite of tools for using D3 visualizations with R.
- [RGL](https://cran.r-project.org/web/packages/rgl/). Provides medium to high level functions for 3D interactive graphics, including functions modelled on base graphics (plot3d(), etc.) as well as functions for constructing representations of geometric objects.
- [magick](https://cran.r-project.org/web/packages/magick). Advanced Graphics and Image-Processing in R.
- [dygraphs](https://cran.r-project.org/web/packages/dygraphs/). An R interface to the 'dygraphs' JavaScript charting library.
- [gganatogram](https://github.com/jespermaag/gganatogram). Create anatograms using ggplot2.

## Maps
- [tmap](https://github.com/mtennekes/tmap). Drawing thematic maps in R.
- [Leaflet](https://cran.r-project.org/web/packages/leaflet/). Create and customize interactive maps using the 'Leaflet' JavaScript library and the 'htmlwidgets' package. 
- [RColorBrewer](https://cran.r-project.org/web/packages/RColorBrewer/index.html). Provides color schemes for maps (and other graphics) designed by Cynthia Brewer as described [here](http://colorbrewer2.org).

# Finance
- [quantmod](https://cran.r-project.org/web/packages/quantmod/). Specify, build, trade, and analyse quantitative financial trading strategies.
- [blotter](https://github.com/braverock/blotter). Provides transaction infrastructure for defining transactions, portfolios and accounts for trading systems and simulation with portfolio support for multi-asset class and multi-currency portfolios.
- [PerformanceAnalytics](https://cran.r-project.org/web/packages/PerformanceAnalytics/). Econometric Tools for Performance and Risk Analysis.
- [EliteQuant_R](https://github.com/EliteQuant/EliteQuant_R). R based multi-threading, concurrent high-frequency trading platform that provides consistent backtest and live trading solutions.
- [zoo](https://cran.r-project.org/web/packages/zoo/). S3 Infrastructure for Regular and Irregular Time Series.
- [FactorAnalytics](https://github.com/braverock/FactorAnalytics). Linear factor model fitting for asset returns.
- [quanstrat](https://github.com/braverock/quantstrat). Transaction-oriented infrastructure for constructing trading systems and simulation. Provides support for multi-asset class and multi-currency portfolios for backtesting and other financial research.
- [FinancialInstrument](https://cran.r-project.org/web/packages/FinancialInstrument/index.html). Infrastructure for defining meta-data and relationships for financial instruments.
- [PortfolioAnalytics](https://cran.r-project.org/web/packages/PortfolioAnalytics/). Portfolio optimization and analysis routines and graphics.
- [RQuantLib](https://cran.r-project.org/web/packages/RQuantLib/index.html). Provide a standard open source library for quantitative analysis, modeling, trading, and risk management of financial assets.
- [portfolio](https://cran.r-project.org/web/packages/portfolio/index.html). Classes for analysing and implementing equity portfolios.
- [TTR](https://cran.r-project.org/web/packages/TTR/index.html). Technical Trading Rules.

# Functional data
- [fda](https://cran.r-project.org/web/packages/fda/). Set of functions developed to support functional data analysis as described in Ramsay, J. O. and Silverman, B. W. (2005) Functional Data Analysis. New York: Springer.
- [fda.usc](https://cran.r-project.org/web/packages/fda.usc/). Routines for exploratory and descriptive analysis of functional data such as depth measurements, atypical curves detection, regression models, supervised classification, unsupervised classification and functional analysis of variance.
- [fdapace](https://cran.r-project.org/web/packages/fdapace/index.html). Provides implementation of various methods of Functional Data Analysis (FDA) and Empirical Dynamics.
- [funData](https://cran.r-project.org/web/packages/funData/index.html). S4 classes for univariate and multivariate functional data with utility functions.
- [rainbow](https://cran.r-project.org/web/packages/rainbow/index.html). Bagplots, Boxplots and Rainbow Plots for Functional Data.
- [roahd](https://cran.r-project.org/web/packages/roahd/index.html). A collection of methods for the robust analysis of univariate and multivariate functional data, possibly in high-dimensional cases, and hence with attention to computational efficiency and simplicity of use.

# Regression
- [car](https://cran.r-project.org/web/packages/car/index.html). Functions to Accompany J. Fox and S. Weisberg,An R Companion to Applied Regression, Third Edition, Sage, 2019.
- [MASS](https://cran.r-project.org/web/packages/MASS/). Support Functions and Datasets for Venables and Ripley's MASS.
- [caret](https://cran.r-project.org/web/packages/caret/). Misc functions for training and plotting classification and regression models.
- [glmnet](https://cran.r-project.org/web/packages/glmnet/). Lasso and Elastic-Net Regularized Generalized Linear Models.
- [xgboost](https://cran.r-project.org/web/packages/xgboost/). Includes efficient linear model solver and tree learning algorithms, it can automatically do parallel computation on a single machine which could be more than 10 times faster than existing gradient boosting packages. It supports various objective functions, including regression, classification and ranking. 
- [quantreg](https://cran.r-project.org/web/packages/quantreg/). Estimation and inference methods for models of conditional quantiles.
- [np](https://cran.r-project.org/web/packages/np/). Nonparametric (and semiparametric) kernel methods that seamlessly handle a mix of continuous, unordered, and ordered factor data types. 
- [effects](https://cran.r-project.org/web/packages/effects/index.html).  Effect Displays for Linear, Generalized Linear, and Other Models.
- [lme4](https://cran.r-project.org/web/packages/lme4/). Fit linear and generalized linear mixed-effects models. The models and their components are represented using S4 classes and methods.
- [FWDselect](https://cran.r-project.org/web/packages/FWDselect/). A simple method to select the best model or best subset of variables using different types of data (binary, Gaussian or Poisson) and applying it in different contexts (parametric or non-parametric).

# Optimization
- [optimization](https://cran.r-project.org/web/packages/optimization/). Flexible Optimization of Complex Loss Functions with State and Parameter Space Constraints.
- [lpSolve](https://cran.r-project.org/web/packages/lpSolve). Interface to 'Lp_solve' v. 5.5 to Solve Linear/Integer Programs.
- [lpSolveAPI](https://cran.r-project.org/web/packages/lpSolveAPI/index.html). Provides an R interface to 'lp_solve', a Mixed Integer Linear Programming (MILP) solver with support for pure linear, (mixed) integer/binary, semi-continuous and special ordered sets (SOS) models.

# Spatial statistics
- [sp](https://cran.r-project.org/web/packages/sp/). Classes and methods for spatial data; the classes document where the spatial location information resides, for 2D or 3D data. Utility functions are provided, e.g. for plotting data as maps, spatial selection, as well as methods for retrieving coordinates, for subsetting, print, summary, etc.
- [sf](https://cran.r-project.org/web/packages/sf/index.html). Support for simple features, a standardized way to encode spatial vector data. Binds to 'GDAL' for reading and writing data, to 'GEOS' for geometrical operations, and to 'PROJ' for projection conversions and datum transformations.
- [npsp](https://cran.r-project.org/web/packages/npsp/index.html). Multidimensional nonparametric spatio-temporal (geo)statistics.


# Web scraping
- [rvest](https://cran.r-project.org/web/packages/rvest/). Easily Harvest (Scrape) Web Pages.
- [XML](https://cran.r-project.org/web/packages/XML/). Many approaches for both reading and creating XML (and HTML) documents (including DTDs), both local and accessible via HTTP or FTP. Also offers access to an 'XPath' "interpreter".
- [Rselenium](https://cran.r-project.org/web/packages/RSelenium/). Provides a set of R bindings for the 'Selenium 2.0 WebDriver' using the 'JsonWireProtocol' 
- [httr](https://cran.r-project.org/web/packages/httr/index.html). Useful tools for working with HTTP organised by HTTP verbs (GET(), POST(), etc).

# Computer vision
https://jeroen.github.io/munster2018/#26

# Packages development
- [usethis](https://cran.r-project.org/web/packages/usethis/). Automate package and project setup tasks that are otherwise performed manually. 
- [pkgdown](https://cran.r-project.org/web/packages/pkgdown/index.html). Generate an attractive and useful website from a source package. 
- [roxygen2](https://cran.r-project.org/web/packages/roxygen2/). Generate your Rd documentation, 'NAMESPACE' file, and collation field using specially formatted comments.
- [devtools](https://cran.r-project.org/web/packages/devtools/). Tools to Make Developing R Packages Easier.
- [profvis](https://cran.r-project.org/web/packages/profvis/index.html). Interactive Visualizations for Profiling R Code.

# Fun stuff
- [ggcats](https://github.com/R-CoderDotCom/ggcats). The geom you always wished for adding cats to ggplot2.
- [ggbernie](https://github.com/R-CoderDotCom/ggbernie). A ggplot2 geom for adding Bernie Sanders to ggplot2.
- [TurtleGraphics](https://cran.r-project.org/web/packages/TurtleGraphics/) - An R implementation of vector graphics using a relative cursor (the "turtle") upon a Cartesian plane.
- [fun](https://cran.rstudio.com/web/packages/fun/). Collection of R games and other funny stuff, such as the classic Mine sweeper and sliding puzzles.
- [Fortunes](https://cran.r-project.org/web/packages/fortunes/). A collection of fortunes from the R community.
- [cowsay](https://github.com/sckott/cowsay). ASCII art animals in R console.
- [drumr](https://github.com/jamesmartherus/drumr). Turn R into a Drum Machine. 
- [ggphysics](https://github.com/chang/ggphysics). Physics animations in ggplot2, just for fun. 
- [raptors animation](https://github.com/imjakedaniels/raptors_animation). Using gganimate to bounce emoji basketballs over the course of a game. 
- [brownianbridge](https://github.com/djnavarro/brownianbridge). Contains scripts used to draw various "Brownian bridge" animations that to explore some of the functionality of the gganimate package.
- [pushoverr](https://cran.r-project.org/web/packages/pushoverr/index.html). Send push notifications from R to mobile devices or the desktop. These notifications can display job status, results, scraped web data, or any other text or numeric data.
- [BRRR](https://github.com/brooke-watson/BRRR). Let Gucci Mane tell you when your script is done.
- [meme](https://cran.r-project.org/web/packages/meme/index.html). Create memes in R.
- [xkcd](https://cran.r-project.org/web/packages/xkcd/index.html). Plotting ggplot2 Graphics in an XKCD Style.
- [beepr](https://cran.r-project.org/web/packages/beepr/index.html). The main function of this package is beep(), with the purpose to make it easy to play notification sounds on whatever platform you are on. It is intended to be useful, for example, if you are running a long analysis in the background and want to know when it is ready.
- [twitteR](https://cran.r-project.org/web/packages/twitteR/). Send Tweets from R.
- [CatterPlots](https://github.com/Gibbsdavidl/CatterPlots). Cat themed scatter plots.
- [crayon](https://cran.r-project.org/web/packages/crayon/index.html). Colored Terminal Output.




More soon...

