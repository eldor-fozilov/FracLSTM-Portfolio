# FracLSTM-Portfolio

This project explores the effectiveness of **fractional differencing** in financial time series preprocessing for return prediction. It investigates whether transforming non-stationary stock price data can improve prediction accuracy and portfolio performance when combined with **Long Short-Term Memory (LSTM)** networks.

## Overview

- Preprocessed S&P 500 stock price data (2000–2023) using fractional differencing and daily volume features.
- Trained two LSTM-based return forecasting models:
  - **Target model**: fractionally differenced prices + volume
  - **Benchmark model**: raw returns + volume
- Constructed long-short portfolios by ranking predicted returns (top-5 long, bottom-5 short).
- Conducted two experiments with varying lag and hidden unit configurations.

## Key Insights

- Benchmark models using raw returns **outperformed** those using fractionally differenced data in both experiments.
- Results suggest **fractional differencing may not consistently enhance return prediction** in this context, though further exploration might be necessary.

---

📄 For full details, please refer to `project_summary.pptx` and `project_report.pdf` included in this repository.
