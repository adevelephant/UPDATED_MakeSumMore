# MakeSumMore
A small character level model that generates new names, built using the guidance of Andrej Karpathy's 'makemore'.

This model uses a Bigram language model, but will be improved.

## What it does
* Reads a dataset of names (names.txt)
* Learns which letters tend to follow which other letters (a bigram model)
* Generates new, made-up names one letter at a time

## What I learnt
* How to turn text into numbers a model can work with (tokenizing characters)
* How a bigram language model predicts the next character
* How to train a model with a loss function and gradient descent in PyTorch
* The basic idea behind how bigger models like GPT generate text

### Credits:
Andrej Karpathy's 'makemore' model on github.
