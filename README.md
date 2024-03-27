# Movie-Review-Sentiment-Analysis

This project is done as part of the Machine Learning Practices project of IIT Madras BS degree. 
In the dataset, each record represents a movie review pair with a movie title, description, genres, duration, director, actors, users' ratings, review text, reviewer name, etc. 
## My task was to build an ML model to predict the sentiment of the review text.
- Implemented classification algorithms for sentiment analysis of movie reviews.
- Improved results through hyperparameter tuning, and cross-validation and achieved an accuracy score of 80 (F1 score)
- Tech Stack: scikit-learn, Logistic Regression, Gradient Boost, Random Forest, XGBoost, seaborn, matplotlib.

Dataset Description

**Files**
- train.csv - the training set containing the review sentiment along with other features.
- test.csv - the test set, has review features, but no sentiment column, since it is the target.
- movies.csv - the file with metadata on movies.
  
**Columns**
- movieid - named id of the movie
- sentiment - indicating "POSITIVE" or "NEGATIVE", which is the target.
- Other columns are self explanatory.
