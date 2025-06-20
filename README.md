
# Volatility Surface Tutorial

This repository contains a single Jupyter notebook that walks through the process of constructing and analyzing an option volatility surface using data for Apple Inc. (AAPL). The notebook combines theoretical background with practical Python code and is aimed at students or practitioners of quantitative finance.

## Contents

- **Volatility_Surface.ipynb** – a comprehensive tutorial that covers:
  - Loading real-world option data from Yahoo Finance via the `yfinance` API (with a fallback to synthetic data if necessary).
  - Calculation of implied volatilities.
  - Fitting parametric models such as SVI and SABR.
  - Interpolating the surface across strikes and maturities.
  - Visualization of volatility smiles and the full three‑dimensional surface.
  - Discussion of calibration, no‑arbitrage constraints and common pitfalls.

## Requirements

To run the notebook you will need a recent Python environment with the following packages:

- `numpy`
- `pandas`
- `matplotlib`
- `scipy`
- `yfinance`
- `jupyter` (for interactive execution)

Install them with `pip`:

```bash
pip install numpy pandas matplotlib scipy yfinance jupyter
```

## Usage

Launch Jupyter and open the notebook:

```bash
jupyter notebook Volatility_Surface.ipynb
```

The notebook is organized into sections with explanatory text and executable code cells. Run the cells in order to reproduce the examples and figures. Internet access is required to fetch current AAPL option data; otherwise the notebook will generate synthetic data so that all subsequent steps still run.

## License

All notebook content is provided for educational purposes. See the headers within `Volatility_Surface.ipynb` for author information.
