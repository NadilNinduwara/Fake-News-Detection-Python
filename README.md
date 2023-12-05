# Fake News Detection Project

## Overview
This project focuses on the detection of fake news using machine learning techniques in Python. The primary objective is to build a robust model capable of classifying news articles as either real or fake based on their content. The implementation utilizes the Passive Aggressive Classifier algorithm in conjunction with the TF-IDF (Term Frequency-Inverse Document Frequency) vectorization method.

## Dataset
The dataset employed for this project is stored in a CSV file named "news.csv," comprising 7796 news articles. Each article is labeled as either real or fake, and the dataset structure includes four columns: identifier, title, text, and label..

## Prerequisites
Ensure that the following libraries are installed using pip:

- numpy
- pandas
- scikit-learn

Additionally, Jupyter Lab is required to execute the code. Please make sure Jupyter Lab is installed on your system before running the project.

## Usage
1. Clone the repository to your local machine.
2. Download the "news.csv" dataset and place it in the project directory.
3. Open a terminal and navigate to the project directory.
4. Run the code using the following commands:
   ```bash
   jupyter lab

Execute the cells in the provided Jupyter notebook.
The project will load the dataset, split it into training and testing sets, perform TF-IDF vectorization, train the model, and evaluate its accuracy. The output will display the accuracy of the model and a confusion matrix illustrating true positives, true negatives, false positives, and false negatives

Results
The implemented model achieved an impressive accuracy of 92.82% in classifying news articles as real or fake. The confusion matrix provides detailed insights into the model's performance.

Contributing
Contributions to this project are encouraged. If you encounter issues or have suggestions for improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License. Feel free to use and modify the code according to the terms of the license.

References
Passive Aggressive Classifier
TF-IDF Vectorization
