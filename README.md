# Heart-Stroke-Prediction
Comparative study of different ML Predictive models for predicting heart stroke.
This project presents a comparative study of various machine learning (Naive Bayes, Decision Tree, Random Forest, Logistic Regression, SVM) and deep learning (ANN with embedding layers) algorithms for predictive modeling. The aim is to analyze the performance of different algorithms on a given dataset (heart.csv) and identify the most effective approach for the task at hand.

## Dataset
The dataset used for this study contains information about individuals, including demographic attributes, medical history, and lifestyle factors. The target variable is "stroke". The dataset consists of 5110 samples and 11 features.

## Algorithms Explored
1. Naive Bayes Classifier
2. Decision Tree Classifier
3. Random Forest
4. Logistic Regression
5. Support Vector Machine (SVM)
6. Artificial Neural Network (with Embedding Layers)

## Implementation
The project is implemented using Python and various libraries such as scikit-learn for traditional ML algorithms and TensorFlow/Keras for deep learning models. The code includes data preprocessing, model training, evaluation, and comparative analysis.

## Results
The accuracies achieved by each model are as follows:
- Naive Bayes Classifier: 87.01%
- Decision Tree Classifier: 93.89%
- Random Forest: 93.66%
- Logistic Regression: 93.58%
- Support Vector Machine (SVM): 93.74%
- Artificial Neural Network (ANN): 99.41%

## Conclusion
Based on the accuracies obtained from the analysis, the Naive Bayes Classifier (NBC) shows decent accuracy and simplicity, making it a viable option unless computational constraints are significant. The Decision Tree Classifier (DTC) and Random Forest (RF) both exhibit good accuracy and interpretability, with RF providing additional robustness as an ensemble method. Logistic Regression (LR) offers comparable accuracy while maintaining interpretability, suggesting its retention unless higher accuracy is required. The Support Vector Machine (SVM) displays high accuracy but may be computationally intensive. Lastly, while Artificial Neural Networks (ANNs) offer high accuracy, their computational cost should be considered, especially if resources are limited. In summary, model selection should balance accuracy, computational cost, interpretability, and task suitability, ensuring an informed decision-making process.
