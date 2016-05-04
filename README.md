# word2vec-acc-cuda
Acceleration of word2vec using GPU without losing accuracy.

It accelerates every training algorithm(hierarchical softmax, negative sampling) and architecture(skip-gram, CBOW) of word2vec.
This acceleration targets dataset of general sentences(~50 words per sentence), so can’t get speed up on dataset without new-line delimiter.

Requirements
----------
CUDA Toolkit & NVIDIA GPU supporting CUDA

Usage
----------
The script ‘demo-word.sh’ downloads pre-processed text dataset(1.7G) has almost 1 billion words.
The usage is almost same with google’s word2vec because it based on it. You can get more information about word2vec at https://code.google.com/p/word2vec/
