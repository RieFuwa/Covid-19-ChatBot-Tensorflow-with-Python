# Covid-19-ChatBot-Tensorflow-with-Python
import nltk
from nltk.stem.lancaster import LancasterStemmer
stemmer = LancasterStemmer()
import numpy
import tflearn
import tensorflow
import random
import json
import pickle
from tensorflow.python.framework import ops
ops.reset_default_graph()

If you want to open the project, you have to install all the necessary stuffs. My project has already been trained.
If you are going to retrain the project, you need to delete the data.pickle file.
