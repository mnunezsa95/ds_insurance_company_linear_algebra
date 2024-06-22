# Sure Tomorrow Insurance Company Machine Learning Integration
## Overview
In the realm of contemporary business, the Sure Tomorrow insurance company stands at the precipice of innovation, poised to leverage the capabilities of Machine Learning (ML) to address an array of challenges. Entrusted with the task of evaluating the feasibility of integrating ML into the company's operations, the is to encompass a spectrum of objectives aimed at optimizing processes and enriching customer experiences.

## Description
The project is designed to assess how Sure Tomorrow can incorporate ML to enhance various aspects of its operations. The aim is to tackle four main tasks:

1. Customer Profiling: Identifying customers similar to a specified profile using ML algorithms to enhance targeted marketing strategies.
2. Benefit Prediction: Predicting the likelihood of a customer receiving insurance benefits through advanced predictive models.
3. Benefit Magnitude Forecasting: Using linear regression models to predict the magnitude of insurance benefits a customer might accrue.
4. Data Obfuscation: Implementing data masking techniques to protect client data while maintaining the efficacy of ML models.

## Objectives
Task 1: Customer Profiling
- Utilize k-Nearest Neighbors (kNN) algorithm to find similar customers.
- Evaluate the impact of scaling (MaxAbsScaler) and different distance metrics (Euclidean, Manhattan) on the kNN algorithm.
- Assess how unscaled data affects kNN and the similarity of results using Manhattan distance metric.

Task 2: Benefit Prediction
- Develop a kNN-based classification algorithm to predict the likelihood of receiving insurance benefits.
- Compare the kNN model's performance with a dummy model using the F1 metric.
- Split the data into training (70%) and testing (30%) sets.

Task 3: Benefit Magnitude Forecasting
- Build a Linear Regression (LR) model to predict the number of insurance benefits.
- Implement a custom LR algorithm and compare RMSE for original and scaled data.
- Evaluate the consistency of RMSE between scaled and unscaled data.

Task 4: Data Obfuscation
- Implement data obfuscation by multiplying the feature matrix with an invertible matrix.
- Verify the invertibility of the matrix and recover original data.
- Test LR with obfuscated data and compare RMSE and R² metrics with the original data.

## Libraries
- Scikit-learn: For kNN, scaling, and dummy model implementation.
- NumPy: For matrix operations and linear algebra computations.
- Pandas: For data manipulation and preprocessing.
- Matplotlib: For data visualization

## Conclusion
Findings from Customer Profiling
- Euclidean distance with scaled data yielded the most accurate results for identifying similar customers.

Findings from Benefit Prediction
- The kNN model trained on scaled data achieved high F1 scores, significantly outperforming the dummy model.

Findings from Benefit Magnitude Forecasting
- The linear regression model maintained consistent RMSE values for both scaled and unscaled data, indicating the robustness of the model.

Findings from Data Obfuscation
- Data obfuscation effectively protected client information without compromising the integrity of the ML models.
- The RMSE and R² metrics remained consistent, demonstrating the feasibility of using obfuscated data in ML models.

Embarking on this journey, Sure Tomorrow showcases its commitment to innovation, integrity, and excellence in the application of Machine Learning to enhance its business operations and customer experience.
