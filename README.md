# insta-keras

Keras demos and experiments using Instacart data.

I'mm learning Keras and TensorFlow, with a focus on recommendation-related problems, and created this repo to store my experiments along the way.

## Experiment 1

See the `experiment1` subdirectory.

This experiment uses data from the [Instacart Kaggle contest](https://www.kaggle.com/c/instacart-market-basket-analysis) about market basket analysis, but addresses a slightly different task from the contest.

The aim is: given a user's order, can we predict which items from that order will be present in the user's next order?

`experiment1` contains two IPython notebooks.

### 1-DataPrep.ipynb

This reads the CSV files supplied by Instacart via Kaggle, parses them, performs some feature extraction and writes out the data to HDF5 files.

Note that you need to download the CSVs yourself, as they're a bit too big to store in GitHub... See the instructions in the notebook.

### 2-ModelTraining.ipynb

This reads in the HDF5 files created by the previous notebook, and trains a Keras model. See the instructions and notes in the notebook for more detail.

## Experiment2 ... ExperimentN

Watch this space!
