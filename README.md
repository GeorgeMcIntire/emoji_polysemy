# emoji_polysemy

This is the repo for my Emoji Polysemy project.

In this project I use a version of BERT trained on tweets to extract contextual embeddings for a selection of emojis. Then for each emoji, I cluster their collection of embeddings. The clusters produced by this process represent the various semantic meanings of an emoji. The goal of this project is to quantify an emoji's polysemy and determine if there are any temporal patterns in the usage rate of those clusters over the span of 2014 to 2022.


### Notebooks

- [Emoji Cleaning and Analysis](Emoji%Cleaning%and%Analysis.ipynb) 
Where I clean, munge, and transform the raw twitter data. Here I extract the embeddings and save them.
- [Topics, Emoition, and Sentiment Extraction](Topics%2C%20Emotion%20and%20Sentiment%20Extraction.ipynb)
- [EDA Effnet Genres](EDA\ Effnet\ Genres.ipynb)
- [EDA Style Classification](EDA\ Style\ Classification.ipynb)

![image](prayer_hands_tsne.png)