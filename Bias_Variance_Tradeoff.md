## Bias is the simplifying assumptions made by the model to make the target function easier to approximate.
## Variance is the amount that the estimate of the target function will change given different training data. 
## Trade-off is tension between the error introduced by the bias and the variance

![Screenshot (27)](https://user-images.githubusercontent.com/69463767/189346457-be3dc04d-86e2-4e4d-9be4-2c85c6f4c7a2.png)

## Training set error will tell you about bias, if it is high, bias is generally high
## Dev set or test set error will tell you about variance, if it is high then generally variance is high

![image](https://user-images.githubusercontent.com/69463767/189346784-fb7388a8-995f-44b5-aa8a-6593ddd4474d.png)

## The above image has high bias because it is mostly linear, but a curved function was needed to fit them well
## It is also high variance because it is overfitting on those noises by being too flexible in the middle.
