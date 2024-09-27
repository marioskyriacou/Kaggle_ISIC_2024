# Kaggle_ISIC_2024
## Collaborators

| [Ioannis Demetriades](https://github.com/marioskyriacou) | [Marios Kyriacou](https://github.com/IoannisDem)|
|:---------------------------------:|:---------------------------------:|

The Kaggle competition for Skin Cancer Detection, utilizing the ISIC-2024 dataset, was divided into two phases:
(a) image classification and (b) tabular data classification. In the tabular phase, an XGBoost (XGB) model
was employed, incorporating hyperparameter tuning and repeated stratified K-fold cross-validation for optimal
performance. Additionally, an Artificial Neural Network (ANN) model was used, where data was split using a ratio
matrix to downsize the majority class, while SMOTE was applied to oversample the minority class, ensuring better
class balance.
