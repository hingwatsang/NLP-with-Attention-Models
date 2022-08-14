# NLP-with-Attention-Models

In Course 4 of the Natural Language Processing Specialization, I :

a) Translate complete English sentences into German using an encoder-decoder attention model, <br>
b) Build a Transformer model to summarize text, <br>
c) Use T5 and BERT models to perform question-answering, and<br>
d) Build a chatbot using a Reformer model. <br>


## Assignment 1: Neural Machine Translation
The first assignment of Course 4. Here, I built an English-to-German neural machine translation (NMT) model using Long Short-Term Memory (LSTM) networks with attention. Machine translation is an important task in natural language processing and could be useful not only for translating one language to another but also for word sense disambiguation (e.g. determining whether the word "bank" refers to the financial bank, or the land alongside a river). Implementing this using just a Recurrent Neural Network (RNN) with LSTMs can work for short to medium length sentences but can result in vanishing gradients for very long sequences. To solve this, I added an attention mechanism to allow the decoder to access all relevant parts of the input sentence regardless of its length. By completing this assignment, I :

<li>learn how to preprocess your training and evaluation data</li>
<li>implement an encoder-decoder system with attention</li>
<li>understand how attention works</li>
<li>build the NMT model from scratch using Trax</li>
<li>generate translations using greedy and Minimum Bayes Risk (MBR) decoding</li>
