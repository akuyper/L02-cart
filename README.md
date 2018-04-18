# CART Lab II (L04)

Download the repository as a zip folder and begin an R project for this lab. The zip folder will contain instructions (repeated below) and a template to get an Rmd file started.

## Overview

The main goal of this lab is to continue practicing the application of tree-based methods (i.e., classification and regression trees).

## Datasets

We have split the `wildfires.csv` dataset into a training dataset (`wildfires_train.csv`) and test dataset (`wildfires_test.csv`). They are contained in the **data** subdirectory along with a codebook.  

## Exercises

Please complete the following exercises. The document should be neatly formatted. 

#### Exercise 1 
The total area burned by a wildfire is of great concern to government planners. This is captured by the variable `burned` in the `wildfires` dataset. Applying boosting, bagging, and random forests methods to build candidate regression trees to predict the total area burned by a wildfire (`burned`). Include a multiple linear model that uses all appropriate predictors for comparison. Compare the estimated test errors for each model to determine which is best. **Exclude `wlf` as a predictor.** 

<br><br>

#### Exercise 2
Located in the northeast of the wilderness area is a wildlife protection zone. It is home to several rare and endangered species, and thus conservationists and park rangers are very interested in whether a given wildfire is likely to reach it. Applying boosting, bagging, and random forests methods, build candidate classification trees that predict whether a wildfire will reach this zone, as determined by the indicator variable `wlf`. Include a multiple linear logistic model that uses all predictors for comparison. Compare the estimated test errors for each model to determine which is best. **No exclusion on which varibles to use as predictors.** 
