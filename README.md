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

- Type your question: What is the best cryptocurrency?<br>

  > Bitcoin has not just been a trendsetter, ushering in a wave of cryptocurrencies built on a decentralized peer-to-peer network, it's become the de facto standard for cryptocurrencies , inspiring an ever-growing legion of followers and spinoffs. What is cryptocurrency and altcoin? Before we take a closer look at some of these alternatives to bitcoin, let's step back and briefly examine what we mean by terms like cryptocurrency and altcoin. A cryptocurrency, broadly defined, is virtual or digital money which takes the form of tokens or coins. While some cryptocurrencies have ventured into the physical world with credit cards or other projects, the large majority remain entirely intangible. The crypto in cryptocurrencies refers to complicated cryptography which allows for a particular digital token to be generated, stored, and transacted securely and, typically, anonymously. Alongside this important crypto feature of these currencies is a common commitment to decentralization; cryptocurrencies are typically developed as code by teams who build in mechanisms for issuance (often, although not always, through a process called mining) and other controls. Cryptocurrencies are almost always designed to be free from government manipulation and control.check affiliatecoin.tech for more. cryptosbinary provide all the resources you need to seamlessly flow through the experience of investing crypto 24/7. Cryptocurrency exchanges are for traders. (www.cryptosbinary,com) is the easiest, most convenient platform for both beginners and cryptocurrency enthusiasts.They are a non-custodial platform, meaning that your crypto is securely and instantly delivering of your 40% ROI investment directly to your personal wallet after 7 days of investment.

- Type your question: What is the current price of Bitcoin?
  > The current price of Bitcoin is 17,092.50 United States Dollar.
