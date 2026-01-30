# Quant Trading & Systematic Strategies

Quantitative market analysis using Python, focusing on returns, risk metrics, and strategy evaluation.

## Project Objectives

This repository presents a structured exploration of quantitative finance and systematic trading strategies, with a strong emphasis on statistical foundations, market risk analysis, and robust backtesting practices.

The project is organized around reusable quantitative tools, clean data pipelines, and well-documented research notebooks. It covers core topics such as return modeling, portfolio risk, drawdowns, Monte Carlo simulations, and the implementation and evaluation of momentum and mean-reversion strategies.

The objective of this work is not to optimize performance at all costs, but to demonstrate a rigorous and realistic approach to quantitative research, highlighting assumptions, limitations, and sources of bias.

This repository is intended as a study as well as a professional portfolio for quantitative research, trading analyst, or junior quant roles.

## Repository structure

quant-trading/
├── notebooks/        # Research notebooks (analysis & experiments)
├── src/              # Reusable quantitative functions
├── data/             # Market data (local or cached)
├── README.md
└── requirements.txt

## Covered topics

- Return modeling (simple & log returns)
- Volatility and correlation analysis
- Portfolio risk and diversification
- Drawdown and performance metrics
- Monte Carlo price simulations
- Momentum strategies
- Mean-reversion strategies
- Strategy comparison and reporting

## Methodology

The research follows a disciplined workflow:

- Clean separation between research (notebooks) and reusable code (src)
- No lookahead bias in signal construction
- Walk-forward evaluation when applicable
- Explicit reporting of assumptions and limitations
- Focus on statistical significance rather than curve-fitting

## Installation

bash
git clone https://github.com/Brynhyldr/quant-trading.git
cd quant-trading
pip install -r requirements.txt
jupyter lab

## Disclaimer

This project is for research and educational purposes only and does not
constitute financial or investment advice.

