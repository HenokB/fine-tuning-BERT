<p align="center">
<h1> A transformers network with a pre-trained BERT model</h1>
<p align="center">
   <a href="#contributors"><img src="https://img.shields.io/github/contributors/HenokB/fine-tuning-BERT.svg?color=c0c8d0"></a>
   <a href="https://github.com/HenokB/fine-tuning-BERT/stargazers"><img src="https://img.shields.io/github/stars/HenokB/fine-tuning-BERT?color=e4b442" alt="Github Stars"></a>
   <a href="https://github.com/HenokB/fine-tuning-BERT/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-9d2235" alt="License"></a>
   <a href="https://github.com/HenokB/fine-tuning-BERT/commits/main"><img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/HenokB/fine-tuning-BERT?color=8b55e3"/></a> 
</p> </br>
</p>
Fine-Tuning BERT: A Transformers Network with a Pre-trained BERT Model
This project involves fine-tuning a pre-trained BERT model for a sentiment analysis task. The model is trained and validated using a dataset containing text entries labeled with their respective sentiment.
<p align="center">
<h1> What is BERT?</h1>

<img scr="https://static.wixstatic.com/media/3eee0b_2fe2b87045f14615808783b3f17f2662~mv2.png/v1/fill/w_935,h_483,al_c,lg_1,q_90,enc_auto/3eee0b_2fe2b87045f14615808783b3f17f2662~mv2.png">
</p>
BERT (Bidirectional Encoder Representations from Transformers) is a revolutionary model in the field of Natural Language Processing (NLP), developed by researchers at Google. BERT set new records in a wide array of NLP tasks when it was first introduced. It is designed to pre-train deep bidirectional representations from the unlabeled text by jointly conditioning on both left and right context in all layers.

## Key Characteristics
- Bidirectional Context: Unlike previous models, BERT takes into account the context from both the left and the right of a word in a sentence during training, enabling it to have a deeper understanding of the meaning of each word.

- Pre-training and Fine-Tuning: BERT adopts a two-step process: pre-training and fine-tuning. During pre-training, the model is trained on a large corpus of text to understand language semantics. During fine-tuning, BERT is adapted to specific NLP tasks with task-specific datasets, such as question answering and sentiment analysis.

- Transformer Architecture: BERT is built upon the Transformer architecture, which uses attention mechanisms to focus on different words in the input sentence, allowing it to process words in parallel and capture the relationships among words and sub-words.

## Architecture Details
Embedding Layers: BERT uses WordPiece embeddings with a 30,000 token vocabulary. The input representation for BERT is created by summing the corresponding word, segment, and position embeddings.

- Transformer Blocks: BERT’s architecture is composed of a stack of identical Transformer blocks. Each block consists of two main layers: a multi-head self-attention mechanism and a position-wise fully connected feed-forward network.

- Attention Mechanism: The attention mechanism allows the model to focus on different words for a given input. Multi-head attention uses multiple attention layers (or “heads”) to capture different types of relationships among words.

- Positional Encoding: BERT uses positional encodings to maintain the order of the words.

# Conclusion

BERT has significantly impacted the NLP community by providing a robust and versatile model that understands the intricacies of language semantics and context. Its pre-training and fine-tuning strategy, along with its powerful Transformer architecture, enable it to excel in numerous NLP tasks, often outperforming task-specific models. Consequently, BERT has become a foundational model for developing more advanced NLP applications and continues to inspire the creation of more sophisticated models in the field.

# Resources 

- [The Illustrated BERT, ELMo, and co. (How NLP Cracked Transfer Learning)](http://jalammar.github.io/illustrated-bert/)
- [Google BERT: Understanding the Architecture](https://www.theaidream.com/post/google-bert-understanding-the-architecture)
- [Dataset used](https://ai.stanford.edu/~amaas/data/sentiment/)


