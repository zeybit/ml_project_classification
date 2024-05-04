# ml_project_classification
**Title: Exploring Wine Quality with Machine Learning**

**Introduction:**
This project delves into the world of wine quality prediction using machine learning. We aim to understand how various characteristics of wines relate to their quality ratings and develop a model to predict these ratings accurately.

**Data Collection and Preprocessing:**
We obtained a dataset containing information about wine properties like acidity, sugar content, sulfur dioxide levels, and alcohol percentage. After handling missing values, the dataset was ready for analysis.

**Exploratory Data Analysis (EDA):**
Visualizations such as histograms, correlation matrices, and box plots were created to understand the distribution of wine quality, explore correlations between attributes, and visualize how alcohol content varies across quality ratings.
![histogram](https://github.com/zeybit/ml_project_classification/assets/148189146/f714b777-94f4-42b2-8f9f-73b94612503a)
![correlation matrix](https://github.com/zeybit/ml_project_classification/assets/148189146/3078e3bb-d3d0-4edd-9453-2759cb0f7ede)
![box plot](https://github.com/zeybit/ml_project_classification/assets/148189146/a35fcbed-0fdf-4c19-9449-b5d78f15880f)



**Model Development:**
A Random Forest Classifier was chosen as the predictive model due to its robustness and ability to handle complex data. After splitting the data into training and testing sets, the model was trained using the training data. Cross-validation and grid search techniques were employed to fine-tune the model's parameters for optimal performance.

**Model Evaluation:**
The trained model was evaluated using accuracy, confusion matrix, and classification report metrics. Accuracy measures how often the model predicts the correct wine quality, while the confusion matrix provides insights into the model's performance across different quality levels. The classification report offers a detailed breakdown of precision, recall, and F1-score for each quality level.

**Conclusion:**
Our analysis highlights the potential of machine learning in predicting wine quality based on its characteristics. By leveraging advanced algorithms and thorough data analysis, we can uncover valuable insights for winemakers to produce high-quality wines consistently.
