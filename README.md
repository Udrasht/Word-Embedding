# Word Embedding Models for Classification Task

This repository contains implementations of two word embedding models: Skip-gram and Co-occurrence Matrix based model (SVD). These models are trained on a subset of a news dataset.

## Files
- **code**: This directory contains the following .py files:
  - `SVD.py`: Contains the implementation of the SVD model. By default, it runs on a pretrained model. The file predicts words stored in a list, which can be modified to predict more words.
  - `skip-gram.py`: Contains the implementation of the Skip-gram model. Similar to SVD, it runs on a pretrained model by default.
  - `svd-classification.py`: Trains an RNN (LSTM) on the classification task using the SVD word vectors. By default, it runs on a pretrained model.
  - `skip-gram-classification.py`: Trains an RNN (LSTM) on the classification task using the Skip-gram word vectors. By default, it runs on a pretrained model.
- **2022201020_Assignment_3**: This directory contains hyperparameters used to train the model(s), corresponding graphs and evaluation metrics, and analysis of the results.
- **models**: This directory contains trained models (`svd-word-vectors.pt`, `skip-gram-word-vectors.pt`, `svd-classification-model.pt`, `skip-gram-classification-model.pt`).
- **data**: This directory contains training and test data .csv files and also contains embedding files.

## Execution

To execute the models, follow these steps:

1. Open a terminal.
2. Run the following commands:
    ```bash
    $ python SVD.py
    $ python skip-gram.py
    $ python svd-classification.py
    $ python skip-gram-classification.py
    ```

## Note

Ensure that the provided directory structure is maintained for the code to work properly.

## Assumptions
- Only 30,000 sentences are used for creating the embeddings.
- RNN (LSTM) is used for classification.

For the complete dataset and other supplementary files, refer to the [Google Drive link](https://drive.google.com/drive/folders/1nXl6xrnW4Nl7owjGAGpKcf7xCVztqfu8?usp=sharing) provided.

**Please download the "data" and "models" folders from the following link before running the .py files because I have hard-coded the file and models paths in the .py files.**

---> https://drive.google.com/drive/folders/1nXl6xrnW4Nl7owjGAGpKcf7xCVztqfu8?usp=sharing

**Submitted by:** 2022201020
