# Personality-Classifier

This is a simple logistic‐regression classifier that takes your seven questionnaire inputs (hours spent alone, stage fear, event attendance, going out frequency, post frequency, friend‐circle size, and whether you feel drained after socializing), encodes any categorical answers into dummy variables, and then computes a weighted linear combination of those features passed through a logistic (sigmoid) function to output a probability of being an extrovert vs. an introvert.

Once trained on your labeled survey data, it achieves about 92 percent accuracy on held‐out examples, with both classes (introvert/extrovert) showing precision and recall in the low-90s. The confusion matrix confirms it rarely mislabels introverts as extroverts (and vice versa) more than a few percent of the time.
