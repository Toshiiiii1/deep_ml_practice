## [Single Neuron](https://www.deep-ml.com/problems/24) ![Difficulty](https://img.shields.io/badge/-Easy-brightgreen)

Write a Python function that simulates a single neuron with a sigmoid activation function for binary classification, handling multidimensional input features. The function should take a list of feature vectors (each vector representing multiple features for an example), associated true binary labels, and the neuron's weights (one for each feature) and bias as input. It should return the predicted probabilities after sigmoid activation and the mean squared error between the predicted probabilities and the true labels, both rounded to four decimal places

### Example:

**Input:**

```
features = [[0.5, 1.0], [-1.5, -2.0], [2.0, 1.5]]
labels = [0, 1, 0]
weights = [0.7, -0.4]
bias = -0.1
```


**Output:**

```([0.4626, 0.4134, 0.6682], 0.3349)```
