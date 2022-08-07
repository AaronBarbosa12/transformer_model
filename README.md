# transformer_model
An implementation of a transformer neural network for language translation.


Transformers are machine learning models that have proven to be incredibly powerful for natural language processing (NLP) applications. Standard NLP tools such as LSTM or GRU networks suffer from vanishing gradients, therefore, performance tends to suffer when processing long sequences. Transformers, however, use a special attention mechanism to bypass this vanishing gradient problem.

In this project we create a portuguese-to-english translator in Tensorflow. We do this by training and building a transformer model from first principles.

NOTE:

The model in this example is not optimized for performance. This project is for the purposes of learning about transformers in general.
This project was inspired by the following Tensorflow tutorial: https://www.tensorflow.org/text/tutorials/transformer
I'm using the same portuguese to english dataset as in the tutorial featured above ^. While implementing the transformer itself, however, I've avoided looking at any outside resources (aside from the original research paper "Attention Is All You Need": https://arxiv.org/abs/1706.03762).
