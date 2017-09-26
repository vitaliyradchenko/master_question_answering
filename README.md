# master_question_answering
UCU master work (question answering)

[Leaderbord](https://rajpurkar.github.io/SQuAD-explorer/)

## Road Map

1. Sliding window baseline (For each candidate answer, we compute the uni- gram/bigram overlap between the sentence contain- ing it (excluding the candidate itself) and the ques- tion. We keep all the candidates that have the max- imal overlap. Among these, we select the best one using the sliding-window approach proposed in Richardson et al. (2013))
2. Logistic Regression (features)
3. [Bi-directional Attention Flow for Machine Comprehension](https://github.com/allenai/bi-att-flow)
