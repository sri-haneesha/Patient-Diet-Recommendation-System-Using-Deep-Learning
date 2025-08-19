# Patient-Diet-Recommendation-System-Using-Deep-Learning
**Overview**
This project develops a deep learning-based patient diet recommendation system that suggests suitable food products based on patients’ medical records, physical attributes, and nutritional requirements. The system integrates patient data with a product dataset and uses advanced machine learning and deep learning algorithms to classify foods as allowed or not allowed.

**Features**

Combines patient data (age, gender, weight, disease, nutritional requirements) with product data (calories, protein, fat, sodium, carbohydrates, fiber, cholesterol).
Implements feature selection using Random Forest to identify the most relevant features for diet recommendations.
Supports multiple classification models, including:
Machine Learning: Naive Bayes, Logistic Regression
Deep Learning: Multilayer Perceptron (MLP), Recurrent Neural Network (RNN), Gated Recurrent Units (GRU), Long Short-Term Memory (LSTM)
Uses cross-validation to evaluate model performance.
Provides evaluation metrics: accuracy, precision, recall, F1-score, ROC-AUC.

**Key Insights**

LSTM achieved the highest accuracy (95.73%) and recall (92.78%) among all models, outperforming other deep learning and machine learning techniques.
Deep learning algorithms performed better than traditional machine learning models for patient diet classification.
The system can recommend personalized diets for patients based on their medical records, improving health outcomes.

**Dataset**

Patient Dataset: 30 records with 13 attributes (age, gender, weight, disease, and nutritional info).
Product Dataset: 1000 food items with 8 nutritional features.
Combined dataset: 30,000 records with 21 features for model training and testing.

**Methodology**

Data Collection & Integration: Combined patient and product datasets.

Preprocessing:
Normalization (Min-Max scaling)
Encoding categorical variables (one-hot encoding)
Optimal feature selection using Random Forest importance

Model Training & Testing:
Split data: 70% training, 30% testing
Implemented machine learning and deep learning models

Evaluation: 
Compared models based on accuracy, precision, recall, F1-score, and ROC-AUC.

**Tools & Libraries**

Python 3.x
Libraries: numpy, pandas, scikit-learn, tensorflow, keras, matplotlib

**Future Work**

Expand datasets to include more patients and diverse food items.
Incorporate patient preferences, allergies, and cultural considerations.
Deploy as a real-time recommendation system integrated with healthcare applications.
Explore hybrid models combining LSTM with attention mechanisms for improved accuracy.
