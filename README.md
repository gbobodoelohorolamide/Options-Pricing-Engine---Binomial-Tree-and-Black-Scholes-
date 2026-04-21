📈 Options Pricing Engine

🧠 Overview

This project implements and compares two fundamental approaches to option pricing: the Black-Scholes analytical model and the Binomial Tree numerical model.
The goal is to build a structured framework for pricing European options and understanding how key variables such as volatility, time to maturity, and interest rates impact derivative pricing.

🎯 Objectives

* Implement Black-Scholes closed-form pricing model

* Build a flexible Binomial Tree pricer (multi-step)

* Compare convergence between numerical and analytical methods

* Analyze sensitivity to volatility and time decay

* Visualize pricing behavior under different market conditions

⚙️ Models Implemented


📊 Black-Scholes Model

A continuous-time analytical solution for pricing European call and put options under constant volatility assumptions.

🌳 Binomial Tree Model

A discrete-time model that simulates possible price paths and uses backward induction to compute option value.

📈 Key Insights

* Binomial model converges to Black-Scholes as number of steps increases

* Option price is highly sensitive to volatility (vega effect)

* Time decay (theta) significantly impacts near-expiry options

* Discrete models provide intuition behind continuous pricing theory

🧮 Features

* Call and Put option pricing

* Adjustable parameters: volatility, strike price, interest rate, maturity

* N-step binomial tree flexibility

* Model comparison between analytical and numerical methods

* Graphical visualization of results

🚀 How to Run
# Clone repositorygit clone https://github.com/gbobodelohorolamide/Options-Pricing-Engine---Binomial-Tree-and-Black-Scholes.git# Install dependenciespip install -r requirements.txt# Run notebook or scriptjupyter notebook

📊 Example Outputs

Binomial vs Black-Scholes convergence plot

🧠 Future Improvements

* Add Monte Carlo simulation pricing

* Implement implied volatility solver

* Extend to American option pricing

* Add real market data calibration

🛠️ Tech Stack

* Python

* NumPy

* Matplotlib

* SciPy (optional)

👤 Author
Gbobodo Elohor Olamide
Aspiring Quantitative Analyst
Focus: Derivatives Pricing, Stochastic Models, Financial Engineering
