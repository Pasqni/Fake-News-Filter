# Fake News Filter

## Project Description
This project focuses on developing a Natural Language Processing (NLP) solution to address the escalating issue of fake news. With the exponential growth of social media over the past decade, the spread of fake news has become a significant problem. In response, the United States government tasked the company with creating a filter capable of identifying fake news. The goal was to develop a model that can accurately distinguish between real and fake news, which would then be deployed by the machine learning engineers and web developers on our team.

## Objective
The primary objective was to create a robust NLP model that can recognize fake news articles. We were provided with two datasets: one containing only fake news and the other containing only real news. These datasets were used to train the model.

## Datasets
The project utilized two distinct collections of news articles:

- Fake News Dataset: Contained articles confirmed to be false.
- Real News Dataset: Contained articles confirmed to be true.

## Analysis and Model Training
### Initial Analysis
An in-depth analysis was conducted to answer key questions such as:

- Are fake news articles more frequent in certain categories?
- Within each category, are there specific topics that are more prone to fake news?
- Do fake news headlines exhibit distinct patterns?

### Model Development
- Data Preprocessing: The data was cleaned and prepared for model training, including tokenization, removing stop words, and other relevant preprocessing steps.
- Feature Extraction: Features were extracted from the text data using techniques such as TF-IDF, word embeddings, and other NLP methodologies.
- Model Training: Various machine learning models (e.g., logistic regression, SVM, random forest, neural networks) were trained on the prepared datasets.
- Evaluation: The model's performance was evaluated using appropriate metrics such as accuracy, precision, recall, and F1-score.

### Model Export
After training and evaluating the model, it was exported using `Pickle`.

## Summary
This project successfully delivered an NLP-based solution for detecting fake news, addressing a critical need in the era of social media. The developed model, trained on distinct datasets of real and fake news, enables accurate identification of false information.
