# Hi, I'm Yinghao 👋

I build reproducible research software at the intersection of **quantitative
modeling**, **medical imaging**, and **scientific machine learning**.

My work focuses on turning research ideas into complete Python projects:
well-defined assumptions, leakage-aware validation, tested code, clear
limitations, and results that other people can inspect.

## Featured projects

### [Cross-Asset Portfolio Allocation](https://github.com/yinghaofmri1/cross-asset-portfolio-allocation)

A walk-forward research framework for 11 cross-asset ETFs.

- Modern Portfolio Theory: minimum variance and maximum Sharpe
- Black-Litterman with momentum and market-regime views
- Expected-return and covariance shrinkage
- Monthly rebalancing with turnover and transaction costs
- Out-of-sample comparison, stress scenarios, SVG charts, and HTML reports
- Automated tests with GitHub Actions

### [Ocular Rigid Registration](https://github.com/yinghaofmri1/ocular-rigid-registration)

A PyTorch pipeline for rigid propagation of ocular MRI labels across dynamic
3D frames.

- 3D CNN regression of six-degree-of-freedom rigid transforms
- Spatial-transformer label propagation
- Subject-level five-fold cross-validation
- Separate right-eye and left-eye models
- Reproducible training, inference, tests, and documented limitations

## Technical toolkit

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

`Python` · `PyTorch` · `NumPy` · `pandas` · `CVXPY` · `yfinance` ·
`NIfTI` · `Git` · `GitHub Actions`

## Current research interests

- Robust portfolio construction and risk-aware asset allocation
- Point-in-time macroeconomic and factor data
- Regime detection and model stability
- 3D medical-image registration and label propagation
- Validation design for small scientific datasets

## How I approach research

- Keep training and evaluation information strictly separated.
- Use subject-level or time-aware validation when the problem requires it.
- Include realistic costs, constraints, and baseline comparisons.
- Report limitations as clearly as the headline result.
- Package experiments as readable, tested, reproducible software.

