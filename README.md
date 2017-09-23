# phishing-website-detection
Final master's degree project. 

I used this dataset https://archive.ics.uci.edu/ml/datasets/phishing+websites and got good results using xgboost and a simple perceptron.

![alt text](https://github.com/jvicentem/phishing-website-detection/raw/master/accuracy_ranking.png)

Undersampling techniques were used such as One-Sided Selection and Condensed Nearest Neighbor and they improved massively the training time of SVM models and the accuracy/precision/F1 measures of SVM with RBF Kernel.

