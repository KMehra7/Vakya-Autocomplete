# NLP
Computational and Linguistics NLP Final Project

# Abstract
Autocomplete is a feature which predicts what would be the next most probable word based on what we have written so far. Hinglish (Hindi-English) is a language which is quickly gaining popularity. The words are written in English language but they mean something in the Hindi language. It is primarily spoken in the Indian subcontinent.

# What we plan to do
We plan to use N-gram model to derive the probabilities of the next word based on the previous ones and return the result which is a combination of multiple suggestions.

# Dataset
There aren’t readily available datasets available due to the fluid nature of the language as people use different spellings for the same word so we need to either create our own from scratch or modify the existing ones. For our work we have used the dataset_0 file from the following link and added our own sentences to it as well-
https://www.kaggle.com/datasets/thanatoz/hinglish-blogs

# Results
Sentence in corpus: “kar sakte hai.”

Input given: 

<img width="300" alt="image" src="https://github.com/user-attachments/assets/be788d27-89fe-450e-857f-deb5a8169a3a">

---
Expected outcome:

Kar sakte hai".”

--- 
Actual outcome: 

<img width="300" alt="image" src="https://github.com/user-attachments/assets/02d662d9-3413-4c9d-8013-d06d46c8d1ba">

# Conclusion
In this project we used N-gram models to calculate the frequencies of the words existing in our corpus and thereby finding the most probable words depending upon if we were using Unigrams, Bigrams, Trigrams, Quadgrams and Quintgrams. 
We observed that giving more than 5-grams the output doesn’t improve.
