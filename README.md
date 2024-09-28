# Credit Risk Analysis using K-Nearest Neighbors (KNN)

## Description

This project focuses on **Credit Risk Analysis** using the **K-Nearest Neighbors (KNN) algorithm** to classify transactions as **fraudulent** or **non-fraudulent**. The dataset, sourced from Kaggle's credit card fraud detection dataset, is highly imbalanced, with only a small percentage of fraud cases. To address this, **downsampling techniques** are employed to create a balanced dataset, enabling more effective model training and evaluation.

## Methodology

1. **Exploratory Data Analysis (EDA)**:
   - Perform EDA to understand the distribution of classes and features.
   - Visualize patterns in fraudulent vs. non-fraudulent transactions.
   
2. **Data Preprocessing**:
   - Standardize the dataset using **StandardScaler** (since KNN is sensitive to the scale of features).
   - Perform downsampling to balance the dataset.
   - Split the dataset into training and testing sets.
   
3. **Model Training**:
   - Train the **KNN algorithm** on the balanced dataset.
   - Choose KNN for its simplicity and effectiveness in classification, especially in **fraud detection** tasks.
   
4. **Hyperparameter Tuning**:
   - Experiment with different values for **'K'** (number of neighbors) to find the optimal setting.
   
5. **Model Evaluation**:
   - Evaluate the model using metrics such as:
     - **Accuracy**
     - **Precision**
     - **Recall**
     - **F1-score**
   - Generate **Confusion Matrices** and **Classification Reports** to visualize the results and performance of the model.

## Tools and Libraries

The following tools and libraries were used to develop and execute this project:

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**

## Highlights

- Implements the **K-Nearest Neighbors (KNN) algorithm** for **credit risk analysis**.
- Addresses **imbalanced data** by using **downsampling techniques**.
- Uses **StandardScaler** to normalize the dataset before applying KNN.
- Performs **hyperparameter tuning** to optimize the KNN model.
- Provides comprehensive evaluation metrics like **confusion matrices**, **precision**, **recall**, and **F1-scores** for fraud detection tasks.

## Contact

If you have any questions or suggestions regarding this project, feel free to reach out to me:

**Priyant Prashant Nikhare**  
[GitHub Profile](https://github.com/dhanashree010804)  
Email: dhanashreegiriya2013@gmail.com
