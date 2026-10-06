# MakeSumMore
A small character level model that generates new names, built using the guidance of Andrej Karpathy's 'makemore'.

This model used to use a Bigram model, but now uses an MLP, which improved generations and made the names more name-like.

## What it does
* Reads a dataset of names (names.txt)
* Learns which letters tend to follow which other letters (a bigram model) **Part 1**
* Learns context and patterns in the letters, to generate a more realistic name.
* Generates new, made-up names one letter at a time

## What I learnt
* How to turn text into numbers a model can work with (tokenizing characters)
* How a bigram language model predicts the next character
* How to train a model with a loss function and gradient descent in PyTorch
* The basic idea behind how bigger models like GPT generate text

### Credits:
Andrej Karpathy's 'makemore' model on github.
