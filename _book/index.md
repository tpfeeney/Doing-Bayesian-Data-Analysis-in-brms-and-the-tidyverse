--- 
title: "*Doing Bayesian Data Analysis* in brms and the tidyverse"
subtitle: "version 0.0.1"
author: ["A Solomon Kurz"]
date: "2019-10-19"
site: bookdown::bookdown_site
output: bookdown::gitbook
documentclass: book
geometry:
  margin = 0.5in
urlcolor: blue
highlight: tango
header-includes:
  \usepackage{underscore}
  \usepackage[T1]{fontenc}
link-citations: yes
github-repo: ASKurz/Doing-Bayesian-Data-Analysis-in-brms-and-the-tidyverse
twitter-handle: SolomonKurz
description: "This project is an attempt to re-express the code in Kruschke's (2014) textbook. His models are re-fit in brms, plots are redone with ggplot2, and the general data wrangling code predominantly follows the tidyverse style."
---

# What and why {-}

Kruschke began his text with "This book explains how to actually do Bayesian data analysis, by real people (like you), for realistic data (like yours)." In the same way, this project is designed to help those real people do Bayesian data analysis. My contribution is converting Kruschke's JAGS code for use in Bürkner's [**brms** package](https://github.com/paul-buerkner/brms), which makes it easier to fit Bayesian regression models in **R** using Hamiltonian Monte Carlo (HMC). I also prefer plotting and data wrangling with the packages from the [**tidyverse**](http://style.tidyverse.org). So we'll be using those methods, too.

This project is not meant to stand alone. It's a supplement to the second edition of [Kruschke’s *Doing Bayesian Data Analysis*](https://sites.google.com/site/doingbayesiandataanalysis/). Please give the source material some love.

## Caution: Work in progress {-}

The first release of this project only contains chapters 1 through 5, the first section of the text. Most of the remaining chapters have completed drafts and just need another round of edits. I'll add them, soon.

More importantly, there are sections and chapters in this project I have yet to work through. In addition to checking in here, you can follow my GitHub [progress log](https://github.com/ASKurz/Doing-Bayesian-Data-Analysis-in-brms-and-the-tidyverse/issues/1). In that log, I will point out figures or sections I'm having trouble with. Please feel free to offer insights and suggestions, there.


