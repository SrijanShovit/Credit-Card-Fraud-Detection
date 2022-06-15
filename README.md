# Credit-Card-Fraud-Detection

The dataset was imbalanced

Algos tried on both imbalanced and balanced dataset with close notice on precision,recall & f1-score

- Shallow Neural Network
- GradientBoostingClassifier
- SVM
- Logistic Regression
- RandomForest

### comparison of the models (for fraud)

|         Models tried                             |       P    |     R    |   f-1   |
|--------------------------------------------------|------------|----------|---------|
|shallow_nn on val                                 |     0.68   |  0.78    | 0.73    |
|                                                  |            |          |         |
|GradientBoostingClassifier on val                 |     0.67   |  0.67    | 0.67    |
|                                                  |            |          |         |
|SVM on val(1000)                                  |     0.66   |   0.64   |  0.65   |
|                                                  |            |          |         |
|Logistic on val                                   |     0.73   |   0.53   |  0.61   |
|                                                  |            |          |         |
|Random forest on val                              |     0.81   |   0.47   |  0.60   |
|                                                  |            |          |         |
|SVM on val(5000)                                  |     0.18   |   0.83   |  0.29   |

### comparison of the models on balanced dataset

|         Models tried                             |       P    |     R    |   f-1   |
|--------------------------------------------------|------------|----------|---------|
|shallow_nn on val                                 |            |          |         |
|Not Fraud                                         |      0.89  |   1.00   |  0.94   |
|Fraud                                             |      1.00  |   0.87   |  0.93   |    
|                                                  |            |          |         |
|GradientBoostingClassifier on val                 |            |          |         |
|Not Fraud                                         |      0.94  |   0.92   |  0.93   |
|Fraud                                             |      0.92  |   0.94   |  0.93   |  
|                                                  |            |          |         |
|SVM on val(1000)                                  |            |          |         |
|Not Fraud                                         |      0.96  |   0.93   |  0.94   |
|Fraud                                             |      0.93  |   0.96   |  0.94   |  
|                                                  |            |          |         |
|Logistic on val                                   |            |          |         |
|Fraud                                             |     0.96   |   0.93   |  0.94   |
|Not fraud                                         |     0.93   |   0.96   |  0.94   |
|                                                  |            |          |         |
|Random forest on val                              |            |          |         |
|Not Fraud                                         |      0.99  |   0.92   |  0.95   |
|Fraud                                             |      0.98  |   0.91   |  0.95   |  
|                                                  |            |          |         |

### Conclusion:

I feel SVM to be best suited!!
