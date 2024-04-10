# Steel Plates Defect Prediction

## Project Overview

This project aims to develop a predictive model for identifying defects in steel plates. The dataset used for this project was generated from a deep learning model trained on the Steel Plates Faults dataset from the UCI Machine Learning Repository. The goal is to utilize the CatBoost algorithm for analysis and prediction.

## Dataset

The dataset consists of features extracted from images of steel plates. The features are derived from the original Steel Plates Faults dataset from UCI, although the distributions may not be exactly the same. There are 7 binary target variables indicating different types of defects in the steel plates.

- `train.csv`: Training dataset containing features and target variables.
- `test.csv`: Test dataset for evaluating model performance.

## Methodology

1. **Data Preparation**: Load the dataset and preprocess the data.
2. **Model Training**: Utilize the CatBoost algorithm to train a predictive model.
3. **Model Evaluation**: Evaluate the model's performance using appropriate metrics.
4. **Insights and Analysis**: Analyze the results and gain insights into the data.

## Usage

To run the project locally, follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/your_username/steel-plates-defect-prediction.git
```

2. Navigate to the project directory:

```bash
cd steel-plates-defect-prediction
```

3. Install the required dependencies:

```bash
pip install -r requirements.txt
```

4. Run the project:

```bash
python main.py
```

## Conclusion

This project demonstrates the application of machine learning techniques for defect prediction in steel plates. By leveraging the CatBoost algorithm and analyzing the dataset, valuable insights can be gained to improve manufacturing processes and quality control.
