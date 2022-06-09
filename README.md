# MINDS_programming_challenge

## Data Format
Data are stored in the json file. The following information of each article has been collected:
- Title
- Link
- Abstract
- Date
- Content

## Sentiment Analysis Approach
I used the built-in, pretrained sentiment analyzer in the NLTK package. The analyzer will give us the negative, neutral, positive, and compound scores of the corpora. And I used the compound score as the final sentiment.
