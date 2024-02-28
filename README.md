# Summary
Indonesia's presidential election will be held in February 2024. This event will certainly gains a lot of discussion and/or opinions.
This project obtained data from X posts then tries to classify wether that posts containing positif or negative sentiments. Using TF-IDF as weighting method, this project did 3 training
with different data split rasio namely; 80:20, 50:50, 30:70. Since the dataset is in Bahasa, this project utilized sastrawi for preprocessing purpose.

## Tools
- Jupyter Notebook
- Pandas
- Sklearn
- Sastrawi

## Language
- Python

## Steps
- Import dataset
- Preprocessing (Cleansing, Case folding, Tokenizing, Stopword Removal, Stemming)
- Weighting (Term Frequency - Inverse Document Frequency)
- Data Training (Splitted three times; 80:20,50:50,30:70)
- Evaluation (Confussion matrix)
