# Recurrent-Neural-Networks
Speech De-Noising on TIMIT datasets using LSTM

Notebook Speech_Denoising_RNN.ipynb contains code which is used to train a Recurrent Neural Network (LSTM) using tensorflow to remove
noise from an audio signal. We use the TIMIT dataset which consists of train and test audio signals. We also have a bunch of noise signals.
The noise signals are mixed with training data to clean noise signals. The LSTM network is trained by giving the noisy signal as input and
corresponding clean signal as output. We use the test data to measure how well the model performs. We use Signal-to-noise ratio to measure
the performance of the neural network.

A sample clean test signal is present in the repo as 'test_s_01_recons.wav'
