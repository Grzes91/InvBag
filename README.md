# Inverse Bagging algorithm implementation 

This file contains an R implementation of the Inverse Bagging algorithm. Given two sets: a training one containing observations from a certain distribution and a testing one which can include as well anomalous observations generated from a different unknown distribution; the algorithm returns scores for the testing set observations related to evidence of their anomalous propoerties.

To install the package directly from the GitHub page use 
devtools::install_github("Grzes91/InvBag")
and for documentation and examples run ?RunInvBag
