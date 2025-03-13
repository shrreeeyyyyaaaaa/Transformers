# Transformers
This is the Transformer model architecture,which is widely used for natural language processing (NLP)tasks like machine trenslation and text generation (e.g,GPT,BERT)


let's break it down 

**Tokenization & Embedding:**

Input text is broken into tokens (Smaller chunks).

Each token is mapped to a vector in highdimensional space,where words with in similar meanings cluster together.

**The Attention Mechanism (Self-Attention):**

Words influnce each other based on context ensuring "bank"in riverbank isn't confused with financial bank.

The Attention Block weighs relationships between words, refining their represntaions dynamically.

**Feed-Forward Laayers (Deep Neural Network Processing)**

After attention, tokens pass through multiple feed-forwards layers that refine meaning.

Each layer learns deeper semantic relationships,improving predictions.

**Iteration & Deep Learning**

This process repeats through dozens or even hundreds of layers,adjusting token meanings iteratively.

This is where the "deep"in deep learning comes in layers upon layers of matrix multiplications and optimizations. 

**Prediction & Sampling**

The final vector representation is used to predict the next word as a probability distribution,
The model samples frome this distribution,generationg text word by word.


These mechanics are at the core of all LLMs (e.g.chatGPT)It is crucial to have a solid understanding how these mechanics work if you want to bulid scalable,responsible
**AI solutions**.


#**WHY WE USE SOFTMAX**






