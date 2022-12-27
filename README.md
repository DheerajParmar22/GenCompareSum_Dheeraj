# GenCompareSum_Dheeraj

Pre-trained Language Models (PLMs) have been used to improve the
performance of TS. However, PLMs are limited by their need of labeled training data and by
their attention mechanism, which often makes them unsuitable for use on long documents. To
this end, we propose a hybrid, unsupervised, abstractive-extractive approach, in which we walk
through a document, generating salient textual fragments representing its key points. We then
select the most important sentences of the document by choosing the most similar sentences to
the generated texts, calculated using BERTScore. We evaluate the efficacy of generating and
using salient textual fragments to guide extractive summarization on documents from the
biomedical and general scientific domains. We compare the performance between long and
short documents using different generative text models, which are fine tuned to generate
relevant queries or document titles. We show that our hybrid approach outperforms existing
unsupervised methods, as well as state-of-the-art supervised methods, despite not needing a
vast amount of labeled training data.
