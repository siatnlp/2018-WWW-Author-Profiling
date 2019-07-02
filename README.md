# 2018-WWW-Author-Profiling
Multi-task Learning for Author Profiling with Hierarchical Features

## Abstract
Author profiling is an important but challenging task. In this paper, we propose a novel Multi-Task learning framework for Author Profiling (MTAP), in which a document modeling module is shared across three different author profiling tasks (i.e., age, gender and job classification tasks). To further boost author profiling, we integrate hierarchical features learned by different models. Concretely, we employ CNN, LSTM and topic model to learn the character-level, word-level and topic-level features, respectively. MTAP thus leverages the benefits of supervised deep neural neural networks as well as an unsupervised probabilistic generative model to enhance the document representation learning. Experimental results on a real-life blog dataset show that MTAP has robust superiority over competitors and sets state-of-the-art for all the three author profiling tasks.
