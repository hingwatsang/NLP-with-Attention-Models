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



## Assignment 2: Transformer Summarizer
The second assignment of course 4. In this assignment I explored summarization using the transformer model. I implemented the transformer decoder from scratch.<br>
Summarization is an important task in natural language processing and could be useful for a consumer enterprise. For example, bots can be used to scrape articles, summarize them, and then you can use sentiment analysis to identify the sentiment about certain stocks. Anyways who wants to read an article or a long email today, when you can build a transformer to summarize text for you. By completing this assignment I learnt to:

<li>Use built-in functions to preprocess your data</li>
<li>Implement DotProductAttention</li>
<li>Implement Causal Attention</li>
<li>Understand how attention works</li>
<li>Build the transformer model</li>
<li>Evaluate your model</li>
<li>Summarize an article</li>



## Assignment 3: Question Answering
The third assignment of course 4. In this assignment I explored question answering. I implemented the "Text to Text Transfer from Transformers" (better known as T5). Since I implemented transformers from scratch last week I was able to use them.

Due to memory and time constraints of this environment I was not able to train a model and use it for inference. Instead I created the necessary building blocks for the transformer encoder model and used a pretrained version of the same model in two ungraded labs after this assignment.

After completing these 3 (1 graded and 2 ungraded) labs I:

<li>Implement the code neccesary for Bidirectional Encoder Representation from Transformer (BERT).</li>
<li>Understand how the C4 dataset is structured.</li>
<li>Use a pretrained model for inference.</li>
<li>Understand how the "Text to Text Transfer from Transformers" or T5 model works.</li>




## Assignment 4: Chatbot
The fourth assignment of Course 4. In this assignment, I used the Reformer, also known as the efficient Transformer, to generate a dialogue between two bots. I feed conversations to my model and it learnt how to understand the context of each one. Not only will it learn how to answer questions but it will also know how to ask questions if it needs more info. For example, after a customer asks for a train ticket, the chatbot can ask what time the said customer wants to leave. I can use this concept to automate call centers, hotel receptions, personal trainers, or any type of customer service. By completing this assignment, I :

<li>Understand how the Reformer works</li>
<li>Explore the MultiWoz dataset</li>
<li>Process the data to feed it into the model</li>
<li>Train your model</li>
<li>Generate a dialogue by feeding a question to the model</li>
