# Crisis-Aware AI Forecasting for U.S. Equity Indices

## Project Overview

This repository presents an independent empirical finance and financial machine learning project on crisis-aware forecasting for U.S. equity indices.

The project studies whether long-history macro-financial information, crisis-regime indicators, machine learning models, conformal uncertainty calibration, backtesting evidence, and mechanism interpretation can jointly support a crisis-aware forecasting framework for the S&P 500 and Nasdaq-100.

## Research Title

**Crisis-Aware AI Forecasting for U.S. Equity Indices: Evidence from the S&P 500 and Nasdaq-100**

## Core Design

This project follows a long-history empirical design rather than a short post-2000 sample.

- S&P 500 layer: begins around 1957 where available.
- Nasdaq-100 layer: begins around 1985/1986 where available.
- Pooled panel: more than 27,000 asset-date observations.
- Forecasting targets: future returns and future return directions.
- Model layers: baseline, tree-based, boosted-gradient, ensemble, crisis-aware routing, stacking, conformal uncertainty calibration, backtesting, and mechanism interpretation.

## Main Evidence

- Tree-based models provide the strongest directional classification evidence among the clean model layers.
- Advanced model layers improve over simple baseline models.
- Conformal prediction provides uncertainty-calibration evidence.
- Backtesting evaluates economic relevance but does not imply guaranteed trading profitability.
- Mechanism decomposition links model outputs to interpretable macro-financial channels.

## Repository Structure

```text
reports/   Final reports and teacher-annotated guide
figures/   Selected figures used in the final report
tables/    Key quantitative evidence tables
docs/      Project summary and reproducibility notes

## Important Disclaimer

This repository is for academic and research portfolio purposes only.

It does not provide investment advice, trading recommendations, or guaranteed financial performance.

The results should be interpreted as predictive and mechanism-consistent evidence, not as causal proof.

## Author

Yingjie Wang


