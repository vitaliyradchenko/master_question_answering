# master_question_answering
UCU master work (question answering)

[Leaderbord](https://rajpurkar.github.io/SQuAD-explorer/)

## Road Map

1. Sliding window baseline (For each candidate answer, we compute the uni- gram/bigram overlap between the sentence contain- ing it (excluding the candidate itself) and the ques- tion. We keep all the candidates that have the max- imal overlap. Among these, we select the best one using the sliding-window approach proposed in Richardson et al. (2013))
2. Logistic Regression ([features](https://github.com/vitaliyradchenko/master_question_answering/blob/master/plots/log_reg_features.png))
3. [Bi-directional Attention Flow for Machine Comprehension](https://github.com/allenai/bi-att-flow)


MEMEN: Multi-layer Embedding with Memory Networks for Machine Comprehension

Key words: Syntactic, semantic, char- & word- embeddings, bi-lstm, alignment matrix, hierarchical attention, pointer networks

Difference:
	1) the encoding of context and query, in which we add useful syntactic and semantic information in the embedding of every word
	2) the high-efficiency multilayer memory network of full-orientation matching to match the question and context
	3) the pointer-network based answer boundary prediction layer to get the location of the answer in the passage

ReasoNet: Learning to Stop Reading in Machine Comprehension

Key words: word- & char embeddings, bi-gru, similarity matrix, internal state controller, termination module, RL

Difference:
Our proposed approach explores the idea of using both attention- sum to aggregate candidate attention scores and multiple turns to attain a better reasoning capability. Unlike previous approaches using a xed number of hops or iterations, motivated by [15, 16], we propose a termination module in the inference. The termination module can decide whether to continue to infer the next turn after digesting intermediate information, or to terminate the whole inference process when it concludes existing information is suficient to yield an answer. The number of turns in the inference is dynamically modeled by both a document and a query, and is generally related to the complexity of the document and the query. 

	
Structural Embedding of Syntactic Trees for Machine Comprehension 

Key words: word- & char- based embeddings, Structural Embedding of Syntactic Trees, bi-LSTM, Bi-directional Attention flow model (Query2Context and Context2Query) 

Difference: Structural Embedding of Syntactic Trees (Stanford CoreNLP)

BI-DIRECTIONAL ATTENTION FLOW FOR MACHINE COMPREHENSION

Key words: contextual, word- & char- embeddings, bi-directional attention (Query2Context and Context2Query) 

Difference: Contextual Embedding Layer, bi-directional attention (Query2Context and Context2Query)

Exploring Question Understanding and Adaptation in Neural-Network-Based Question Answering

Baseline model: word embedding, input encoder, alignment, aggregation, and prediction

Key words: word- & char- embeddings, TreeLSTM, Stanford CoreNLP

Difference: Explicit question-type embedding, TreeLSTM, adaptation mechanism 

Multi-Perspective Context Matching for Machine Comprehension

Key words: word- & char- embeddings, biLSTM

Difference: filter layer
