# LSTM ChatbotMethodology:
## Project Overview
In this project, I will build a chatbot that can converse with you at the command line. The chatbot will use a Sequence to Sequence text generation architecture with an LSTM as it's memory unit. I will also learn to use pretrained word embeddings to improve the performance of the model. At the conclusion of the project, I will be able to show this chatbot to potential employers.

A sequence to sequence model (Seq2Seq) has two components:

An Encoder consisting of an embedding layer and LSTM unit. A Decoder consisting of an embedding layer, LSTM unit, and linear output unit. The Seq2Seq model works by accepting an input into the Encoder, passing the hidden state from the Encoder to the Decoder, which the Decoder uses to output a series of token predictions.

