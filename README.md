# Amazon-Reviews-Sentimental-Analysis
This project aims to classify the sentiment of Amazon customer reviews using Natural Language Toolkit's VADER sentiment analysis tool and the huggingface Roberta Transformers package. We also compare the results of the sentiment analysis performed by both packages.

## Dataset
We used a dataset of Amazon customer reviews, which contains reviews for various products across different categories such as books, electronics, and kitchen appliances. The dataset consists of around 300,000 reviews with ratings ranging from 1 to 5 stars.

## Preprocessing
Before performing sentiment analysis, we preprocessed the dataset by removing any non-alphabetic characters, converting all text to lowercase, and removing stop words. We also performed stemming to reduce words to their base form.

## Sentiment Analysis
We performed sentiment analysis on the preprocessed dataset using both VADER and Roberta Transformers. VADER is a rule-based sentiment analysis tool that uses a lexicon of words and their sentiment scores to classify the sentiment of text. Roberta Transformers is a state-of-the-art language model that uses deep learning techniques to perform sentiment analysis.

We compared the results of the sentiment analysis performed by VADER and Roberta Transformers and found that the two packages produced different sentiment scores for the same text. We further analyzed the differences in the results and identified some of the factors that may have contributed to the variations.

## Tools
- Anaconda
- Jupyter Notebook
- Python Libraries(pandas,Numpy,seaborn matplotlib,re..etc)

## Conclusion
This project demonstrates how to perform sentiment analysis on Amazon customer reviews using two different packages and how to compare the results. The differences in the results highlight the importance of understanding the limitations and assumptions of the sentiment analysis tools being used. Overall, this project provides a starting point for anyone interested in sentiment analysis and its applications.
