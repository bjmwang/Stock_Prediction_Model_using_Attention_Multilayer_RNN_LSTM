# RNN - Stock Prediction Model using Attention-LSTM

Author: [Soumyendu Sarkar](https://www.linkedin.com/in/soumyendusarkar/)

## Data Preparation

* Data Source research and identification (free part of QuantQuote database )
* Importing decade long stock data of the S&P 500 companies
* Cleaning and Normalizing data with zero mean, unit variance and logarithmic scaling for normal distribution
* Processing and Separating data into Input Data (the intra-day price fluctuations) and Expected Output Data (discrete categorized classification values for price gain over consecutive days )
* Forming Data Frames for Training and Testing for Neural Network

## Code for Two Distinct Neural Networks for Comparison

* Code for Fully Connected Feed Forward Neural Network classifier using low level Tensorflow Framework API
* Code for Attention Adaptation of Multilayer (2x) Recurrent Neural Networks (100x NN lookback) with LSTM / GRU Memory Optimized Cells using low level Tensorflow Framework API. This follows latest publication and enhancement in Recurrent Neural Networks.
* Accelerated Linear Algebra optimization for faster code execution with XLA JIT (Just in time compilation) directives
* Both these codes uses low level Tensorflow API to facilitate usage of advanced Tensorflow framework features with embedding and model structure refinements

## Model Visualization and Tensorboard Embeddings

* Tensorboard code embedding for Graphical Model Visualization and Data visualization 

## Analysis and Result Visualization

* Diagnostics and Evaluation with Graphical presentation of the effectiveness of the Model
* Confusion Matrix and Accuracy, Precision, Sensitivity and Specificity
* The Graph demonstrates the effectiveness of both the Neural Networks in making daily trading decisions, scored against random buys and sells
* Several measures of effectiveness in decision making
