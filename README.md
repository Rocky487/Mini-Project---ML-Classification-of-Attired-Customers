# Machine Learning Project of Classification
A classic classification problem found from Kaggle aiming to identify attrited customers of a bank. By preprocessing the data with the undersampling, weighting and one-hot-encoding techniques, a random forest and a XGBoost classification models are built upon parameter tuning and compared according to the recall score (since cost of false negative >> cost of false positive). Both models have acquired a score > 0.9, with the latter taking a small lead. The confusion matrix results of both are shown below:

![image](https://github.com/user-attachments/assets/a4277c9a-aba4-4638-8210-3d7b0fff2d6d)

To run randomforest.ipynb and XGBoost.ipynb successfully, please set them up in a Google Colab environment, with bankrefined.csv located in your own Colab Notebooks folder.

My key takeaways from this project:
1. Concepts behind decision tree, random forest and XGBoost and their parameters
2. The basic workflow of machine learning and use of pipeline
3. Pros and cons of parameter tuning with Bayesian, random and grid searches
4. Different types of evaluation metrics
