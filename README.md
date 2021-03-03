# Assessing the funniness of news headlines
Competition/Coursework - Imperial College NLP course

We used two approaches for this challenge:
The first, we every tool provided on internet (approach 1). The second, with no loaded models or embeddings (approach 2).

## Approach 1
For the approach 1, we used a BERT model, that we slightly modified and trained for our need. The code can be found in the file [nlp_approach1.ipynb](./nlp_approach1.ipynb).
To run it, you need to make sure you have train.csv, dev.csv and test.csv in the same folder as the jupyter notebook.

## Approach 2
For the approach 2, we tried to be more creative: we associated an embedding of the headlines with some engineered features and passed it through a neural network. The code for this approach can be found in [nlp_approach2.ipynb](./nlp_approach2.ipynb). Similarly, you need to make sure you have train.csv, dev.csv and test.csv in the same folder as the jupyter notebook.



## Interesting articles
### Use BERT with PyTorch
- By far my favorite along the 3/4 sources that I had a look at: [BERT Fine-Tuning Tutorial with PyTorch for Text Classification on The Corpus of Linguistic Acceptability (COLA) Dataset.](https://medium.com/@aniruddha.choudhury94/part-2-bert-fine-tuning-tutorial-with-pytorch-for-text-classification-on-the-corpus-of-linguistic-18057ce330e1)
- More straight to the point : [Fine-Tuning BERT model using PyTorch](https://medium.com/@prakashakshay/fine-tuning-bert-model-using-pytorch-f34148d58a37)
### Use BERT for a specific task (regression is quite a rare task in NLP - classification being much more used)
- Get inspiration from the source code : [BERT for classification model](https://huggingface.co/transformers/_modules/transformers/models/bert/modeling_bert.html#BertForSequenceClassification)
### A guys talking about what he did for this codalab competition
- Not amazing but interesting though : [Assessing the Funniness of Edited News Headlines](https://medium.com/@cselig/assessing-the-funniness-of-edited-news-headlines-3ec03056f29a)


