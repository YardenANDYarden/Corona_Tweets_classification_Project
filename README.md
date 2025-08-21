#Corona Tweets Sentiment Analysis with BERT & RoBERTa 

## Project Overview
This project performs sentiment analysis on COVID-19 related tweets using two state-of-the-art transformer models:
- **BERT Base Uncased**: General-purpose language model
- **Twitter RoBERTa Base**: Specialized model pre-trained on Twitter data



## Quick Start

### Prerequisites
- Python 3.8+
- PyTorch
- Transformers library
- Jupyter Notebook


## Download required data files:
   
   **IMPORTANT:** 
   
    - When running: `git_Final_report_test_cardiffnlp.ipynb`,`Final_report_test_Bert-base-uncased.ipynb` or any code from Compression folder:
   - Download data files from: https://drive.google.com/drive/folders/106ZMER63xe-W9CrslRpyjUMtUpF7rb9Z?usp=sharing
   - Extract and place all files in the `data/` folder
   
   **For Final Report Execution:**
   - When running `git_Final_report_test_cardiffnlp.ipynb`, download additional files from: https://drive.google.com/drive/folders/1SQqFX_sUHeb_rtbhUHx6C-9vch3WQb8L?usp=sharing
   - Extract and place all files in the `data/` folder
   

## Project Structure

### `/Compression`
Contains model compression implementations and experiments:
- `MODEL2_OPTUNA_COMPRESSION` - Optuna-based pre traind Twitter RoBERTa Base model compression
- `MODEL3 HF COMPRESSION.ipynb` - HuggingFace pre traind Twitter RoBERTa Base model compression
- `MODEL_COMPRESSION.ipynb` - All of BERT Base Uncased pre traind models compression notebook

### `/bert-base-uncased-training`
BERT model training and fine-tuning:
- `.gitkeep` - Git folder tracking
- `BERT-base-uncased-API-traning` - API-based BERT training
- `BERT-base-uncased-optuna-train` - Optuna optimization for BERT training
- `Final_report_test_Bert-base-uncased.ipynb`- **TEST report notebook for all bert-base-uncased pre- trained models**

### `/data`
Dataset files and processed data:
- `Corona_NLP_test.csv` - Test dataset for Corona NLP task
- `Corona_NLP_train.csv` - Training dataset for Corona NLP task
- `augmented_1.csv` - First augmented dataset
- `augmented_light333.csv` - Lightweight augmented dataset
- `test_processed.csv` - Preprocessed test data
- `train_processed.csv` - Preprocessed training data
- `val_processed.csv` - Preprocessed validation data

### `/notebook`
Jupyter notebooks for data analysis and experiments:
- `git_Cleaning_and_augmentation.ipynb` - Data cleaning and augmentation pipeline
- `git_EDA_corona_tweets.ipynb` - Exploratory data analysis for Corona tweets

### `/twitter-roberta-base-training`
RoBERTa model training and evaluation:
- `dir_cardiffnlp_API_training.ipynb` - Cardiff NLP API training
- `git_Final_report_test_cardiffnlp.ipynb` - **TEST report notebook for all twitter-roberta pre- trained models**
- `git_cardiffnlp_optuna_training.ipynb` - Optuna optimization for RoBERTa


