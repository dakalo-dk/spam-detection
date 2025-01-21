# spam-detection

This project is about detecting spam messages from the normal ones using SMS dataset.
This dataset is imbalanced, which is expected, with most messages being normal (87%) compared to spam (13%) messages.

![image](https://github.com/user-attachments/assets/793f50ca-4b5e-47b7-8514-c4132ade2a9e)

# Steps

1. Import required libraries
2. Loaded data
3. Create Wordcloud
4. Experiments:
   * Use defualt CountVectorizer except for english stopwords
   * Use default TfidfVectorizer except for english stopwords
   * Use Stemming
   * Use Lemmatization
5. Train Naive Bayes ML model
6. Model Evaluation
7. Compare model performance based on the four experiments
8. Conclusion: Default CountVectorizer perfomed best
9. Deploy the model using FastAPI

# Confusion Matrix

![image](https://github.com/user-attachments/assets/49e4b490-04e1-4404-aae1-b7925b631f99)

# ROC Curve

![image](https://github.com/user-attachments/assets/ac4b0b67-d617-4152-8218-d0bbccf6410a)

# Word Cloud

## Spam Words

![image](https://github.com/user-attachments/assets/8be84940-85dd-4638-b981-ce25aa47322d)

## normal words

![image](https://github.com/user-attachments/assets/0283bab8-68ad-481c-b2e7-f442ccf864dd)






