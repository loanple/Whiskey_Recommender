# Whiskey Recommender
Through sentiment analysis, the model empirically categorizes reviews on a positive, negative, neutral, compounded or polarity score from -1 to 1. The model utilizes the scores to create recommendations. 


## Dataset
The dataset contains reviews for various whiskey brands. The dataset has 2,247 observations & 6 featured variables. The variables include:
  - Name of Whiskey
  - Category of Whiskey
  - Review Point (scale from 1-5)
  - Price of Whiskey
  - Currency of Price
  - Description of Review
  
 ## Data Cleaning 
Set up reviews for sentiment analysis by:
  - Changing all text to lowercase
  - Tokenizing words and removing punctuation
  - Removing common and custom stop words
  - Lemmatizing text (e.g. commitment → commit)
  - Removing one letter words
  
 ## Sentiment Analysis
 Used 2 lexicons - Vader and Textblob to analyze the sentiment of reviews.
  - **Vader Lexicon** categorizes positive and negative words by also taking into account the context of sentence to determine 4 scores from *neutrality, positivity, negativity, and compounded*. These scores are rated from *-1 to 1*. 
  - **Textblob Lexicon** computes a *polarity score* from *-1 to 1*
  
  ## Recommendation System
  
 

 
