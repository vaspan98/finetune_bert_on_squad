# finetune_bert_on_squad
Fine-tuning of bert-base-uncased on SQuAD dataset  

## Platform
Google Collab

## Language
Python

## Libraries
PyTorch, Transformers, Pandas, Numpy

## Description / Goals
The purpose of this project is to develop a simpler and lighter version of the official Hugging face example [Fine-tuning a model on a question-answering task](https://github.com/huggingface/notebooks/blob/master/examples/question_answering.ipynb) where `distilbert-base-uncased` is trained on the SQuAD dataset.
In order to achieve that we use a smaller sample of the [SQuAD 2.0 dataset](https://rajpurkar.github.io/SQuAD-explorer/) (86821 samples of the `train-v2.0.json` dataset and 10388 samples of the `dev-v2.0.json` dataset)  on which we fine-tune the `bert-base-uncased` model. 

## Tips
Add the `train-v2.0.json` and `dev-v2.0.json` datasets in your `gdrive/My Drive/Colab Notebooks/` path to execute correctly

Suggested Runtime Type: GPU

## Author
Vassilis Panagakis

## Date
February 2021
