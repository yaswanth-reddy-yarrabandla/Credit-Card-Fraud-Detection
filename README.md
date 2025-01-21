# Credit-Card-Fraud-Detection 💳🔍

## Overview  
This project addresses the critical issue of credit card fraud by leveraging advanced machine learning techniques and the **Synthetic Minority Over-Sampling Technique (SMOTE)** to handle the class imbalance inherent in fraud detection datasets. The goal is to enhance fraud detection accuracy and reliability, providing a robust solution for real-world financial applications.

---

## Key Highlights  
- **Dataset**:  
  - Sourced from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud), the dataset includes **284,807 transactions** made by European cardholders in September 2013.  
  - Only **492 transactions (0.172%)** are fraudulent, reflecting a significant class imbalance.

- **Techniques**:  
  - **Data Preprocessing**: Addressed outliers and ensured data integrity for accurate modeling.  
  - **SMOTE**: Balanced the dataset by generating synthetic samples for the minority class.  
  - **Sampling Strategies**: Explored both under-sampling and SMOTE-based over-sampling to evaluate model performance.  

- **Models**:  
  - Implemented Decision Tree, Random Forest, Gradient Boosting, AdaBoost, Multi-Layer Perceptron (MLP), and Support Vector Machine (SVM).  
  - **Gradient Boosting** emerged as the best-performing model, with an **AUC of 0.99** and a high recall of **95%**.  

- **Evaluation Metrics**: Focused on **recall**, **F1-score**, and **AUC** for a balanced assessment of model effectiveness in detecting fraud.  

---

## Results  

| Model               | Accuracy | AUC  | Recall | F1-Score |
|---------------------|----------|------|--------|----------|
| Decision Tree       | 92.77%  | 0.92 | 90.90% | 88.23%   |
| Random Forest       | 95.49%  | 0.97 | 90.15% | 92.25%   |
| Gradient Boosting   | 96%     | 0.99 | 95%    | 96%      |
| AdaBoost            | 94%     | 0.90 | 88%    | 91%      |
| MLP (50 Neurons)    | 82%     | 0.89 | 78%    | 82%      |
| SVM                 | 95%     | 0.99 | 93%    | 95%      |

---

## Key Features  
- **Explainability**: Identified **V11**, **V3**, and **V14** as the top predictive features for fraud detection.  
- **Visualization**: Included **confusion matrix** and **ROC curve** to demonstrate model performance.  
- **Deployment**: Developed a scalable and reliable framework suitable for real-world applications.

---

## Future Scope  
- **Investigate Advanced Architectures**: Explore advanced neural network architectures and optimize hyperparameters to capture complex patterns.  
- **Real-Time Detection**: Extend the approach to include real-time fraud detection capabilities for evolving fraudulent tactics.  

---

Feel free to explore, contribute, and enhance this repository to further strengthen fraud detection systems! 🚀
