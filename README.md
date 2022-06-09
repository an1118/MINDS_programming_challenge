# MINDS_programming_challenge

## Data Format
Data is stored in the json file. The following information from each article has been collected:
- Title
- Link
- Abstract
- Date
- Content

## Sentiment Analysis Approach
I used the built-in, pretrained sentiment analyzer in the NLTK package. The analyzer will give us the negative, neutral, positive, and compound scores of the corpora. And I used the compound score as the final sentiment.

## Running the File
The solution code has four parts: collecting data, data pre-processing, sentiment analysis and visualization. You can run all cells from the beginning and it will create a json file storing collected data in the same folder as your code file. <br/>

Please uncomment this line in the sentiment analysis part when you run the code for the first time. <br/>

```
nltk.download('vader_lexicon')
```

## Total Operation Time
The total operation time of solution.ipynb is 5.90s.
