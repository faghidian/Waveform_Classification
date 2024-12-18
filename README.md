# Classifier Design for Waveform Classification

- This project aims to design a classifier to distinguish between three classes of waveforms based on signal data. Each sample represents n seconds of data, and the challenge is to separate these events effectively.
- The dataset was preprocessed by handling missing values, encoding categorical variables, and scaling numerical features. Feature selection was performed using methods like Chi-squared tests and correlation analysis, identifying main key features.
- An XGBoost classifier was used for multi-class classification, evaluated through metrics like F1 score, confusion matrix, and ROC curve with AUC. The model performed well, with the ability to distinguish between the three waveform classes.
- Challenges such as potential class imbalance and over-fitting were considered. To mitigate these, techniques like cross-validation and balanced datasets can be implemented. Further improvements can be made by refining the model to address these issues and enhance its generalization.
