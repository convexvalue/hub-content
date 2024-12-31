---
title: The IP Module
date: 2024-12-31
---

# The IP Module

IP stands for "Implied Probability". The IP module uses option prices to find the ranges where the underlying is expected to close on a given expiration within a 50% and 70% range.

Here is how it works:

## The Theory

If you think about what the price of an option should be, you quickly find yourself thinking about probabilities.

For example - if $AAPL stock price is 100, what should the price of an $AAPL Strike 110 Call expiring in 10 days be?

If stock price is below 110 at expiration the Call option will be worthless, and if stock price is above 110 it will be worth something. Thus - whatever the price of the option is, it must be deeply tied to the probability of the stock price being above or below 110.
