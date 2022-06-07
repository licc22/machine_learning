# machine_learning
## Machine learning strategy
### basic algorithm
** SVM ** a good choice, give a not bad result
you should focus on C and gamma, which affect model bias and variance, and of course kernel is important. 
** Decision Tree ** has a reasonable explaining
** logistic regression ** 

### how to find the best parameter
** grid search ** 
** bayesian search ** 

##  integrated approach
** bagging **
trains n base learners(bootstrap sampling) in parallel, 
decrease variance, 
make model(eg decision tree, not linear regression) more stable.
application random forrest 
**  boosting **
combines weak learners into a strong one,
reduce bias,
focus on wrong predictions,
eg adaboost, gradient boosting.
** stacking **
