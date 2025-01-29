# wine_data_artificialintelli

**Problem statement:**
The quality and classification of wine are crucial in the wine industry, impacting producers, distributors, and consumers. Traditionally, wine classification has been performed by expert tasters using sensory analysis, which is time-consuming, subjective, and inconsistent. Our objective is to build a machine learning model that can accurately classify wines into their respective categories based on their chemical composition. By using ML model, wine producers and retailers can ensure consistent quality control, enhance customer experience, and optimize production processes.

**Dataset Overview:**
The dataset used in this project is the Wine Dataset from the scikit-learn library. It contains 178 samples of wine, each belonging to one of three classes (Class 0, Class 1, and Class 2), representing different cultivars (varieties) of wine grown in Italy. There are 13 numerical features which include Alcohol content, Malic Acid, Ash, Alcalinity of Ash, Magnesium, Total Phenols, Flavanoids, Nonflavanoid Phenols, Proanthocyanins, Color Intensity, Hue, OD280/OD315 of diluted wines, Proline.
The target variable is the class of wine (0, 1, or 2), representing three different cultivars.

**Model Approach:**
I have implemented a Random Forest Classifier technique in our model. Step by step implementation of machine learning model is updated in the jupyter notebook along with detailed explanation. 

**Model Evaluation:**
• We measured performance using accuracy score, classification report, and confusion matrix
•  We visualized the confusion matrix using a heatmap to understand misclassifications better.

**Results:**
•	95% accuracy, demonstrating its effectiveness in classifying wines correctly.
•	Feature Importance: Features such as Flavanoids, Proline, and Color Intensity played a significant role in classification.
•	Confusion Matrix Analysis: Most predictions were accurate, with very few misclassifications occurring between similar wine classes. (Figure 1)

**Benefits of the model:**
Quality Control
Process Optimization
Cost Savings
Customer Satisfaction

Figure 1: ![image](https://github.com/user-attachments/assets/6b2b8648-1f7f-4d51-b36d-3f0fe6ff2ced)

