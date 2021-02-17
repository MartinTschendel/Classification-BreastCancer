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
* Kernel SVM：Accuracy： 96.43%； St.-Dev.: 3.48 %
* SVM: Accuracy: 95.53 %; St.-Dev.: 2.68 %

<b>Application of Grid Search</b><br>
Kernel SVM has the best performance. We can even improve the performance with Grid Search, that finds the best parameters of a model.<br>
Final performance of Kernel SVM after the application of Grid Search: Accuracy: 96.6 %
