# Iris Flower Classification Project

This project implements a machine learning pipeline to classify Iris flowers into three species: Setosa, Versicolor, and Virginica. It uses the K-Nearest Neighbors (KNN) algorithm and includes data preprocessing, exploratory data analysis (EDA), and model evaluation.

## Project Overview

The goal of this project is to demonstrate a complete machine learning workflow using the famous Iris dataset. The pipeline includes:

- **Data Loading**: Importing the Iris dataset from a CSV file.
- **Exploratory Data Analysis (EDA)**: Visualizing class distributions and feature statistics.
- **Data Preprocessing**: Handling missing values, feature scaling (Standardization), and label encoding.
- **Model Training**: Implementing the K-Nearest Neighbors (KNN) classifier.
- **Hyperparameter Tuning**: Finding the optimal 'K' value by analyzing error rates.
- **Evaluation**: Assessing model performance using accuracy, confusion matrices, and classification reports.

## Dataset

The project uses the `Iris.csv` dataset, which contains 150 samples with 4 features:
- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

The target variable is the `Species` of the flower.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/iris-classification.git
   cd iris-classification
   ```

2. **Install dependencies**:
   It is recommended to use a virtual environment.
   ```bash
   pip install -r requirements.txt
   ```

## Usage

You can run the analysis using the provided Jupyter Notebook:

```bash
jupyter notebook ArtificialIntelligenceProject2.ipynb
```

## Results

The model achieves high accuracy on the test set. Through hyperparameter tuning, an optimal 'K' value was identified to minimize the error rate.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
