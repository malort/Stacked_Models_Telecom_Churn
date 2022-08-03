# Stacked_Models_Telecom_Churn
The dataset comes from a telecommunications company:
https://drive.google.com/file/d/1dPCG76ST6NohYKtVMGv6HpFL-jD5p1eJ/view

The goal is to predict customer churn using Machine Learning.

## Requirements:

```pandas:``` Data analysis and manipulation tool.

```matplotlib:``` Visualization library.

```seaborn:``` Data visualization library based on matplotlib, it enhances the style of matplotlib plots.

```Numpy:``` Numerical analysis library.

```scikit-learn:``` Machine Learning library.

```XGBoost:``` Decision-tree-based ensemble Machine Learning algorithm.

```LightGBM:``` Gradient boosting framework that uses tree based learning algorithms.

## Description: 

The first part comprises the cleaning process and a concise exploratory data analysis. 

The second part describes the model definition process. Several models such as Random Forest, XGBoost, SVM and AdaBoost are used as base estimators and LightGBM as the final estimator in a stacked model. 

The following diagram depicts the final model architecture.



![Stacked_Diagram3](https://user-images.githubusercontent.com/20369543/153266129-b1caa9be-ec1a-4a4e-b3aa-fb49553bde41.png)
