# A Donald Trump-like Text Generator

In this second notebook on NLP, we use +30K Donald Trump speeches to create a simple text generator.

By 'simple', we mean that we use N-grams rather then today's most advanced tehniques such as NN transformers.
Nonetheless, it's a good intro to NLP.

### What is a N-gram?
An N-gram is a contiguous sequence of N items such as words or symbols in a text or speech. 
The value of N determines the length of the sequence. 
In NLP, they are particularly useful for capturing patterns and context in text data.
By analyzing the frequency and co-occurrence of N-grams in a large corpus of text, NLP models can better understand the structure of a language and make predictions or generate coherent text.

### A few limitations of N-grams
Some limitations impact their effectiveness in certain applications:

- Lack of Semantics: N-grams do not capture the meaning or semantics of language. They are purely based on the sequential order of words or characters. This means that N-grams may not differentiate between words with multiple meanings or consider the context in which words are used.

- Fixed-Length Context: N-grams rely on a fixed window of context (N) & may miss longer-range dependencies in language. For example, in a long sentence, a trigram or bigram might not capture the relationship between words at the beginning and end of the sentence.

- Data Sparsity: Many N-grams may occur infrequently or not at all in the training data, making it challenging to estimate their probabilities accurately.

- Limited Generalization: N-grams are not very good at generalizing from the training data to handle unseen or out-of-vocabulary words. They rely heavily on the training data's vocabulary, which can lead to problems when dealing with new words or rare words.

... 

In summary, while N-grams have their uses in NLP, they are not suitable for all tasks and have limitations when it comes to capturing meaning, handling data sparsity, and modeling complex linguistic relationships. 
More advanced techniques, such as neural networks and deep learning models, have been developed to address some of these limitations and perform better on various NLP tasks.

### In this notebok
What is covered in this note book:
- Data processing
- Calculating N-grams probabilities and perplexity
- Auto-completion model
- Sentence generation model

![image](https://github.com/marcomudenge/NLP-2-A-Donald-Trump-Text-Generator/assets/44266914/398a6ef2-9bd2-4d8c-8bed-15d1ce41c8db)

### Good read! PS: Might need some french to read through this notebook.
