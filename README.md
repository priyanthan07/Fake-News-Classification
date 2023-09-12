# Fake-News-Classification

## description
In the field of natural language processing, the detection of fake news is a popular topic. In our everyday routine, we absorb news through a variety of sources, but occasionally it can be challenging to distinguish between fake and real news. Our task is to develop a model that can determine whether a particular piece of news is true or false.

## requirements

    import pandas as pd
    import numpy as np
    import re
    import nltk
    from nltk.corpus import stopwords
    from nltk.stem import PorterStemmer, WordNetLemmatizer
    from sklearn.model_selection import train_test_split
    from sklearn.ensemble import RandomForestClassifier
    from sklearn.feature_extraction.text import TfidfVectorizer
    from sklearn.metrics import accuracy_score, confusion_matrix, classification_report

## Process
   1. data gathering
   2. Data preprocessing
   3. vectorization
   4. Train and Test dataset split
   5. model building
   6. model evaluation
   7. checking the accuracy of training dataset
   8. checking accuracy on testing dataset
   9. Building prediction pipeline
      
