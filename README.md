# NLP-varun-sain-2301201134-project-1

Project 1: University FAQ Chatbot

Goal: Create a chatbot that answers student queries about university information such as admissions, fees, timetable, hostel, exams, etc.

Concepts Used:

Text preprocessing (tokenization, stopword removal, lemmatization)

TF-IDF or Word Embeddings for query matching

Cosine similarity for retrieving the best answer

Tools: Python (NLTK, Scikit-learn, or spaCy)

Dataset: Self-created CSV with Question and Answer pairs (example:

Question: "How much is the admission fee?"

Answer: "Admission fee is 5000.")

Workflow Solution:

Preprocess FAQ dataset: Tokenize, remove stopwords, lemmatize all questions and answers.

Preprocess user input query: Same steps as above.

Similarity Calculation: Compute cosine similarity between the user query and FAQ dataset (using TF-IDF or embeddings).

Retrieve Answer: Return the best matching answer from the dataset.
