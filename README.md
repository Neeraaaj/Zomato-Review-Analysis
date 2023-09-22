# Zomato Review Sentiment Analysis.

This project is a Python-based Natural Language Processing (NLP) application that performs sentiment analysis on Zomato restaurant reviews. It helps classify reviews as positive or negative based on the text content.

Table of Contents
Project Overview
Usage
Dependencies
Data
Preprocessing
Model Training
Testing
Results
Contributing
License

Project Overview
Objective: The main goal of this project is to build a machine learning model that can automatically classify Zomato restaurant reviews as either positive or negative based on the text content. Sentiment analysis is a common NLP task used to understand customer sentiments and feedback.

Technologies Used:

Python
Pandas for data manipulation
NLTK for text preprocessing
Scikit-learn for machine learning
Matplotlib for data visualization
Usage
To use this project:

Clone the repository to your local machine:

bash
Copy code
git clone https://github.com/Neeraaaj/Zomato-Review-Analysis.git
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Follow the instructions in the Jupyter Notebook or Python script to preprocess the data, train the model, and perform sentiment analysis on new text.

Dependencies
This project relies on several Python libraries, which can be installed using the requirements.txt file.

Data
The dataset used for this project is stored in the ZomatoReview.tsv file. It contains restaurant reviews, including the review text and sentiment labels.

Preprocessing
Text preprocessing is an essential step in NLP projects. The code in this project performs the following preprocessing steps:

Removal of non-alphabetic characters
Lowercasing of text
Tokenization
Stopword removal
Word stemming
Model Training
The project trains a machine learning model using the preprocessed text data. The trained model is used for sentiment analysis.

Testing
You can test the model's sentiment analysis capabilities by providing new input text. The code will preprocess the text, vectorize it, and predict the sentiment (positive or negative).

Results
The project achieves 71% accuracy on the test data, demonstrating its effectiveness in sentiment analysis.

Contributing
Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
