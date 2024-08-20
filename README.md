# NLP
labs and projects regarding natural language processing

regarding NLP_Project
Introduction:
our project aims to design and implement a sentiment analysis system using Python for analyzing customer reviews of restaurants. The system is tasked with classifying these reviews as either positive, negative, or neutral based on the sentiments expressed by the customers.

Data collected:
https://www.kaggle.com/datasets/joebeachcapital/restaurant-reviews
Dataset of restaurant reviews with 10000 rows and 8 columns.
The dataset used for this sentiment analysis project is sourced from a collection of restaurant reviews. The dataset comprises a diverse set of textual data representing customer feedback on various dining experiences.
The dataset includes several attributes such as the review text, reviewer metadata, timestamps, and accompanying images. However, for the purpose of this sentiment analysis project, only the review text and corresponding ratings were utilized.
Each review in the dataset is associated with a numerical rating provided by the customer, ranging from 1 to 5 stars. These ratings serve as the basis for annotating the reviews with sentiment labels, enabling the classification of reviews into positive, negative, or neutral categories.
Sentiment Analysis Implementation:

Data Preprocessing:
-Removing any non-alphanumeric characters and converting the text to lowercase.
- Tokenization to split the text into individual words.
- Stop word removal to eliminate common English words that do not contribute much to the sentiment analysis.
- Stemming to reduce words to their base or root form.

Feature Extraction:
For feature extraction, the TF-IDF (Term Frequency-Inverse Document Frequency) method was employed. It converts text documents into numerical vectors while considering the importance of words in the document relative to their frequency in the entire corpus.

Model Selection:
Two machine learning models were selected for sentiment analysis:
- Support Vector Machine (SVM)
- Naive Bayes
These models were chosen for their effectiveness in text classification tasks.

Model Evaluation:
The performance of the sentiment analysis models was evaluated on a separate test dataset using metrics such as accuracy, precision, recall, and F1-score. And confusion matrix to visualize of the performance of the two models.
