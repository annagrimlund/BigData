

# BigData
Competition link:
  - https://www.kaggle.com/competitions/tmdb-box-office-prediction/overview

Presentation
- how we preprocessed the data and why we removed stuff
- which models we tried and which one was best fit
- result/performance

Code clean up:
  - collection convert to boolean values (part of collection yes/no)
  - language (3 categories)

transform into bolean value
  - homepage --
  - belongs to collection
  - original language (english or not)

transoformed
- realese data --> release year, season, weekday
- runtime --> missing values were filled manually
- overview --> counting nbr of words
- tagline --> counting nbr of words
- genres --> multiclass hot encoding to 

Counting how many of each
  - production country
  - spoken language
  - key word
  - tagline
  - cast
  - crew


Columns to remove:
  - imdb_id
  - original_title
  - poster path
  - status
  - title
