#Corona Tweets Sentiment Analysis with BERT & RoBERTa 

## 📋 Project Overview
This project performs sentiment analysis on COVID-19 related tweets using two state-of-the-art transformer models:
- **BERT Base Uncased**: General-purpose language model
- **Twitter RoBERTa Base**: Specialized model pre-trained on Twitter data

## Project Structure
```
corona_tweets_classification_project/
│
├── data/                                 # All datasets
│   ├── Corona_NLP_train.csv            # Original training data
│   ├── Corona_NLP_test.csv             # Original test data
│   ├── train_processed.csv             # Cleaned training data
│   ├── val_processed.csv               # Cleaned validation data
│   └── test_processed.csv              # Cleaned test data
│
├── notebook/                             # Preprocessing notebooks
│   ├── EDA_corona_tweets.ipynb         # Exploratory Data Analysis
│   └── data_cleaning.ipynb             # Data cleaning and preprocessing
│
├── models/                               # Model training directories
│   ├── bert-base-uncased/
│   │   ├── training_bert.ipynb         # BERT training notebook
│   │   └── README.md                   # BERT model documentation
│   │
│   └── twitter-roberta-base/
│       ├── training_roberta.ipynb      # RoBERTa training notebook
│       └── README.md                   # RoBERTa model documentation
│
├── results/                              # Training outputs
│   ├── bert/                           # BERT results
│   └── roberta/                        # RoBERTa results
│
├── create_project_structure.py          # Setup script
├── requirements.txt                      # Python dependencies
├── .gitignore                           # Git ignore rules
└── README.md                            # This file
```

