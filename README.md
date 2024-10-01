# Credit Risk Analysis using K-Nearest Neighbors (KNN)

## Description

This project focuses on **Credit Risk Analysis** using the **K-Nearest Neighbors (KNN) algorithm** to classify transactions as **fraudulent** or **non-fraudulent**. The dataset, sourced from Kaggle's credit card fraud detection dataset, is highly imbalanced, with only a small percentage of fraud cases. To address this, **downsampling techniques** are employed to create a balanced dataset, enabling more effective model training and evaluation.

## Table of Contents

- [Description](#description)
- [Methodology](#methodology)
- [Tools and Libraries](#tools-and-libraries)
- [Highlights](#highlights)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Contact](#contact)

## Methodology

1. **Exploratory Data Analysis (EDA)**:
   - Understand the distribution of classes and features.
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
   - Generate **Confusion Matrices** and **Classification Reports** to assess model performance.

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

## Installation

To install and run this project locally, follow these steps:

1. **Clone the repo:**

   ```bash
   git clone https://github.com/dhanashree010804/KNN_credit_analysis.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd Knn_CreditRiskAnalysis
   ```

3. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the project:**

   ```bash
   python Knn_CreditRiskAnalysis.ipynb
   ```

## Usage

- To start the project, execute the `main.py` file after installation.
- The results, including confusion matrices, classification reports, and model evaluation metrics, will be displayed after running the KNN model.

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

To contribute:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a pull request

## Contact

**Dhanashree Giriya**  
[GitHub Profile](https://github.com/dhanashree010804)  
Email: dhanashreegiriya2013@gmail.com
