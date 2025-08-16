 # Yield Curve Shifts and Duration/Convexity Impact
  Objective - 
 The goal of this project is to analyze and visualize the impact of parallel and non-parallel yield curve shifts on bond portfolios. By applying duration and convexity        measures, we can approximate the price changes due to interest rate movements and compare them against exact repricing.
 Project Structure -
 • src/ycsdc/: Core modules for curves, bonds, portfolio analytics, scenarios, and plots
 • scripts/simulate.py: CLI script for running shift simulations and visualizations
 • data/: Sample portfolio and yield curve CSV files
 • notebooks/: Jupyter notebook with an end-to-end demo
 • tests/: Basic unit tests for verification
 • artifacts/: Output plots and reports
 Usage -
 1. Install dependencies from requirements.txt
 2. Run simulations with scripts/simulate.py:
 python scripts/simulate.py --portfolio data/sample_portfolio.csv --curve
 data/sample_zero_curve.csv --outdir artifacts
 3. View generated P&L; curves, approximation error plots, and scenario analyses in the artifacts/
 folder.
 Key Features -
 • Parallel yield curve shifts (−300 to +300 bps)
 • Non-parallel shifts: steepener, flattener, butterfly, and key-rate moves
 • Bond-level and portfolio-level repricing
 • Duration and convexity-based approximation
 • Key-rate duration analysis
 • Visualization of P&L; impacts and approximation errors
 Conclusion -
 This project demonstrates how yield curve movements affect fixed-income portfolios through duration and convexity measures. Parallel and non-parallel shifts highlight the importance of convexity in non-linear interest rate environments. By combining exact repricing with analytical approximations, portfolio managers gain better insights into risk exposures and potential valuation changes. This framework can be extended to stress testing, risk management, and hedging strategies in real-world fixed-income portfolios
