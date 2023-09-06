# Model Complexity and Overfitting

During the phase of model selection, it is always preferable choosing a simpler model over the complex ones. It aligns with Occam's Razor terminology that simpler explaination (model) is always better to complex explaination. 

In the world of Machine Learning, it is important to understand the term of overfitting and underfitting due to practitioners would always encounter this during the development phase. Overfitting is a tendency of capturing noises in the training data, hence the model perform greatly in the training data, but performs poorly on the out-of-sample data. Meanwhile on the other spectrum, underfitting is a situation that the model cannot capture the actual relationship between data and the target variables.

The solution of overfitting depends on each model parameter, for instance applying maximal pruning for tree based model, applying a correct level of regularisation for the L1, L2 for the linear regression, reduce the hidden layer for Neural Network, ETC. In contrary, underfitting needs injecting more complexity to be able to capture the relationship from the data.

---
### Metadata
- **Author**: Yogi Cahyono.
- **Created**: September, 5th 2023.
- **Modified**: September, 5th 2023.