# Homework 03: Probability

Answer each question using the notation from lecture. When possible, give exact fractions as well as decimals.

## Part I: Probability Spaces, Events, and Random Variables

### Problem 1: One Coin Flip

A fair coin is flipped once.

1. Write the sample space $\mathcal{S}$.
2. Give two nontrivial events in $\mathcal{E}$.
3. State the probability of each outcome.

### Problem 2: Events on One Die

A fair six-sided die is rolled once. Let

$$
A=\{2,4,6\},
\qquad
B=\{1,2,3,4\}.
$$

Compute:

$$
p(A),\qquad p(B),\qquad p(A\cap B),\qquad p(A\cup B),\qquad p(B^c).
$$

### Problem 3: Conditional Probability

A fair six-sided die is rolled once. Let

$$
A=\{\text{the roll is even}\},
\qquad
B=\{\text{the roll is greater than }3\}.
$$

Compute $p(A\mid B)$.

### Problem 4: From Outcomes to a PMF

A random variable $X$ is defined on a fair die roll by

$$
X(s)=
\begin{cases}
1, & s \in \{1,2,3\}\\
4, & s \in \{4,5\}\\
10, & s=6.
\end{cases}
$$

Write the probability mass function of $X$.

### Problem 5: Expected Value from a PMF

Let the random variable $X$ have PMF

$$
p[X=0]=0.2,\qquad p[X=1]=0.5,\qquad p[X=4]=0.3.
$$

Compute $\mathbb{E}[X]$.

### Problem 6: Linearity of Expectation

Use the same random variable $X$ from Problem 5. Compute $\mathbb{E}[2+3X]$ in two ways:

1. Directly, by writing down the transformed values of $2+3X$ and their probabilities.
2. Using linearity of expectation.

## Part II: Conditioning, Bayes' Rule, and Expected Payoffs

### Problem 7: Coffee and Majors

A class has 12 students. Of these, 7 are math majors and 5 are not. Of the 7 math majors, 4 drink coffee. Of the 5 non-majors, 1 drinks coffee.

If a student is selected uniformly at random and is known to drink coffee, what is the probability that the student is a math major?

### Problem 8: A Simple Gamble

A box contains three slips labeled 1, 2, and 3. One slip is chosen uniformly at random.

Define the random variable

$$
X=\text{the amount you win in dollars}
$$

by:

- if 1 is drawn, you win $\$0$,
- if 2 is drawn, you win $\$3$,
- if 3 is drawn, you lose $\$2$.

Compute $\mathbb{E}[X]$. Would a player who only cares about expected value want to play this game?

### Problem 9: Weather Forecasting

A weather forecaster has the following track record:

- on 30% of days it rains,
- when it rains, she predicts rain 80% of the time,
- when it does not rain, she predicts rain 10% of the time.

If she predicts rain today, what is the probability that it actually rains?

### Problem 10: Two-Dice Payoff

Two fair six-sided dice are rolled. Let $X$ be your payoff, where

$$
X=
\begin{cases}
5, & \text{if the sum is }7\\
1, & \text{if the sum is even but not }7\\
-2, & \text{if the sum is odd}.
\end{cases}
$$

Compute the PMF of $X$, then compute $\mathbb{E}[X]$.
