## [Phi Transformation for Polynomial Features](https://www.deep-ml.com/problems/84) ![Difficulty](https://img.shields.io/badge/-Easy-brightgreen)

Write a Python function to perform a Phi Transformation that maps input features into a higher-dimensional space by generating polynomial features. 

The transformation allows models like linear regression to fit nonlinear data by introducing new feature dimensions that represent polynomial combinations of the original input features.

The function should take a list of numerical data and a degree as inputs, and return a nested list where each inner list represents the transformed features of a data point. If the degree is less than 0, the function should return an empty list.

### Example:

**Input:**

```python
data = [1.0, 2.0]
degree = 2
```


**Output:**

```[[1.0, 1.0, 1.0], [1.0, 2.0, 4.0]]```
