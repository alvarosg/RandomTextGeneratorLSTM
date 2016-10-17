# RandomTextGeneratorLSTM
A random text generator using a recursive neural network implemented in tensorflow.

This work was inspired by [this entry](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) in Andrej Karpathy blog, where a similar result is achieved using Torch instead of tensorflow. 

There is an official [tensorflow tutorial](https://www.tensorflow.org/versions/r0.11/tutorials/recurrent/index.html) on language modelling using RNNs with LSTMs, however there are a couple of key differences between the two:
* In this case the generation is performed character by character, instead of word by word, so the model first needs to learn how to build words, and then how to build sentences.
* The code is provided as a jupyter notebook, written in a very sequential way, instead of a standalone python program. While this is not optimal from an engineering point of view, it makes reading through the code much easier.

Copyright © 2016 - Alvaro Sanchez Gonzalez


