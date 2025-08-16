# Sentiment-Analysis
Perform sentiment analysis on textual data using Natural Language Processing techniques

**COMPANY:** CODTECH IT SOLUTIONS

**NAME:** P VAISHNAVI

**INTERN ID:** CT08DH1432

**DOMAIN:** Data Analytics

**DURATION:** 8 WEEKS

**MENTOR:** NEELA SANTOSH

Task Description:
For the fourth task of my internship, I performed sentiment analysis on a Twitter dataset using Natural Language Processing (NLP) techniques and machine learning models. The dataset contained tweets labeled as either positive or negative, which made it suitable for a classification problem. Before starting with implementation, I carefully studied the dataset to understand the distribution of tweets and prepared a plan for text cleaning and modeling.

The task began with data preprocessing, which is an essential step in NLP. I transformed all text to lowercase, removed unwanted characters such as links, numbers, and punctuation, and eliminated stopwords to reduce noise. I also applied lemmatization to bring words to their base form (e.g., “running” → “run”), which helped reduce vocabulary size and improve model accuracy. For this stage, I used NLTK and referred to GeeksforGeeks (https://www.geeksforgeeks.org/) and YouTube tutorials to revise the preprocessing steps and their importance. I also used quickref.me (https://quickref.me/) to quickly check Python and Scikit-learn syntax during implementation, which saved time and avoided small errors.

After preprocessing, I converted the text into numerical features using TF-IDF Vectorization, which highlights important words by considering both frequency and uniqueness across tweets. Once features were extracted, I trained two models: Naive Bayes and Logistic Regression. Naive Bayes, being probabilistic, is simple and effective for text classification, while Logistic Regression is a baseline linear model widely used for binary classification problems. To strengthen my understanding, I read comparisons from Scikit-learn documentation (https://scikit-learn.org/stable/) and Towards Data Science (https://towardsdatascience.com/), as well as a few Google articles explaining differences in model performance on text datasets.

The evaluation was carried out using accuracy, precision, recall, F1-score, and a confusion matrix. Logistic Regression achieved higher accuracy compared to Naive Bayes, showing that it handled the dataset better. Additionally, I extracted the most frequent words in positive and negative tweets, which gave meaningful insights into user sentiments expressed on Twitter.

Through this task, I gained valuable experience in end-to-end sentiment analysis workflows — from raw tweet preprocessing to feature extraction, model training, and evaluation. I also learned how to interpret evaluation metrics and compare models in terms of performance. This project enhanced my understanding of text cleaning, TF-IDF, classification algorithms, and practical applications of NLP in real-world sentiment analysis tasks.
