

# The Capital Asset Pricing Model (CAPM)
###By Chris Preuss

CAPM remains one of the workhorse statistical models in finance. It is so common that sites like Yahoo!Finance report the measures we will estimate statistically.
I use CAPM for a reason: absent experimental data, it is the only application of the bivariate linear model that I believe has validity in the real world.
The upshot of the CAPM says that we can directly interpret the intercept and slope coefficients as real-world measures relating the excess (or risk-adjusted) returns of a particular stock to those of a basket of stocks, such as a specific market.

CAPM as a Bivariate Linear Model

Let ri denote the rate of return to asset i, rf denote the known rate of return on a risk-free asset (for example, short-term US government debt), and rm denote the rate of return to a portfolio (or a market) that includes i. The following equation can be derived:

E(ri)−rf= α+β⋅(E(rm)−rf)

Here, E(⋅) denotes an expected value (because this is a forward-looking prediction). In CAPM, β captures the sensitivity of an asset’s returns to the returns to a portfolio or to the market on which an asset trades. In other words, it non-diversifiable risk. In addition, α measures an asset i’s excess (or abnormal) returns.

Phrases you may have heard:

  1. The stock's beta is high
  2. The hedge fund is chasing alpha

Formally, we can express our conjecture as a joint hypothesis:

H0:α=0,β=1 H1: not H0
