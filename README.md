# Quantitative Pairs Trading Research
Quantitative pairs trading research using R, cointegration analysis, statistical modeling, backtesting, and risk-adjusted performance evaluation.

**Statistical Modeling | Financial Risk Analysis | Backtesting | R**

University of Toronto | Four-person collaborative academic project with Elena Kheir

## Project Overview

This research explores whether statistical relationships between financial assets can support a systematic, market-neutral pairs trading strategy.

Using R and historical financial market data, our team evaluated asset relationships, tested cointegration, developed Z-score-based trading signals, and assessed simulated strategy performance.

The research focused on understanding not only potential profitability but also model reliability, statistical limitations, and financial risk.

## Research Approach

**1. Asset Selection & Hypothesis Testing**

- Investigated Visa/Mastercard and Coca-Cola/Pepsi as initial trading pairs.
- Applied statistical tests to evaluate potential long-term relationships.
- Reconsidered initial asset selections after identifying weaknesses in the cointegration results.

**2. Statistical Modeling**

- Investigated GLD and IAU gold ETFs as an alternative trading pair.
- Applied regression and Engle-Granger cointegration diagnostics.
- Estimated the trading spread using historical adjusted prices.

**3. Strategy Development & Backtesting**

- Constructed Z-score-based trading signals.
- Used an 80/20 chronological training and testing split.
- Simulated long/short trading positions based on deviations from the estimated relationship.

**4. Financial Risk & Performance Evaluation**

- Evaluated simulated cumulative P&L and trading performance.
- Investigated sensitivity to model parameters and trading thresholds.
- Identified limitations involving model stability, transaction costs, and historical assumptions.

## Key Research Findings

The original research reported approximately **5% cumulative simulated P&L** for the GLD/IAU strategy before transaction costs.

The findings also highlighted important risks:

- Strong correlation alone does not guarantee a stable cointegrated relationship.
- Historical model parameters may become unreliable as market conditions change.
- Transaction costs, slippage, and financing costs can reduce actual profitability.
- Further out-of-sample and rolling-window testing would strengthen model validation.

**Note:** Reported backtesting results are historical simulations, not realized trading profits. They have not been independently reproduced in this portfolio edition.


### Interpretation & Reproducibility

This repository documents the original research and analytical work completed as part of a collaborative university project.

The reported performance figures reflect historical, spread-based simulations rather than realized investment returns. Transaction costs, slippage, and financing costs were not included.

Supplementary experiments use different asset pairs and modeling assumptions and should not be directly compared with the main GLD/IAU backtest.

The original R Markdown files and rendered HTML are provided as evidence of the analytical process. The full workflow has not been independently reproduced or validated as a production-ready trading strategy.


## Technical Skills Demonstrated

**Programming:** R, R Markdown

**Statistical Methods:** Regression Analysis, Cointegration Testing, Time-Series Analysis

**Financial Analytics:** Pairs Trading, Statistical Arbitrage, Backtesting, Financial Risk & Performance Evaluation


## Project Files

| File | Description |
|---|---|
| [Research Portfolio Report](team7_final_report.pdf) | Research methodology, findings, visualizations, and limitations |
| [Main R Analysis](analysis/pairs_trading_main.Rmd) | Cointegration analysis, statistical modeling, and GLD/IAU backtesting |
| [Supplementary Analysis](analysis/threshold_sensitivity.Rmd) | Additional asset-pair experiments and trading-parameter analysis |
| [Rendered R Analysis](results/pairs_trading_analysis.html) | HTML report containing R code outputs, statistical diagnostics, and visualizations |


## Project Attribution

This portfolio presents collaborative quantitative finance research originally completed as a four-person University of Toronto course project in 2025.

Jake Jung and Elena Kheir shared project coordination. The underlying analysis and research materials were developed collaboratively.
