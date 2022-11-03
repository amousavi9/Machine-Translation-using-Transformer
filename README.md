# [Transformer model for end-to-end Machine Translation](https://github.com/amousavi9/Machine-Translation-using-Transformer)
The Transformer model architecture was introduced by Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Lukasz Kaiser and Illia Polosukhin in their paper [Attention Is All You Need](https://arxiv.org/abs/1706.03762).    
The Transformer model extracts the features for each word using a self-attention mechanism to know the importance of each word in the sentence. No other recurrent units are used to extract this feature, they are just activations and weighted sums, so they can be very efficient and parallelizable.   
In this study, I implement machine translation in Persian language with the help of transformer network by anki dataset.

## Basic Architecture
In the Transformer Architecture, there is an encoder model on the left side and the decoder on the right. Both encoder and decoder contain a core block of attention and a feed-forward network repeated N number of times.
Attention allowed us to focus on parts of our input sequence while we predicted our output sequence. self attention helps us create similar connections but within the same sentence. Multi-head Attention is a module for attention mechanisms which runs through an attention mechanism several times in parallel.   
<p align="center">
  <img src="https://github.com/amousavi9/Machine-Translation-using-Transformer/blob/main/figures/transformer-architecture.JPG" width="750" height="400" />
</p>


## Evaluation

<p align="center" width="100%">
    <img width="43%" src="https://github.com/amousavi9/Machine-Translation-using-Transformer/blob/main/figures/accuracy.JPG">
    <img width="40%" src="https://github.com/amousavi9/Machine-Translation-using-Transformer/blob/main/figures/loss.JPG">
</p>
