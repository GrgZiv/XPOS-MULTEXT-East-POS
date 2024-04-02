# About

***MULTEXT-East*** is a multilingual dataset for language engineering research, focused on the morphosyntactic level of linguistic description1. It includes morphosyntactic specifications, morphosyntactic lexica, and a parallel corpus. The resources cover 16 languages, mainly from Central and Eastern Europe.

***The XPOS tagging***, also known as treebank-specific POS tagging, is a more detailed form of Part-of-Speech (POS) tagging, used in MULTEXT-East. A POS tagset is a list of part-of-speech tags (POS tags for short), i.e., labels used to indicate the part of speech and sometimes also other grammatical categories (case, tense etc.) of each token in a text corpus.

- Project consists of 3 notebooks:
    1. Data Preprocessing
    2. Model Training
    3. Model Testing

- The python notebooks are made to run in Google Colab (preferably on T4 GPU).

# Objective

- Train a custom model to do XPOS classification with a weighted F1 score of at least 0.90. 

# Dataset

The hr500k training corpus contains about 500,000 tokens manually annotated on the levels of
tokenisation, sentence segmentation, morphosyntactic tagging, lemmatisation and named entities.
- Download the dataset: https://www.clarin.si/repository/xmlui/handle/11356/1792