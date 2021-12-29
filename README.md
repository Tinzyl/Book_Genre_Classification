# Book_Genre_Classification
### In this project, I built a model that classifies Book Genres. I used Natural Language Processing to categorize the genres, and then I used classification models(MultinomialNB and the Support Vector Classifier) to make the predictions of what genre the text belongs to. The steps which were taken to build this model were as follows:
- Perform Data Preprocessing and EDA(i.e. use NLP to remove stopwords, perform lemmatization, perform stemming, perform encoding on the genres).
- Use CountVectorizer and TfidfVectorizer to build feature vectors of the words and fit them to the estimators. 

## Results
### CountVectorizer

MultinomialNB Accuracy | Support Vector Classifier Accuracy 
-----------------------|------------------------------------
66%                    | 56%                               

### TFIDFVectorizer

MultinomialNB Accuracy | Support Vector Classifier Accuracy 
-----------------------|------------------------------------
78%                    | 78%                                

The tfidfVectorizer performed the best and both the MultinomialNB and the Support Vector Classifier had the same accuracy of **78%**.
