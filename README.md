# MCQ-Generator-and-Text-Similarity-Model

## Table of Contents

1. [Project Description](#desc)
2. [Install](#install)
3. [Code](#code)
4. [Run](#run)
5. [Data](#data)

<a name="desc"></a>
## Project Description

Teachers around the world spend vast amounts of time to select the text to be given for the comprehension/reading section of assignments and much more time to write down the questions that can be asked - be it Multiple Choice Questions (MCQs), short answer questions, or true or false questions. It’s a tedious and time-consuming job. The project aims to aid this traditional method of framing questions using Natural Language Process where the MCQ are auto-generated from any text content with the help of BERT summarizer/ custom summarizer techniques.

The model includes key word extraction process in order to map the most relevant sentences from the summary to frame the questions and the answer choices are created using the trivial process of keeping the right answer(key word) as one of the options and adding distractors to fill up the choices. The project also tackles the challenging problem of evaluating subjective answers by implementing different methods to assess the answers, starting from finding similarity as a geometric metric (Jaccard Similarity, Cosine similarity, etc) and ending with state of the art transformer based models. Not surprisingly, the results indicate transformer based models perform very well in this task.

<a name="install"></a>
## Install

This project requires Python and the following Python libraries installed:

* en-core-web-sm @ https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-3.2.0/en_core_web_sm-3.2.0-py3-none-any.whl
* flashtext
* Flask
* Flask-Compress
* gensim
* keras
* Keras-Preprocessing
* matplotlib
* matplotlib-inline
* nlp
* nltk
* numpy
* pandas
* parso
* pathspec
* pathy
* pickleshare
* Pillow
* pke-tool
* platformdirs
* plotly
* rarfile
* regex
* scikit-image
* scikit-learn
* scipy
* seaborn
* sentence-transformers
* sentencepiece
* sklearn
* spacy
* spacy-legacy
* spacy-loggers
* stemming
* symspellpy
* tensorboard
* tensorboard-data-server
* tensorboard-plugin-wit
* tensorflow
* tensorflow-hub
* tensorflow-io-gcs-filesystem
* testpath
* textblob
* tf-estimator-nightly
* tokenizers
* torch
* torchtext

You will also need to have software installed to run and execute a Jupyter Notebook.

If you do not have Python installed yet, it is highly recommended that you install the Anaconda distribution of Python, which already has the above packages and more included.
Otherwise, you could execute the code on Google Colaboratory.

<a name="code"></a>
## Code

The template code for Multiple Choice Question Generator is provided in the MCQGenerator.py notebook file. The template code for the subjective answer score generator is provided in the TextSimilarity.py  You will also be required to use the included app.py Python file and the ‘text’ folder which consists of text used to assess the model, in order to complete your work. The ‘requirement’ text file consists of all the dependencies you would need in order to run this project in your system.

<a name="code"></a>
## Run

In a terminal or command window, run one of the following commands:

$ ipython notebook MCQGenerator.ipynb

or

$ jupyter notebook MCQGenerator.ipynb

or open with Juoyter Lab

$ jupyter lab

This will open the Jupyter Notebook software and project file in your browser.

or else download and upload the file on Google Colaboratoty. 

<a name="data"></a>
## Data

The text used for the purpose of evaluating and testing the model is provided in the folder 'text'.

