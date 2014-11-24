Exploring Regression in R
========================================================
author: Developing Data Products Project, aoshotse 
date: 11/2014

Introduction
========================================================

The purpose of this app is to illustrate some of the necessary aspects of choosing variables of a data set to include in a regression model, and some of the key ways to evaluate the given model.        

In 5 different data sets, the user is allowed to specify predictor variables from the data set for inclusion into a regression model against a pre-specified response variable.

The goal is to build a model that explains the highest amount of variance while minimizing variance inflation, avoiding multicolinearity, and keeping an eye on the residuals (from the plots). 



Model Assessment
========================================================

The user can then assess the constructed model by considering the following resulting outputs: 

- The model summary (variable coefficients, residual stats, p-values, etc.)
- A plot of the percent of variance explained by the model
- The variance inflation values for the variables specified in the model
- The residual plots of the model


Example Outputs
========================================================

![plot of chunk unnamed-chunk-1](Exploring_Regression_in_R-figure/unnamed-chunk-1-1.png) 

Conclusion
========================================================
The user gets an exercise in model specification by experiencing first hand such things as:
- How colinear variables may impact estimates     
- How certain variables in a data set may or may not contribute to variance explained (sometimes against intuition) 
- How residual statistics may not tell the full story of residual behavior

All in all, the app is just a fun way to explore regression diagnostics with a few data sets and a bit of visual aid.
