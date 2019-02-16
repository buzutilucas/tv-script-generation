# Project: TV Script Generation
Udacity Deep Learning Nanodegree program 2019. In this project, I develop an algorithm for television script generation.

## Project Overview
In this project, I built a recurrent neural network (RNN) that can generate new [Simpsons](https://en.wikipedia.org/wiki/The_Simpsons) TV scripts. The Neural Network I built will generate a new "fake" TV script.

The project there are five steps:
- _Step 1:_ Implement Preprocessing Functions
  - Lookup Table
  - Tokenize Punctuation
- _Step 2:_ Build the Neural Network
  - Input Function
  - Functions to Build RNN Cell and Initialize
  - Word Embedding Function
  - Function to Build RNN
  - Function to Build the Neural Network
  - Batches Function
- _Step 3:_ Neural Network Training
- _Step 4:_ Implement Generate Functions
  - Function to Get Tensors
  - Function to Choose Word
- _Step 5:_ Generate TV Script

The code is written in Python 3 and [Tensorflow](https://www.tensorflow.org/) all presented in Jupyter Notebook.

### Prerequisites
Thinks you have to install or installed on your working machine:

- Python 3
- Numpy
- Jupyter Notebook
- Tensorflow

## Jupyter Notebook
- `dlnd_tv_script_generation.ipynb`

This jupyter notebook describes the whole project from Udacity, from the beginning to the end.

## Datasets
To train the model, we used part of the [Simpsons dataset](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data) of scripts from 27 seasons. In order to get good results, you'll have to use a smaller vocabulary or get more data. Luckily there's more data! As we mentioned in the beginning of this project, this is a subset of [another dataset](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data).

## Running the project
The whole project is located in the file `dlnd_tv_script_generation.ipynb` and it includes the training and the script generation part.
To open the project [click here](https://github.com/buzutilucas/tv-script-generation/blob/master/dlnd_tv_script_generation.ipynb)
