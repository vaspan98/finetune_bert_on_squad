# finetune_bert_on_squad
Fine-tuning of bert-base-uncased on SQuAD dataset  

## Platform
Google Collab

## Language
Python

## Libraries
PyTorch, Transformers, Pandas

## Description / Goals
The purpose of this project is to develop a simpler and lighter version of the official Hugging face example [Fine-tuning a model on a question-answering task](https://github.com/huggingface/notebooks/blob/master/examples/question_answering.ipynb) where `distilbert-base-uncased` is trained on the SQuAD dataset.
In order to achieve that we use a smaller sample of the [SQuAD 2.0 dataset](https://rajpurkar.github.io/SQuAD-explorer/) where we fine-tune the `bert-base-uncased` model. For a more detailed clarification of the code's functionality follow the link above.

We utilize 
is the developement of a document retrieval system that returns titles and passages of scientic papers containing the answer to a given user question. In order, to achieve that we use different pretrained BERT models applied on the latest version (2020-03-13) of the COVID-19 Open Research Dataset (CORD-19). Specifically, we process the articles in the folder 'comm_use_subset' and we utilize the metadata provided in the 'all_sources_metadata_2020-03-13.csv' file. <br>
We implement 2 models for the titles retrieval task and 2 different models for the passages retrieval task. We evaluate our experiments based on the mathematical-theoretical background of each model. We compare the results of our models based on:
* their architecture
* their execution time
* the cosine similarity score of the retrieved answer


## Tips
Add the 'train-v2.0.json' and 'dev-v2.0.json' datasets in your 'gdrive/My Drive/Colab Notebooks/' path to execute correctly

Suggested Runtime Type: GPU

## Author
Vassilis Panagakis

## Date
February 2021
