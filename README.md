Slides and code for the _Modeling in the Tidyverse_ short course on Wednesday, May 29 2019 at SDSS (Symposium on Data Science and Statistics).

To prepare, please run this code to install and verify the packages:

```r
install.packages(
  c("tidymodels", "xgboost", "tidyposterior", "AmesHousing", "readr"), 
  repos = "http://cran.r-project.org"
)

library(tidymodels)
library(xgboost)
library(tidyposterior)
library(AmesHousing)
``` 

Warnings here are okay, errors are not. 

We will have Rstudio Server instances to use if you can't (or don't want to) install these packages. 