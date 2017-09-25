# Sberbank Question Answering Dataset

[Sberbank Question Answering Dataset](https://contest.sdsj.ru/?locale=en) : In this task participants have to build an algorithm that outputs an answer to a given question based on text paragraph. This is a challenging problem as it requires one to incorporate text comprehension capabilities into the algorithm to give correct and sufficient answers. This task is largely inspired by the fammous SQuAD challenge, but completely in Russian language.
To make the problem more feasible, the task of participants is to build an algorithm that finds an exact substring of a paragraph which serves as an answer. The dataset is designed to have each answer of each question an exact paragraph substring.

Number of questions – 50364
Number of articles – 9080

**Context length distribution**
Percentile 0     : 279
Percentile 20   : 559
Percentile 40   : 635
Percentile 60   : 740
Percentile 80   : 913
Percentile 100 : 7231

**Questions length distribution**
Percentile 0     : 8
Percentile 20   : 41
Percentile 40   : 52
Percentile 60   : 64
Percentile 80   : 83
Percentile 100 : 670

Question format is "question" (`'Где встречаются первые упоминания о строении человеческого тела?'`).

Answer format is "answer" (`'в Древнем Египте'`).

Metrics is **(Macro-averaged) F1 score** (This metric measures the average overlap between the prediction and ground truth answer. We treat the prediction and ground truth as bags of tokens, and compute their F1. We take the maximum F1 over all of the ground truth answers for a given question, and then average over all of the questions.)



