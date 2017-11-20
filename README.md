# Frequency of words in the Alien franchise

## Project Description

This is a basic Natural Language Processing project using Python &amp; Nltk.

The goal is to plot frequency distributions of words in the *Alien* franchise using the movies subtitles from [Springfield! Springfield!](https://www.springfieldspringfield.co.uk/).

For that, we will dive in to analyzing the movies subtitles using the Natural Language ToolKit (`nltk`).
In the process we will learn about important aspects of Natural Language Processing (NLP) such as tokenization and stopwords.
We will come out being able to visualize word frequency distributions of any subtitles that we can find on [Springfield! Springfield!](https://www.springfieldspringfield.co.uk/).

## Prerequisites

It would help if you knew

* the basics of Python
* a bit about Jupyter Notebooks
* a bit about Natural Language Processing
* using the terminal/shell

## Getting set up

You can set up this project locally or using [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/vdbcyril/alien-franchise-nlp/master?filepath=alien-franchise-nlp.ipynb)

### Getting set up locally

#### 1. Clone the repository

You can do so by executing the following command in your terminal:

```
git clone https://github.com/vdbcyril/alien-franchise-nlp.git
```

Alternatively, you can download the zip file of the repository at the top of the main page of the repository.

#### 2. Download Anaconda (if needed)

If you do not already have the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3, go download it.

#### 3. Create your conda environment

Navigate to the directory `alien-franchise-nlp` and install the required packages in a new conda environment:

```
conda env create -f environment.yml
```
This will create a new environment called alien-franchise-nlp. To activate the environment, execute:

```
source activate alien-franchise-nlp
```

#### 4. Open the Jupyter Notebook

In the terminal, execute `jupyter notebook`.

Next, open the notebook `alien-franchise-nlp.ipynb` and you are ready to read about the project.

## Any issues or thoughts ?

If you encounter any issues, use the [Issues page](https://github.com/vdbcyril/alien-franchise-nlp/issues). You can send your thoughts to cyril.vandenberghe.pro@gmail.com
