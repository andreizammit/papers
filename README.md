# Research Papers
A collection of published and unpublished papers targeting Artificial Intelligence, Natural Language Processing and Big Data

## A Dependency Parser for the Maltese Language using Deep Neural Networks
The research paper for Masters in Artificial Intelligence, University of Malta

### File
Andrei_Zammit_ICS5200_Paper.pdf

### Abstract
Tasks such as information retrieval, sentiment analysis and question answering require the processing of text analysis and natural language processing. Sentence parsing is one of the tasks performed in NLP to analyse the grammar structure of a sentence, with the aim of determining the relationships between the words in a sentence.

Whilst there are several parsers for many European languages, Maltese remains a low-resourced and low-researched language and currently there are no parsers for the Maltese language. This work investigates computational parsing of Maltese by using novel Deep Learning and source bootstrapping techniques, with the aim of contributing not only to the increase in computational resources for Maltese, but also to dependency parsing. 

The evaluation of the parser was performed according to the Conference on Computational Natural Language Learning (CoNLL) standards and metrics. Experiments were conducted using datasets provided during CoNLL 2017 except for the Maltese language dataset which is provided directly by the author.

Results show an Unlabelled Attachment Score of 90\% and Labelled Attachment Score of 86\% by using a Quasi-Recurrent Neural Network (QRNN) with a bootstrapped data source of Maltese and other Romance languages. Bi-directional LSTM Neural Networks outperform QRNN by less than 0.2\% in both metrics however, QRNN achieve a three-fold runtime performance over bi-LSTM. To our knowledge, this is the first time that QRNN is applied to the task of dependency parsing. The use of bootstrapped data sources is not documented in the published papers and proceedings of the 2017 shared task we reviewed. 

- - - -

