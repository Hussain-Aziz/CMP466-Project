# Predicting customer behaviour
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)

This repo uses the [in vehicle coupon recommendation dataset](https://doi.org/10.24432/C5GS4P) to predict customer behaviour. The dataset describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the driver whether he will accept a coupon.

The models used were Decision Tree, Naive Bayes, KNN, SVM, and Random Forest. The models were trained using 5-fold cross validation and the accuracy, f1, precision, recall, and AUC were calculated. The results are shown below.

| Model          | Accuracy | F1    | Precision | Recall | AUC   |
|----------------|----------|-------|-----------|--------|-------|
| Decision Tree  | 0.685    | 0.738 | 0.697     | 0.787  | 0.729 |
| Naive Bayes    | 0.660    | 0.723 | 0.670     | 0.787  | 0.702 |
| KNN            | 0.684    | 0.735 | 0.702     | 0.772  | 0.728 |
| SVM            | 0.700    | 0.749 | 0.713     | 0.789  | 0.743 |
| Random Forest  | 0.706    | 0.757 | 0.710     | 0.812  | 0.759 |

The best results were obtained using Random Forest with an accuracy of 0.71. The [state of the art](https://ejournal.seaninstitute.or.id/index.php/Ekonomi/article/view/506) is 0.77.
