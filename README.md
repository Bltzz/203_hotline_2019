# 203_hotline_2019

Maths Project from Epitech

Description:

Uncle Luigi runs a 25-phone hotline in Pondicherry. He reckons 3500 people could possibly call during
each 8-hour day, and would like to know the probability of an overload (that is, the probability of no line
being available), depending on the average duration of calls.

The random variable representing the number of people calling at a given time follows the binomial dis-
tribution, with calls being independent from each other. You’re also thinking about estimating the binomial
ditribution with a Poisson distribution, so it can be used on a larger scale.

Your first task is to compute the binomial coefficient <math>\tbinom nk</math> given k and n (emphasizing the computation speed and stack optimization).

Your second task is to compare the binomial and Poisson distributions, given the average duration of calls,
by printing:

• the probabilities of getting n simultaneous calls (for n increasing from 0 to 50),

• the probability of an overload,

• the computation time.
