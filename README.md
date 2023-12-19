What is Bernoulli and Binomial Distribution? Bernoulli Distribution is a probability
Distribution That model a binary outcomes it can be either success(1) or failure(0).
Experiment* for coin toss perspective: Head = 1, tail = 0 
for machine learning perspective: spam = 1, not spam = 0 
Bernoulli Distribution is used in machine learning for modelling binary outcomes,
whether a customer will make purchase or not. Note Benoulli have only one parameter "p" Formula P(X = x) = p^x(1-p)^1-x 
if the value of n = 1 then it is Bernoulli but the value of n = 5 or can say more than 1 
Then in that particular case it is Binomial and Binomial Distribution is also a mathematical model which is used in many Business situation 
and it often used when the discrete variable is the number of events of interest in a sample of n observation. Formula P((X = x ) = nCxP^x(1-P)^n-x 
it consist of two parameters (n, p)

Criteria:
The process consist of n Trials
only 2 exclusive outcomes are possible i.e a success and a failure.
p(success) = p and p(failure) = 1 - p and it is fixed trial to trial.
The trial are independent.

Use Case:
Hypothesis Testing
Ab Testing
Logistic Regression
Binary Classification Problems
