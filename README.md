# Neural Grammar Dependency Parser

In this notebook, a neural transition-based dependency parser is implemented, based off the paper [A Fast and Accurate Dependency Parser using Neural Networks](https://nlp.stanford.edu/pubs/emnlp2014-depparser.pdf).

The setup for a dependency parser is somewhat more sophisticated than tasks like classification or translation.

---

Here's an example of predicting and evaluating the dependency tree of the sentence: _"Ray's pizza is just too good."_

Actual dependency tree:

[]()

Predicted dependency tree:

[]()

Evaluated dependency tree:

[]()

Unlabeled Attachment Score for this sentence: 100.0<br>
Labeled Attachment Score for this sentence: 100.0 

---

Overall model accuracy performance:

Test Set Unlabeled Attachment Score: 83.55% (i.e., correctly predicted head of sentence)<br>
Test Set Labeled Attachment Score: 80.98% (i.e., correctly predicted head and label of head of sentence)