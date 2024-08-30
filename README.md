# Pyschosis-predictions-using-NLP-minor-project
This repository contains the code and documentation for a project aimed at predicting the risk of psychosis using a Long Short-Term Memory (LSTM) neural network. The model classifies individuals into three risk categories: low risk, medium risk, and high risk.

Project Overview
Psychosis is a serious mental health condition that requires early detection for effective intervention. The goal of this project was to leverage machine learning, specifically LSTM networks, to classify individuals into different risk categories based on their data.

Dataset
The dataset used in this project includes features related to mental health indicators, demographic data, and other relevant factors. The target variable is labeled with three classes: low risk, medium risk, and high risk.

Synthetic Data
Given the limited availability of real-world data, synthetic data was generated using GPT-4, which was trained on a real-life interview transcript available on GitHub. This synthetic data was used to supplement the existing dataset. However, it should be noted that the synthetic data was based on only one interview transcript, which may have limited the model's ability to generalize and achieve higher accuracy.

Model and Methodology
Model: LSTM (Long Short-Term Memory)
Task: Multiclass classification with three labels (low risk, medium risk, high risk)
Accuracy: The model achieved an accuracy of 57%.
Challenges and Limitations
This project was part of a minor college project, and while the model did not achieve high accuracy, the process provided valuable learning experiences. Here are some challenges and limitations encountered:

Class Imbalance: There were differences in the distribution of the three classes, which may have affected the model's performance.
Data Quality: The synthetic data, while useful, may not fully capture the complexity of real-world data due to being based on a single transcript.
Model Complexity: LSTMs are powerful for sequence data, but tuning them for optimal performance in this context proved challenging.
Learning Outcomes
While the accuracy of 57% indicates that there is room for improvement, this project was a significant learning experience in understanding how to apply LSTM networks to a complex problem like psychosis prediction. Key takeaways include:

Understanding the structure and application of LSTM networks.
Gaining experience in preprocessing data for machine learning models.
Exploring the challenges of multiclass classification.
Future Work
There are several directions in which this project could be taken further:


Improved Synthetic Data: In future iterations, I plan to generate more diverse and representative synthetic data to better train the model.
Model Tuning: Experiment with hyperparameter tuning to improve accuracy.
Alternative Models: Explore other models like Random Forests, Gradient Boosting, or even more advanced deep learning architectures.
Feature Engineering: Investigate more sophisticated feature engineering techniques to improve model input.

Improved Synthetic Data: In future iterations, I plan to generate more diverse and representative synthetic data to better train the model.
Model Tuning: Experiment with hyperparameter tuning to improve accuracy.
Alternative Models: Explore other models like Random Forests, Gradient Boosting, or even more advanced deep learning architectures.
Feature Engineering: Investigate more sophisticated feature engineering techniques to improve model input.
Conclusion
This repository is a part of my ongoing learning journey in machine learning. The results may not be perfect, but the process of working through the challenges of this project has been invaluable. I hope this project can serve as a resource for others who are also learning about LSTM networks, psychosis prediction, or multiclass classification.
