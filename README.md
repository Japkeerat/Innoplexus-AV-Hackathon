# Innoplexus-AV-Hackathon


| File | Description | Score |
| ---- | ----------- | ----- |
| [Baseline-First-Submission](https://github.com/Japkeerat/Innoplexus-AV-Hackathon/blob/master/Baseline-First-Submission.ipynb) | Simple baseline with all target values filled as 2 to get started on the leaderboard. | 0.2554089710 |
| [Baseline-Naive-Bayes](https://github.com/Japkeerat/Innoplexus-AV-Hackathon/blob/master/baseline-naive-bayes.ipynb) | Simple baseline with Gaussian Naive Bayes with no preprocessing done. Used CountVectorizer for building sparse matrix. | 0.3397809218 |
| [BernoulliNB](https://github.com/Japkeerat/Innoplexus-AV-Hackathon/blob/master/BernoulliNB-with-preprocessing.ipynb) | Applied standard preprocessing steps followed by using Bernoullli Naive Bayes algorithm. Though it did good on validation, I knew it would perform poorly than the Baseline Naive Bayes one because Baseline First Submission had a validation score of 0.72 and this file had 0.69 which gave me an expression that most of the predictions are same. | 0.294898328428889 |


Evaluation metric: Macro F1 Score

Public Test Set Size: 40%
