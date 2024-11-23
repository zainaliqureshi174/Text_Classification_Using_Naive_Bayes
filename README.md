# Text_Classification_Using_Naive_Bayes

**Project Overview**
This project focuses on classifying IMDB movie reviews as either positive or negative using the Naive Bayes algorithm. Leveraging Natural Language Processing (NLP) techniques, the classifier is trained on a dataset of labeled reviews, enabling it to predict sentiment for new, unseen data accurately. Naive Bayes, a probabilistic machine learning model, is well-suited for text classification tasks due to its simplicity and efficiency.

**Dataset**
The IMDB dataset comprises a collection of movie reviews, labeled as either positive or negative. Each review is processed and transformed into a format suitable for machine learning, with key text preprocessing steps applied to ensure accurate sentiment detection.

**Preprocessing Steps:**
Tokenization: Splitting text into individual words or tokens.
Stop-word Removal: Eliminating common words (e.g., "the," "is") that do not contribute to sentiment analysis.
Stemming/Lemmatization: Reducing words to their root form.
Vectorization: Converting text data into numerical form using methods like Bag-of-Words (BoW) or TF-IDF.

**Model Implementation**
The Naive Bayes classifier, specifically the Gaussian or Multinomial variant, is trained using the preprocessed dataset. This probabilistic model calculates the likelihood of a review belonging to each class (positive or negative) and classifies it based on the higher probability.

**Steps in Model Training:**
Data Splitting: Dividing the dataset into training and testing sets.
Feature Extraction: Transforming text into feature vectors.
Model Training: Fitting the Naive Bayes classifier with training data.
Evaluation: Measuring performance using accuracy, precision, and recall metrics.

**Results**
The trained model demonstrates robust performance, accurately classifying movie reviews with a high success rate. Evaluation metrics indicate its effectiveness in distinguishing between positive and negative sentiments.
