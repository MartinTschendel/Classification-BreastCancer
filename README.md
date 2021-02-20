# Classification-BreastCancer
Using different classification models to predict breast cancer.<br>
Source of the dataset: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Original%29 <br>
This breast cancer databases was obtained from the University of Wisconsin Hospitals, Madison from Dr. William H. Wolberg.<br><br>

<b>Model Performance</b><br>
* Logistic Regression：Accuracy： 96.43%； St.-Dev.: 2.52 %
* Decision Tree：Accuracy： 93.92%； St.-Dev.: 2.68 %
* K-NN：Accuracy： 93.92%； St.-Dev.: 2.68 %
* Naive Bayes：Accuracy： 96.25%； St.-Dev.: 2.82 %
* Random Forest：Accuracy： 95.53%； St.-Dev.: 2.68 %
* Kernel SVM：Accuracy： 96.43%； St.-Dev.: 3.48 % (improvement with Grid Search, that finds best model parameters: 96.6 %; St.-Dev.: 2.58%) 
* SVM: Accuracy: 95.53 %; St.-Dev.: 2.68 %
* XGBoost: 95.71 %; St.-Dev.: 2.67 % (improvement with Grid Search: 96.79 %; St.-Dev.: 2.08%)
* CatBoost: 96.96 %; St.-Dev.: 2.4 %
<br>
CatBoost has the best performance. 
