# Machine_Learning_Project
This project was developed as part of a Machine Learning & Data Mining course. The goal was to build predictive models that classify whether an individual is at risk of developing diabetes, based on medical, demographic, and behavioral data. The work included exploratory data analysis, preprocessing, neural network modeling with undersampling strategies, and evaluation metrics (with emphasis on recall to reduce false negatives). In addition, we integrated an economic cost-benefit model to assess the real-world impact of false positives and missed diagnoses.

# Methodology

1. EDA: analyzed data distribution and class imbalance (~14% diabetics), identified strong predictors (BMI, blood pressure, cholesterol, age, general health).

2. Preprocessing: adjusted feature types, applied one-hot encoding, normalized continuous features, and removed weak predictors.

3. Modeling: trained neural networks with undersampling strategies (75:25, 60:40, 50:50), used dropout & batch normalization, compared optimizers (Adam/SGD) and loss functions (BCE/MSE).

4. Evaluation: focused on Recall to reduce false negatives, alongside accuracy, precision, and F1.

5. Economic Model: cost-benefit analysis of predictions, combining medical costs and savings from early detection to identify the most practical model.
