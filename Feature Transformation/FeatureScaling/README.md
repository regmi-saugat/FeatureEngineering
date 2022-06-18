# Feature Scaling
Feature Scaling is a method used to standardize the range of independent features present in the data in fixed range. It is also known as data normalization and is performed during the data preprocessing steps

## They are two types:
  - Standardizaiton (Z-score Normalization)
  - Normalization

### Standardization:
Standardization is the scaling technique where the value are centered around mean with unit standard deviation (SD). The mean of the attribute become 0 and resultant distribution has unit standard deviation.

### Normalization:
Normalization is the technique often applied as part of data prepration for machine learning. The goal of normalization is to change the value of numeric columns in the dataset to use common scale, without distorting differences in the ranges of values or loosing information.

#### Types of Normalization
- MinMaxScaling: It is used when we need centered data
- Mean Normalization: It is used to rescale in the range of features to scale the range in [-1,1]
- Maximum Absolute Scaling: It scales the data in its maximum value.
- Robust Scaling: It is one of the best scaling technique when we have outliers present in our dataset.
