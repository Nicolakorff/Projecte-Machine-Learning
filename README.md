# ML Project to Increase Deposit Sales

**TRY IT!! ->** [Prediction App](https://projecte-machine-learning-nicola.streamlit.app/)

## Introduction
This is a bank that sells long-term deposits to a diverse audience.

## Project Objectives
The main business objectives are to increase deposit sales by segmenting customers and evaluating sales probabilities for each segment.
The goal is to optimize business decisions related to deposit sales by automating segmentation and prediction for each segment.
While segmentation can be done using spreadsheets or statistical software, the use of machine learning will allow this process to be automated through programmed training that quickly incorporates daily transactions without the need for manual intervention.

## Proposed Methodology
To address the analysis of these problems we have chosen the following algorithms and metrics: To segment customers into different groups by characteristics such as demographics or purchasing behavior: **K-means**, a clustering algorithm. To predict the probability of purchase based on previous interactions: **Logistic regression**: It is used for binary classification problems, where the target variable is categorical. The goal is to predict the probability of a binary class. It minimizes the log-loss function, which measures the error between the predicted probability and the actual value of the class. It does not assume a linear relationship between the independent variables and the probability of the dependent variable, but there is a linear relationship between the independent variables and the logit (logarithm of the odds). Ideal for predicting whether or not a customer will purchase a deposit.

*The logistic regression evaluation metrics* that have been chosen to ensure that the models are more accurate are: **ROC curve or AUC (Area Under the Curve)**: To be able to evaluate the model's ability to correctly classify which customers are most likely to acquire a deposit. Ideal for binary classifications. **Accuracy**: Proportion of correct predictions with respect to the total. **Precision, recall and F1-score**: To measure the balance between precision and recall, controlling false positives and false negatives. **Confusion matrix**: For a deeper understanding of the type of errors of the model and see how it works in true positives, true negatives, false positives and false negatives. **Log-Loss (Logarithmic Loss)**: It is especially useful in banking applications in prediction probabilities instead of a simple binary classification as is the case and to evaluate if the model gives high confidence in its predictions.

*Clustering metrics for K-means clustering*: **Inertia (Sum of Squares of Internal Distances)**: Measures the sum of the squared distances between the points and the centroid of their respective groups. It is minimized during the K-means adjustment. **Silhouette Score**: Measures how well the clusters are separated. **Davies-Bouldin Index**: Measures the quality of the clusters by calculating the average of the similarity between each cluster and the nearest one. **Calinski-Harabasz Index (Inter and Intra-cluster Variance)**: Measures the dispersion within and between clusters.

## Available Data
The Bank has data collected from marketing campaigns.

## Success Metric
To increase in annual sales. This metric would directly reflect the effectiveness of the model in improving the company's decisions.

## Ethical and Social Responsibilities
Since the system collects personal data from customers, it is essential to ensure compliance with data protection laws such as the General Data Protection Regulation (GDPR) in Europe or other similar regional regulations. **Privacy and Data Protection**: Informed data collection, anonymization and data minimization. **Algorithmic Bias and Justice**: Avoiding bias in data, monitoring bias and making transparent decisions. **Transparency and Explainability**: Explainability of the model and business transparency. **Social and Economic Impact**: Impact on personalization and inequality in access to services. **Responsibility in Automated Decision Making**: Human supervision and response to errors. **Management of technological risks**.

![Captura de pantalla 2025-04-21 a las 23 13 04](https://github.com/user-attachments/assets/e88fadd4-c198-4c06-8be7-9668c933dff9)
![Captura de pantalla 2025-04-21 a las 23 07 32](https://github.com/user-attachments/assets/7e80c56f-ba7c-45e5-ac4c-5e843fed0ee8)
![Captura de pantalla 2025-04-21 a las 23 07 52](https://github.com/user-attachments/assets/b88089b2-6acb-4678-8ea2-8fd1e960a65a)
![Captura de pantalla 2025-04-21 a las 23 08 10](https://github.com/user-attachments/assets/7684274e-7a4d-45c7-9dc2-069cd94adb44)
![Captura de pantalla 2025-04-21 a las 23 08 27](https://github.com/user-attachments/assets/87326f40-2884-4b79-aa6c-5321fc374f0c)
![Captura de pantalla 2025-04-21 a las 23 08 39](https://github.com/user-attachments/assets/7125452d-d21c-4e90-bb18-501d8d51f145)
![Captura de pantalla 2025-04-21 a las 23 09 09](https://github.com/user-attachments/assets/e8788509-895e-4763-a3df-214231b6f9e7)
