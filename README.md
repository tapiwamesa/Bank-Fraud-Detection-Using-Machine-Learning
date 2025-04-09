# Fraud-Detection-Using-Machine-Learning
A supervised Machine Learning model for fraud detection on financial data.


In this project we look at historical financial data, thus transactional data under different destinations of purchase or withdrawal. This is an important aspect for banks, fincance companies and the customers as well as it enbales these entities to detect fraud quickly and accurately from just transactional patterns. Much detail will be provided in the notebook step by step as we get.

This project evaluates three machine learning models (Logistic Regression, Random Forest, and Gradient Boosting) on a **class-imbalanced dataset**, where standard accuracy metrics prove misleading. Despite all models showing poor precision (0.02–0.03) due to extreme class imbalance, **Logistic Regression emerges as the most viable** because:  

1. **Best AUC (0.667)**: Superior class separation compared to Random Forest (AUC=0.573).  
2. **Balanced Recall (0.507)**: Captures 50% of true positives without sacrificing as much precision as Gradient Boosting.  
3. **Robustness**: Avoids Random Forest's overfitting (high accuracy but near-random AUC) and Gradient Boosting's precision collapse (0.025).  

**Key Challenge**: Improve model performance by addressing class imbalance and optimizing precision-recall trade-offs. 

