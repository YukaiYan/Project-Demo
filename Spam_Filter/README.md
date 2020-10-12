# CSE 312 Couse project:
A classifier that marks emails as either spam or ham (= nonspam)

Implemented with Java

### Highlights
1. Used training set that already labeled "spam" or "ham" to train the model
2. Used Bayes' theorem, Chain Rule, and the Law of total probability to calculate the likelihood of an email being spam.
3. Includes Laplace smoothing in case we encounter a word that has never appeared in the training set.
4. Called naive Bayes since we assumed that the words in the email are conditionally independent of each other.