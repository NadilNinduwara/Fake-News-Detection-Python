This project aims to detect fake news using machine learning techniques in Python. The goal is to build a model that can classify news articles as either real or fake based on their content. The project utilizes the Passive Aggressive Classifier algorithm along with the TF-IDF (Term Frequency-Inverse Document Frequency) vectorization method.

Dataset
The dataset used for this project is a CSV file named "news.csv", which contains 7796 news articles. Each article is labeled as either real or fake, and the dataset is structured with four columns: identifier, title, text, and label. The dataset can be downloaded from here.

Prerequisites
To run this project, the following libraries need to be installed using pip:

numpy
pandas
sklearn
Additionally, Jupyter Lab is required to execute the code. Please ensure that Jupyter Lab is installed on your system before running the project.

Usage
Clone the repository to your local machine.
Download the "news.csv" dataset and place it in the project directory.
Open Jupyter Lab and navigate to the project directory.
Run the code in the Jupyter Lab console or execute the cells in the provided Jupyter notebook.
The project will load the dataset, split it into training and testing sets, perform TF-IDF vectorization, train the model, and evaluate its accuracy.
The output will display the accuracy of the model and a confusion matrix showing the number of true positives, true negatives, false positives, and false negatives.
Results
The implemented model achieved an accuracy of 92.82% in classifying news articles as real or fake. The confusion matrix provides further insights into the model's performance.

Contributing
Contributions to this project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License. Feel free to use and modify the code as per the terms of the license.

Acknowledgments
This project is based on the guidance provided by DataFlair and their Python project tutorials.

References
Passive Aggressive Classifier
TF-IDF Vectorization
