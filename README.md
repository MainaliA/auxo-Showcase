# AUXO — Monte Carlo Investment Simulator

Oracle-funded undergraduate research project at UMass Boston.

AUXO is a web-based simulator that models long-term investment outcomes across 10,000 randomized market scenarios, helping users understand risk, volatility, and probability—not just average returns.

Live Demo: https://www.mainaliresearch.com/

## Key Features
- Simulates portfolio growth using Geometric Brownian Motion (GBM)
- Visualizes outcomes via interactive fan charts (P10 / P50 / P90 scenarios)
- Models real returns with inflation adjustment
- Estimates probability of loss and drawdowns over long horizons

## Advanced Modeling
- Jump Diffusion (Merton) for market shocks  
- Regime Switching (Markov Chains) for bull/bear cycles  
- Volatility clustering for post-shock behavior  

## Tech Stack
Next.js, React, TypeScript, Tailwind CSS
