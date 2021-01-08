# House Prices - Advanced Regression Techniques

The challenge was a [Kaggle competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques).

My kernel walks through some of the basic data preprocessing and preparation steps -
* Encoding categorical values
* Handling missing values
* Normalizing data
* Feature engineering by creating interactions
* Dimensionality reduction using PCA

Outlier detection is not part of the kernel. I checked for outliers but removing/imputing outlier values deterioriated performance on the test dataset.

For the modeling step, I used only linear regression. Kaggle used root mean squared logarithmic error to measure model performance. My model had a RMSLE of 0.01254 on the validation set and a RMSLE of 0.14918 on the test set.

Here is a [link](https://www.kaggle.com/rmitra/housing-preprocess-pca-lin-reg-rmsle-0-15) to my notebook on Kaggle. to my notebook on Kaggle.
