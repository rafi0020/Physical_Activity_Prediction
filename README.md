# Predicting Physical Activity Levels Using Machine Learning Models

This repository contains the implementation of machine learning models to predict physical activity levels based on a large dataset of health-related parameters. The project employs Logistic Regression, Decision Tree, and Random Forest models to achieve robust predictions, with the Random Forest model achieving the highest accuracy.

---

## 📄 Project Overview

### Motivation
Accurate prediction of physical activity levels is essential for promoting healthier lifestyles and preventing sedentary behaviors. This project explores the application of machine learning models to automate activity prediction, providing personalized insights for individuals.

### Objectives
1. Build machine learning models to classify physical activity levels.
2. Optimize model performance through hyperparameter tuning and feature selection.
3. Evaluate models using metrics like accuracy, precision, recall, and F1-score.

---

## 📊 Dataset

### Description
- **Size**: 2.8 million records.
- **Features**: Includes parameters like heart rate, step count, and sleep duration.
- **Target Variable**: Physical activity level (categorical).

### Data Preparation
- Handled missing values and outliers.
- Performed normalization and scaling.
- Applied feature selection using correlation analysis and recursive feature elimination (RFE).

---

## 🚀 Methodology

### Machine Learning Models
1. **Logistic Regression**:
   - Simple and interpretable model.
   - Accuracy: 69.44%.
2. **Decision Tree**:
   - Captures non-linear relationships and feature importance.
   - Accuracy: 77.48%.
3. **Random Forest**:
   - Combines multiple decision trees for robustness.
   - Accuracy: 78.02%.

### Workflow:
1. Preprocessed the dataset for quality and consistency.
2. Split the data into training (80%) and testing (20%) subsets.
3. Trained models using k-fold cross-validation.
4. Evaluated performance on the test set using confusion matrices and other metrics.

---

## 🔧 Getting Started

1. **Download the Repository**  
   Access the repository files from GitHub and save them locally.

2. **Install Dependencies**  
   Use the `requirements.txt` file to set up your Python environment.

3. **Prepare the Dataset**  
   Follow the instructions in the `data/README.md` file to access or prepare the dataset.

4. **Run the Notebook**  
   Open `Predicting_Physical_Activity.ipynb` to execute the project.

---

## 📊 Results

### Model Performance
- **Logistic Regression**: Accuracy = 69.44%
- **Decision Tree**: Accuracy = 77.48%
- **Random Forest**: Accuracy = 78.02%

### Key Insights:
- Feature importance analysis revealed heart rate and step count as key predictors.
- Random Forest outperformed other models due to its robustness and ability to handle non-linear relationships.

---

## 🤝 Contributions
Contributions are welcome! Open an issue or submit a pull request for suggestions or improvements.

---

## 📫 Contact
- **Email**: rafiulislam1921@gmail.com  
- **LinkedIn**: [Rafiul Islam](https://www.linkedin.com/in/rafi009)

---

## 📄 License
This repository is licensed under the Apache 2.0 License. See `LICENSE` for more details.
