name:LOKESHWAR GASIKANTI
company:CODETECH IT SOLUTIONS
id:CT08DS8418 
domain:ARTIFICIAL INTELLIGENCE 
Duration:september to october,2024


OVERVIEW:

Objective: To implement a sentiment analysis model that classifies movie reviews as positive or negative using the NLTK library and Scikit-Learn.

Key Components
Dataset:

The model uses the NLTK movie_reviews dataset, which contains 2,000 movie reviews categorized as either positive or negative.
Data Preprocessing:

Reviews are shuffled and split into training and testing sets to ensure that the model learns from a representative sample of data.
Feature Extraction:

The CountVectorizer from Scikit-Learn is employed to convert the text data into a numerical format (bag-of-words model), allowing the machine learning algorithm to process it.
Model Selection:

A Naive Bayes classifier (MultinomialNB) is chosen for its effectiveness in text classification tasks. This model is particularly well-suited for problems where the features (words) are conditionally independent given the class labels.
Training and Evaluation:

The model is trained on the training set, and its performance is evaluated on the test set.
Accuracy and a detailed classification report (precision, recall, F1-score) are generated to assess how well the model performs.
Expected Outputs:

The model outputs an accuracy score and a classification report detailing its performance across positive and negative reviews.
Conclusion
This task illustrates the fundamental steps in building a sentiment analysis system using natural language processing techniques. By leveraging NLTK for data access and Scikit-Learn for modeling, the implementation showcases how machine learning can be applied to real-world text data for meaningful insights. If you have further questions or need additional information, feel free to ask!
