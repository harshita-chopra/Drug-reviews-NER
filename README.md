# Named Entity Recognition of Drugs in medical reviews

In this project, we work on the famous Drug Review dataset (downloaded from UCI Machine Learning repository https://archive.ics.uci.edu/ml/datasets/Drug+Review+Dataset+%28Drugs.com%29)

NER, short for, Named Entity Recognition is a standard Natural Language Processing problem which deals with information extraction. The primary objective is to locate and classify named entities in text into predefined categories.
SpaCy provides a default model that can recognize a wide range of named or numerical entities, which include person, organization, language, event, etc. 

Apart from these default entities, we can also add arbitrary classes to the NER model, by training the model to update it with newer trained examples. In this repo, the **spacy_modelling.ipynb** notebook contains a python script which trains a blank SpaCy model to identify drug names in a set of reviews.
