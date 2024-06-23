# r-scripts: A curation of R scripts to get started with various aspects in R

Creating sample R scripts that people can download to get started with their codes in R

## Websites

 - https://r-scripts.rpkg.net
 - https://rscripts.rpkg.net

## Want to contribute?

If you want to contribute scripts, please create and issue and attach your R scripts to it. We will incorporate accordingly.


## Requirement for all script

All scripts will contain the following structure to organize the code

```

############################################################################
############################################################################
##  Document Path: C:/...
##
##  Author: Obinna Obianom
##
##  Date: 2024-06-22
##
##  Title: A simple bar plot
##
##  Description:
##
##  Required Files:
##
##  Exported Files:
##
##  R Version: R version 4.0.2 (2020-06-22)
##
#############################################################################
#############################################################################

# clear environment, console and unload all packages to maintain script consistency
quickcode::clean(
  setwd = './', # set working directory
  source = c(), # script paths to be sourced in
  load = c(), # RData files to load in
  clearPkgs = TRUE # clear all packages
)

# load required packages
quickcode::libraryAll(
  ggplot2 # package for plotting
)


# script body





# session information
  sessionInfo()

```
