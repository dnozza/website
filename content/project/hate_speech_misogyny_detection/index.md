---
aliases: [hatespeech]
title: Hate Speech and Misogyny Detection 
summary: How fair Machine Learning models could solve Hate Speech and Misogyny Detection?
abstract: ""
date: "2020-01-27T00:00:00Z"
image:
  caption: '[Photo by Kyle Glenn on Unsplash](https://unsplash.com/photos/kvIAk3J_A1c)'

  focal_point: Smart

categories:
- hate speech
tags:
- hate speech
- misogyny detection
- nlp
---



While the exponential growth of **Social Media** such as Twitter and Facebook has permit people to freely express themselves in various forms (text, video, images), these new sources of communication, where anonymity or pseudo-anonymity enables the possibility to afflict a target without being recognized or traced, has led to an increasing propagation of hate speech. Automatic Machine Learning models for the detection of **Hate Speech** could help in preventing or automatically reporting these misbehaviors and consequently reduce the episodes of misogyny, racism, homophobia and cyberbullying. This could be helpful both for protecting individuals’ health and also to monitor public reactions to events.

In order to provide a benchmark dataset for **Hate Speech** and **Misogyny Detection**, I have contributed to the organization of the [Automatic Misogyny Identification](https://amievalita2018.wordpress.com/)(AMI) shared task at Evalita 2018 in Italian and English language and of the [HatEval](https://competitions.codalab.org/competitions/19935) task at SemEval 2019 about the detection of hate speech against immigrants and women in Spanish and English messages extracted from Twitter. 

*These tasks permit to create and share the first labelled corpora for misogyny detection in Spanish and Italian. I firmly believe that we still have a long way to go: there are 3,909 written languages in the world, most without misogyny data sets. Moreover, we need to assure that data collection methodologies are the same across all languages in order for them to be valuable.*🌎🌍🌏

After collecting these data, I made some preliminary investigation on the presence of [unintended bias](https://dl.acm.org/doi/10.1145/3350546.3352512) in machine learning models for **Misogyny Detection**. This can lead the models to recognize positive or neutral texts as hate speech texts only because it contains certain terms (e.g. woman, girl).

When training a supervised machine learning model for hate speech detection, it is important to guarantee the **fairness** of the model and therefore to reduce the error due to unintended bias, i.e. the attitude of a model to perform better on comments about some groups than for comments about others groups. 
As you can read in [my work](https://dl.acm.org/doi/10.1145/3350546.3352512) presented at International Conference on Web Intelligence (WI '19), the presence of this bias lead very accurate models to recognize positive or neutral texts as misogynous contents only because they contains certain terms (e.g. woman, girl). *Can you imagine seeing "You're a smart woman" predicted as misogynous just because it's talking about women?* 🤦‍♀️

📣📣 **NEWS**: We are organizing [AMI 2020](https://amievalita2020.github.io/) at Evalita!! Stay updated by [following me](https://twitter.com/debora_nozza) on Twitter and joining the Google Group [amievalita2020](https://groups.google.com/d/forum/amievalita2020)!





