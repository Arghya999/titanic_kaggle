# titanic_kaggle
my solution to the Titanic survival prediction problem on Kaggle.
The repository includes scripts for feature selection, alternate strategies for data modelling, the original test &amp; train data sets and the visualizations plots generated for the same. All code snippets are written in R.

Titanic survival prediction Problem
http://www.kaggle.com/c/titanic-gettingStarted

In this popular challenge, the aim is to predict what sorts of people were likely to survive the Titanic disaster based on attributes such as gender, class, ticket details , age category e.t.c . 

The datasets can be found in 'data' folder.

train.csv (59.76 kb)  
test.csv (27.96 kb)

Following R packages are used.

seqinr: Biological Sequences Retrieval and Analysis
https://cran.r-project.org/web/packages/seqinr/index.html

e1071: Misc Functions of the Department of Statistics, Probability Theory Group (Formerly: E1071), TU Wien
https://cran.r-project.org/web/packages/e1071/index.html


party: A Laboratory for Recursive Partytioning
https://cran.r-project.org/web/packages/party/index.html


Amelia: Amelia II: A Program for Missing Data
https://cran.r-project.org/web/packages/Amelia/index.html

ggplot2: An Implementation of the Grammar of Graphics
https://cran.r-project.org/web/packages/ggplot2/index.html


https://cran.r-project.org/web/packages/corrgram/index.html
corrgram: Plot a Correlogram


## API Reference

Following scripts need to be run seprately

Titanic_eda.R  -- All exploratory data analysis approaches analyzing data sets to summarize their main characteristics, building plots, creating map of missing features e.t.c

titanic_regression_logistic.R -- Feature clean up, split of data set into train test, cross validation & survival prediction using Logistic Regression

titanic_RF.R -- Feature clean up, split of data set into train test, cross validation & survival prediction using Random Forest

titanic_svm.R -- Feature clean up, split of data set into train test, cross validation & survival prediction using Support Vector Machine

bagged_result.R -- Feature clean up, split of data set into train test, cross validation & survival prediction using all the above methods and then bagging the results.


## Plots

Some of the data visualizations are saved as pdfs in eda_ggplot folder. Code for the same can be found in Titanic_eda.R. The remaining visualizations like missmaps are printed in console itself.

Age_Distribution.pdf

Age_Vs_Survival.pdf

Embarked_Vs_Survival.pdf

Fare_Distribution.pdf

PClass_Distribution_Bar.pdf

survival_vs_sex.pdf

survived_vs_died.pdf
