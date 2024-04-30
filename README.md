[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/ml3o3YLw)

# Task

See https://uazhlt-ms-program.github.io/ling-539-course-blog/assignments/class-competition

Competition: https://www.kaggle.com/competitions/ling-539-sp-2024-class-competition

Invitation URL: https://www.kaggle.com/t/33320feca02e42bd924c3473e3a8c2fd

# Grad-Level Term Project: Statistical Natural Language Processing

This repository contains the code and data for the Graduate-Level Term Project for the Statistical Natural Language Processing (INFO-539) course at the University of Maryland, College Park. The project aims to build a classifier model to predict labels for a given text dataset.

## Author
- Eshaan Prasad Mathakari

## Project Structure

- `data/`: This directory contains the training and testing datasets used for the project.
  - `train.csv`: The training dataset.
  - `test.csv`: The testing dataset.
- `scripts/submission/submission.csv`: The final submission file with predictions on the test dataset.
- `classifier.ipynb`: A Jupyter Notebook containing the code for data exploration, preprocessing, model training, and evaluation.

## Requirements

The project requires the following Python packages:

- pandas
- numpy
- matplotlib
- seaborn
- wordcloud
- scikit-learn

These packages will be automatically installed if not already present on your system.

## Usage

1. Clone the repository:

```console
git clone https://github.com/uazhlt-ms-program/grad-level-term-project-kaggle-competition-eshaanmathakari.git
```
2. Navigate to the project directory:

```console
cd grad-level-term-project-kaggle-competition-eshaanmathakari
```
3. Open the `classifier.ipynb` notebook in Jupyter Notebook or JupyterLab.

4. Run the notebook cells sequentially to reproduce the results.

## Methodology

The project follows these main steps:

1. **Data Exploration**: Explore the training and testing datasets using descriptive statistics and visualizations.
2. **Data Preprocessing**: Clean and preprocess the text data, including handling missing values and converting text to numerical features using TF-IDF vectorization.
3. **Model Training**: Split the training data into train and validation sets, and train a Logistic Regression model on the training set.
4. **Model Evaluation**: Evaluate the model's performance on the validation set using accuracy and F1-score metrics.
5. **Prediction**: Make predictions on the test dataset using the trained model.
6. **Submission**: Save the predictions in a submission file (`submission.csv`).

# Notes
- **At least one of your submitted solutions must use one or more of the classification algorithms covered in this course**
- You are not obligated to use Python
- You may delete or alter any files in this repository
- You are free to add dependencies
  - Ensure that your code can be installed/used on another machine running Linux or MacOS (consider containerizing your project with Docker or an equivalent technology)
 
## License
This project is licensed under the [MIT License](LICENSE).
