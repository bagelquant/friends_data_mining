# Data description

We are using five datasets in this project:

- `data/friends_quotes.csv`: sourced from [Kaggle link](https://www.kaggle.com/datasets/ryanstonebraker/friends-transcript)
  - `author`: The character who said the quote
  - `episode_number`: episode number
  - `episode_title`: episode title
  - `quote`: the quote itself
  - `quote_order`: the order of the quote in the episode
  - `season`: the season number

Sentiment analysis datasets: [Kaggle link](https://www.kaggle.com/datasets/ekrembayar/sentiment-lexicons-for-text-mining)

- `data/afinn.csv`: AFINN-111 sentiment analysis word list
  - `word`: the word
  - `value`: range from -5 (very negative) to +5 (very positive)
- `data/bing.csv`: Bing Liu's opinion lexicon
  - `word`: the word
  - `sentiment`: range from -1 (negative) to +1 (positive)
- `data/loughran.csv`: Loughran-McDonald sentiment word list
  - `word`: the word
  - `sentiment`: negative and positive
- `data/nrc.csv`: NRC Emotion Lexicon
  - `word`: the word
  - `sentiment`: the sentiment (e.g. anger, anticipation, disgust, fear, joy, sadness, surprise, trust)

## Acknowledgements

The raw transcripts of every episode were originally scraped from here: [Friends quotes](https://fangj.github.io/friends/).
Additional work cleaning up the data and removing invalid rows was done by [Jorge Nachtigall](https://www.kaggle.com/jorgenachtigall)
