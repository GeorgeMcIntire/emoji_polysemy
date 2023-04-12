# emoji_polysemy

This is the repo for my Emoji Polysemy project.

In this project I use a version of BERT trained on tweets to extract contextual embeddings for a selection of emojis. Then for each emoji, I cluster their collection of embeddings. The clusters produced by this process represent the various semantic meanings of an emoji. The goal of this project is to quantify an emoji's polysemy and determine if there are any temporal patterns in the usage rate of those clusters over the span of 2014 to 2022.

![image](prayer_hands_tsne.png)