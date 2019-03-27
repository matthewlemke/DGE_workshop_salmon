---
title: "R refresher"
author: "Meeta Mistry, Radhika Khetani, Mary Piper"
---

Approximate time: 45 minutes

## Learning Objectives

* Describe the various data types and data structures (including tibbles) used by R
* Use functions in R and describe how to get help with arguments
* Describe how to install and use packages in R
* Use the pipe (%>%) from the dplyr package
* Describe the syntax used by ggplot2 for making plots

## Getting started

**Exercise:**

1 Create a new project called `R_refresher`
2 Create a new R script called `reviewing_R.R`
1 Load the tidyverse and ggplot2 libraries
1 Create the following folders in the project directory - `data`, `figures`
1 Download a counts file to the `data` folder by [right-clicking here]()
1 Use `read.csv()` to read in the downloaded file and save it in the object/variable `counts`
1 What is the data structure of `counts`?
1 Summarize the contents of the `meta` object, how many data types are represented?
1 Create a data frame called `meta` that looks like the table shown below:
 
1 Add row names to the `meta` data frame, and have them be identical to the column names in `counts`
1 Create a list called `project1` with the `meta` and `counts` objects
1 
