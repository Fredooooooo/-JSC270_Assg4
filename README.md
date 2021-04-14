# Evaluation Comments

## Q1

- Careful about using the max_features attribute in the CountVectorizer. This restricts your vocabulary. This is fine as a hyperparameter to tune, but the true vocabulary without constraint should be above 50,000. This will affect your accuracies later in the question, but you'll only lose a mark once.
- What are the top 5 most frequent words for each class in part G?
- Naïve Bayes is Generative, since we're not modelling P(Y|X) directly (we rely on P(Y,X) and Bayes Rule).


## Q2

- Why is predicting the number of followers a useful learning task? A bit more detail on the problem motivation is needed.
- There are other works that predict twitter followers (e.g. see Klotz, Ross, Clark and Martell 2019). In what way is your approach similar/ different?
- How exactly did you choose the 2000 tweets for your dataset? Or was the initial extraction exactly 2000 tweets?
- What does your dataset look like? Are there any interesting trends/ patterns? What are the summary statistics? You should do a bit more EDA, especially with a group of 3
- How did you choose the intervals for your small, medium, and large bins?
- Good point about NB working poorly for imbalanced classes
- Good point about the test accuracy reflecting majority class
- It's ok if the model does not work well (we still learn something)
- Your report should include some graphs and/or tables showing interesting patterns or results.
- Good job
