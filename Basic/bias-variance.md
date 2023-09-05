# Bias Variance Trade-off

Bias Variance Trade-Off is a terminology to explain the generalisation of machine learning model. For every model, it predicts the target variables with formula `f(x) = mx + w` with `w` being a noise that the model `f(x)` cannot predict and its distribution assumed to gaussian distribution. The lower the bias and variance the better the model.

To understand how the model fits well to the data, we can decompose the error of the `y` into three part: 

- **Bias**: How close the prediction value to the actual value. A non-complex model tends to oversimplifies the problem by having higher bias and cannot capture signals from the data training data pretty well. The lower of the Bias value the better.
- **Variance**: How much the error of the model change with regards to the input data. A sophisticated or complex model tends to fit the training data too tightly and captures the noises from the data. As the result, small differences in the data would result the prediction dramatically. Lower variance of the model the better.
- **Irreducible Error**: inherent error that cannot be captured by the model.

The trade-off between bias and variance could be a way to understand how to interpret the model predictability. For instance, a scientist work on a project that predict the price of a housing with multitude of independent variables. A simplest model like linear regression will produce a high bias and low variance result, because linear model oversimplifying the problem. Meanwhile on the other side of the spectrum, a complex model like Neural Network (NN) tends to produce a low bias and high variance prediction. NN produces more accurate result but it varies widely to the input variables.

It is important to understand on how get a balance between Bias and Variance tradeoff in the machine learning prediction. To deal with Low-Variance and High-Bias model, it advisable to add or choose more complex model. On the other hand, adding more data or perform feature engineering would help the high variance and low bias problem.

---
### Metadata
- **Author**: Yogi Cahyono.
- **Created**: September, 5th 2023.
- **Modified**: September, 5th 2023.
