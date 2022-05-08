# Query Product Ranking

<img width="500" alt="Screen Shot 2022-05-07 at 8 51 49 PM" src="https://user-images.githubusercontent.com/69778066/167278431-32511d2c-e993-4412-b06d-44200fabb49c.png">

## Repo Files
**This repo contains 5 main different notebooks that accomplish a different steps and models of this project:**

- 01: `01-read-data.ipynb`: Reading in data [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1cZ7P3Xm0BYL1f-yqo-LzJl7At5ySBc7W)
- 02: `02-sentence-embedding.ipynb`: Create the sentence embeddings by BERT models [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1fNsX-cSF1fqSTT72UWeEyAKnKrTD4miG)
- 03: `06-fine-tune-our-dataset.ipynb`: Multi-Genre Natural Language Inference [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1RErLqYTw5IoVPjzSeBbhvGibbVCzMycD)
- 04: `05-Train-CrossEncoder-scores.ipynb`: Cross-Encoder Regression Model [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1c5Vph8-NlBJVJLGkVYYKNBfp7_pv0jGF)
- 05: `04-Train-CrossEncoder-classification.ipynb`: Cross-Encoder Classification Model [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1c6RH_aqJZVc2Vfg6xPlV9cWmH52nlIF_)

## Overview
Nearly everyone in our Social Network Class has utilized a recommender system one way or another, whether it be browsing through recommended items on a online clothing retail store, viewing advertisements that pop up on the side of our screen, or even when grocery shopping online. Our group wanted to explore what goes behind building these systems and how a computer identifies between relevant to irrelevant items. 

Our project was based on the Amazon KDD Cup 2022 where the overall goal of the competition was to ultimately improve the relevance of search results. This is an important task as such improvements can significantly enhance the customer experience and increase their engagement with the online Amazon platform. While there have been made incredible advancements int he field of machine learning and data science as a whole, accurately classifying items in a recommender system remains a challenging task. Some of these difficulties range from noisy datasets, ambiguous query searches, and the potential lack of diversity in the items available. Further, the goals of recommender systems is not only to accurately classify relevant items, but also to rank them in order of relevance. 

