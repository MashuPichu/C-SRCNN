# C-SRCNN
Context Aware Medical Image Super-Resolution Using Convolutional Neural Networks

Matthew Dong and Pratham Soni
# Overview
An overview can be found in the [abstract](Abstract.pdf).

# Technical Details
Technical details can be found in the [paper](Paper.pdf).

# Data
A selection of data can be found in the [data book](Data_Book.pdf)

# Implementation
Take care to set the correct hyperparameters and training/testing/tensorboard directories in [main.py](main.py)

Training: Use command `python main.py`.

Testing: Use command `python main.py --is_train false`.

Missing checkpoint directories will be automatically created with appropriate sub folders based on hyper parameters.
