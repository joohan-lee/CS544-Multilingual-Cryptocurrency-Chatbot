# CS544-Multilingual-Cryptocurrency-Chatbot

## Introduction

A chatbot is a robot that understands cus-
tomer questions and provides helpful an-
swers quickly. With advances in natural
language processing, chatbots are becom-
ing increasingly popular in various fields.
We implemented a cryptocurrency chatbot
application utilizing TF-IDF, Word2Vec,
BERT, and SIF embedding models in this
project. To assist in answering questions
in multiple languages, a translating mod-
ule was developed that recognizes the lan-
guage type and translates the contents if
needed. The results of measuring the co-
sine similarity showed high accuracy of
the models implemented, especially for
BERT and SIF. Additionally, the response
can be generated in the language entered
by the user.

## Install

```bash
git clone --recurse-submodules https://github.com/joohan-lee/CS544-Multilingual-Cryptocurrency-Chatbot.git
cd CS544-Multilingual-Cryptocurrency-Chatbot
pip3 install -r requirements.txt
```

## How to chat

```bash
python multilingual_chatbot.py
```
