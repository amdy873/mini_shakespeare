# GPT Model for generating text in the style of shakespeare
This model implements the basic transformer decoder architecture. It does not include an encoder to take in input.
While this will generate text it is mostly non-sensical due to lack of gpu power and larger trainging sets.

Basic bigram implementation is found in bigram.py
v2.py creates a transformer model to improve the bigram model

Adapted from:
https://www.youtube.com/watch?v=kCc8FmEb1nY
