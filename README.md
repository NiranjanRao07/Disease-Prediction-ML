# Disease Prediction Using Machine Learning

This repository contains a project aimed at predicting diseases based on symptoms using various machine learning models. The project uses a dataset of symptoms and their associated diagnoses to train classification models for disease prediction.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project focuses on building a machine learning model that predicts diseases based on a wide range of symptoms. The dataset includes 132 symptoms and a target label (`prognosis`) that specifies the disease. The project applies classification algorithms to train a predictive model, and evaluates the model’s accuracy.

### Key Features:
- Data preprocessing (handling missing values, encoding categorical data)
- Feature selection and visualization
- Training and evaluation of multiple machine learning models:
  - Random Forest Classifier
  - Naive Bayes
  - Support Vector Classifier
- Model comparison and selection based on performance metrics such as accuracy.

## Dataset
The dataset used in this project consists of two files:
- `Training.csv`: Contains training data with symptoms and their corresponding diseases.
- `Testing.csv`: Contains test data to evaluate the model's performance.

Each row in the dataset represents a case with 132 symptoms, where `1` indicates the presence of the symptom and `0` indicates its absence. The target variable `prognosis` represents the disease diagnosed based on the symptoms.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/disease-prediction-ml.git
    ```
2. Navigate to the project directory:
    ```bash
    cd disease-prediction-ml
    ```

## Usage

1. **Jupyter Notebook**: Open the `MI.ipynb` file in Jupyter Notebook to explore the project step by step.
    ```bash
    jupyter notebook MI.ipynb
    ```

2. **Train the Model**: The notebook will guide you through the process of loading the training dataset, preprocessing it, and training various machine learning models.

3. **Evaluate the Model**: Use the `Testing.csv` file to test the accuracy of the trained model and compare results across different algorithms.

4. **Visualization**: Explore the data using visualization libraries such as Matplotlib and Seaborn to understand the distribution of symptoms and diseases.

## Results
The project evaluates multiple machine learning models and compares their performance. Based on the results, the Random Forest Classifier achieved the highest accuracy in predicting diseases from symptoms.

**Confusion Matrix and Accuracy Score** will be provided in the notebook after evaluating the models on the test data.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---
