# Stanford Question Answering Dataset (SQuAD)

[Stanford Question Answering Dataset (SQuAD)](https://rajpurkar.github.io/SQuAD-explorer/) is a new reading comprehension dataset, consisting of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to every question is a segment of text, or span, from the corresponding reading passage. With 100,000+ question-answer pairs on 500+ articles, SQuAD is significantly larger than previous reading comprehension datasets.

Number of articles – 442
Mean number of articles splits – 42

**Context length distribution**
Percentile 0     : 185
Percentile 20   : 531
Percentile 40   : 620
Percentile 60   : 706
Percentile 80   : 829
Percentile 100 : 2111

**Number of questions**
Percentile 0     : 1
Percentile 20   : 4
Percentile 40   : 5
Percentile 60   : 5
Percentile 80   : 7
Percentile 100 : 25

Question format is "question" (`'What country is Kathmandu the capital of?'`).

Answer format is "answer start" and "text" (`{'answer_start': 105, 'text': 'Nepal'}`).

Metrics is **Exact Match Score**  (This metric measures the percentage of predictions that match any one of the ground truth answers exactly) and **(Macro-averaged) F1 score** (This metric measures the average overlap between the prediction and ground truth answer. We treat the prediction and ground truth as bags of tokens, and compute their F1. We take the maximum F1 over all of the ground truth answers for a given question, and then average over all of the questions.)



