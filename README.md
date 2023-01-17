# xlsx_data_classification
## Data Preprocessing
- Handling Null Values 
- Feature Scaling
- Handling Categorical Variables

## Results
By using Non-Tree based models
| Model |  F1 Score  (%) |
| --- | --- |
| Logistic Regression  |  88.88|
| Naive Bayers | 81.18 |
|SVM (using linear kernel) | 90.74 |
| SVM (using sigmoid kernel)| 48.14 |
| SVM (using RBF Kernel)| 88.88 |
|**SVM (using poly RBF kernel)** | **92.59** |
|K-nearest Neighbors | 81.18 |

By using Tree based models

| Model |  F1 Score  (%) |
| --- | --- |
| Decision Tree Classifier  |  98|
| Random Forest Classifier | 94.44 |
|**XGBoost Classifier** | **100** |

By using Convolutional Neural Network 

| Model |  F1 Score  (%) |
| --- | --- |
| Custom CNN  |  71.15|





