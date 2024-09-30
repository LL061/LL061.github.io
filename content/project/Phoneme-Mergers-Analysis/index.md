---
title: Historically Attested Phoneme Mergers Analysis
date: 2024-09-01
# external_link: https://github.com/pytorch/pytorch
authors:
  - Chris Brendel
  - Admin
  - Simon Todd

share: false
---

Explore the effect of functional load on historically attested phoneme mergers with the help of language model

<!--more-->

The project explores the relevance of syntactic and semantic factors to historically attested phoneme mergers in a number of different languages. A phoneme merger is when two sounds come to be pronounced the same; for example, in Californian English (and the English of most areas in the Western US), the vowels in the words "cot" and "caught" are now pronounced identically, even though they were originally pronounced differently. The project follows up on a recent thread of work toward a big idea in linguistic theory, the Functional Load Hypothesis, which claims that phonemic contrasts such as the difference between the "cot" and "caught" vowels are less likely to be lost over time if they do a lot of "work" in distinguishing words in a language; in other words, that languages tend not to lose features that play a large role in preventing ambiguity in communication. 

In our study, we adopted the word2vec language model to measures the syntatic and semantic similarity between minimal pairs, and we aimed to test if phonemes that distinguish more minimal pairs with higher similarity scores are less likely to merge. 



