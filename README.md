# Single-Multilingual-Hate-Speech-Detection-Model
This model was create as a part of SemEval-2019 Task 5 competition.

The task was partition into two group: Task A and Task B. Making total of four subtask(English/Spanish task A/B).

TASK A - Hate Speech Detection against Immigrants and Women: a two-class (or binary) classification where systems have to
predict whether a tweet in English or in Spanish with a given target (women or immigrants) is hateful or not hateful.

TASK B - Aggressive behavior and Target Classification: where systems are asked first to classify hateful tweets for English
and Spanish (e.g., tweets where Hate Speech against women or immigrants has been identified) as aggressive or not aggressive,
and second to identify the target harassed as individual or generic (i.e. single human or group).

A binary value (1/0) indicating if HS is occurring against one of the given targets (women or immigrants).
If HS occurs (i.e. the value for the feature at point HS is 1), a binary value indicating if the target is a generic group of 
people (0) or a specific individual (1) denoted as TR. And if HS occurs (i.e. the value for the feature at point HS is 1),
a binary value indicating if the tweeter is aggressive (1) or not (0) denoted as AG. Thus, making 3 coloum
(named HS, TR and, AG) for each tweets.

The Data Set could be downloaded from here: https://competitions.codalab.org/competitions/19935
