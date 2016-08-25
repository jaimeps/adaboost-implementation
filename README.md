
## Implementation of AdaBoost classifier

### Description

This is an implementation of the AdaBoost algorithm for a two-class classification problem. 

### Methods

The algorithm sequentially applies a weak classification to modified versions of the data. By increasing the weights of the missclassified observations, each weak learner focuses on the error of the previous one. The predictions are aggregated through a weighted majority vote. <br />
<img src="https://github.com/jaimeps/adaboost-implementation/blob/master/images/adaboost_algo.png" width="400"> <br />

### Example

Using the Hastie (10.2) dataset, we can appreciate a significant reduction in the error rate as we increase the number of iterations. <br />
<img src="https://github.com/jaimeps/adaboost-implementation/blob/master/images/error_rate.png" width="400"> <br />

### References
- Trevor Hastie, Robert Tibshirani, Jerome Friedman - *The Elements of Statistical Learning*