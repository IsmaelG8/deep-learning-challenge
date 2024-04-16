# deep-learning-challenge

![VC_Deep_Learning_Hero_3200x1800](https://github.com/IsmaelG8/deep-learning-challenge/assets/128990362/0b46d83e-2f50-4b30-9aba-8ee9296f5b77)


This project was initiated to assist the nonprofit organization Alphabet Soup in identifying which applicant organizations are likely to succeed if granted funding. Utilizing a dataset of over 34,000 previously funded organizations, I developed a binary classifier using neural networks to predict funding success based on various organizational attributes.

Objective:

The goal was to leverage machine learning and deep learning techniques to build a model that could accurately predict the success of funded organizations, thereby enhancing the foundation’s ability to allocate resources effectively.

Technical Execution:

Data Preprocessing:

Started with uploading and analyzing the charity_data.csv in Google Colab to understand the data structure.
Identified and separated target features (IS_SUCCESSFUL) and input features while removing non-informative columns (EIN, NAME).
Analyzed unique values in categorical variables and applied binning to reduce dimensionality where necessary.
Encoded categorical variables using pd.get_dummies() and split the data into training and testing sets using train_test_split.
Scaled the feature data using scikit-learn’s StandardScaler() to normalize the dataset.
Model Development and Evaluation:

Designed a neural network using TensorFlow and Keras, considering the complexity of input features to determine the number of neurons and layers.
Established multiple hidden layers with appropriate activation functions to optimize learning.
Compiled and trained the model, incorporating callbacks to save weights every five epochs.
Evaluated the model’s performance on test data focusing on accuracy and loss metrics, achieving a primary accuracy and then striving for optimization.
Model Optimization:

Conducted iterative adjustments on the neural network structure by modifying layers, neurons, and activation functions to surpass a 75% accuracy threshold.
Experimented with additional preprocessing strategies like adjusting input data and altering bin sizes for categorical data aggregation.
The optimized model configuration was saved and documented in AlphabetSoupCharity_Optimization.h5.
Outcomes:

Successfully developed a predictive model that provides Alphabet Soup with the capability to forecast the success of funding applications with considerable accuracy.
Achieved and exceeded the target model accuracy through systematic optimization, making the model a reliable tool for decision-making.
Summary:

The deep learning model developed in this project demonstrates significant potential in helping nonprofit organizations make data-driven decisions regarding funding. The use of neural networks to analyze and predict organizational success showcases the powerful application of AI in enhancing operational efficiencies in the nonprofit sector.

For future improvements, alternative machine learning models such as Random Forest or Gradient Boosting could be explored to compare performance and possibly improve the prediction accuracy. These models could provide additional insights into feature importance and model interpretability.

Conclusion:

This project underscores my proficiency in using advanced machine learning and neural network techniques to address real-world challenges. It highlights my ability to transform raw data into actionable insights, providing strategic guidance to enhance organizational decision-making.
