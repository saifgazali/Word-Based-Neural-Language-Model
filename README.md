# Word-Based-Neural-Language-Model

Generating Text by training the model on the Jack and Jill Poem text.


The training of the network involves providing sequences of words as input that are processed one at a time where a prediction
can be made and learned for each input sequence. Similarly, when making predictions, the
process can be seeded with one or a few words, then predicted words can be gathered and
presented as input on subsequent predictions in order to build up a generated output sequence
Therefore, each model will involve splitting the source text into input and output sequences,
such that the model can learn to predict words. There are many ways to frame the sequences
from a source text for language modeling


Model 1: One-Word-In, One-Word-Out Sequences

Model 2: Line-by-Line Sequence

Model 3: Two-Words-In, One-Word-Out Sequence

