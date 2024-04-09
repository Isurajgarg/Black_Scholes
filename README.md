
#  **1. BLACK SCHOLES MERTON MODEL**

The Black-Scholes model is a fundamental tool in option pricing. It is originally designed for calculating theoretical value of European options on non-dividend paying stocks. The formula for a call option (C) and put option (P) in the absence of dividends is as follows:

# **1.1 Without Dividend paying stocks**
$$C = S_0N(d1)-ke^{-rt}N(d2)$$

$$P = ke^{-rt}N(-d2)- S_0N(-d1)$$


$$d1 = \frac{ln(S_0/k)+(r+\sigma^2/2)t}{\sigma√t}$$

$$d2 = d1-\sigma*√t$$

# **1.2 With Dividend paying stocks**

For dividend-paying stocks, the Modified Black-Scholes model is. The adjusted formula for a call option (C) and put option (P) becomes:

  
$$C = S_0e^{-qt}N(d1)-(ke^{-rt})N(d2)$$

$$P = (ke^{-rt}N(-d2)-S_0e^{-q*t}N(-d1)$$



Where (q) is the continuous dividend yield, and (N) represents the cumulative distribution function of the standard normal distribution. The variables (d_1) and (d_2) are calculated as mentioned earlier.
