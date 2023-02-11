# NLP_classifiers
Contains algorithms to train machine learning models using a variety of classifier strategies.

These steps can be followed as a reference:

1. The data to train your model can be found in data\sentiment_competition_train.csv
2. Pre-process dataset
3. Split dataset into a training and validation set
4. Vectorize data
5. Train model using classification algorithm
6. Validate trained model using validation dataset
7. Improve model/pre-processing/vectorizer etc.
8. Evaluate with the test set and hope for the best!


## Getting started
Before we can make a new Python project, we need to make sure that you have a 
(recent) Python version installed on your device. Python 3.8+ is required. If 
you have a recent version of Python installed, a version of the tool `pip` is
automatically installed.

#### Check Python version
`python --version`

**Note**: When the command is not found or the version is 2.x, try `python3 --version` and use `python3` instead of `python` in the commands below.

#### Project setup
When the right python version is installed, we can open our project and install
all the required packages for this project.
- Create a virtual environment:

    `python -m venv venv`
- Activate the virtual environment:

    - See [this link](https://docs.python.org/3/library/venv.html) how to activate the `venv` for your operating system.
    
- Update `pip` to get its latest version:
    
    `python -m pip install -U pip`

- Install wheel:
    
    `python -m pip install wheel` 


- Install required packages:
    
    `python -m pip install -r requirements.txt` 

## Dataset

The sentiment_competition_train.csv is a subset of the IMBD sentiment review dataset.

See link: https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews