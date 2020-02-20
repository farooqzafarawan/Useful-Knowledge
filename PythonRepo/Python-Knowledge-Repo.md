# NLP Resources
## awesome-nlp
A curated list of resources dedicated to Natural Language Processing

## Chatbot
Dialogue chat bot code with explanation 
[Chatbots aren't as difficult to make as You Think](https://mlwhiz.com/blog/2019/04/15/chatbot/)

### Chatbot Datasets for Machine Learning
- [15 Best Chatbot Datasets for Machine Learning](https://lionbridge.ai/datasets/15-best-chatbot-datasets-for-machine-learning)

- [Question-Answer Dataset](http://www.cs.cmu.edu/~ark/QA-data/)

### Open source Training data
- The WikiQA Corpus : a publicly available set of question and sentence pairs. It uses Bing query logs and links to Wikipedia pages.
- Yahoo Language Data : Curated question and answer datasets from Yahoo Answers
- Ubuntu Dialogue Corpus : Around 1 million two person conversations extracted from chat logs used to receive technical support
- Twitter Support : over 3 million tweets and replies from the biggest brands on Twitter
- CoNLL 2003 dataset : for training named entity recognition models

# Python Basic Task Libraries
## Python File Split Library
A python module that can split files of any size into multiple chunks, with optimum use of memory and without compromising on performance. 
The module determines the splits based on the new line character in the file, therefore not writing incomplete lines to the file splits.

### Usage
The module is available as a part of PyPI and can be easily installed using pip
`pip install filesplit`

Create an instance of the FileSplit object by passing file path and split size as arguments.
```python
from fsplit.filesplit import FileSplit
fs = FileSplit(file='path/to/file', splitsize=500000000, output_dir='/path/to/output directory/')
fs.split
```

# Python Flask Resources
##Reddit Job Search
Junter is a simple to use, free and open source web application to find job opportunities on Reddit.
Junter uses Reddit API through PRAW and Flask on the backend, standard Jinja 2 is used for rendering
[Reddit Job Search](https://github.com/anis-coding/Reddit-Job-Search)

# Python Urdu Libraries
Some noteable librariesL
- urduhack
- 

## UrduHack
Urduhack is a NLP library for urdu language. It comes with a lot of battery included features to help you process Urdu data in the easiest way possible.
- Normalization
- Tokenization
- Data pre-processing

## Urdu Datasets for NLP [Dataset by Irfan]
Collection of Urdu datasets for POS, NER and NLP tasks provided by [Irfan](https://mirfan899.github.io/Urdu/)

- POS Dataset
- NER Dataset
- UNER Dataset
- MK-PUCIT Dataset
- Sentiment Analysis Dataset
- Small Urdu Corpus

### Urdu Model for Spacy
Urdu model for SpaCy is available now. You can use it to build NLP apps easily. Install the package in your working environment.

`pip install ur_model-0.0.0.tar.gz`

### NLP Tutorials for Urdu
[NLP-Dataset](https://github.com/niderhoff/nlp-datasets)

