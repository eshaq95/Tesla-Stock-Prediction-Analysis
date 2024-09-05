# Comparative Study of Traditional Technical Analysis and Machine Learning in Stock Prediction

## Project Overview
This project compares the effectiveness of traditional technical analysis and machine learning techniques in predicting the price movements of Tesla, Inc. (NASDAQ: TSLA) stock. The study analyzes various technical trading rules and employs advanced machine learning models to forecast stock price directions.

## Key Features
- Analysis of technical trading rules based on popular indicators (BB, RSI, MACD, MA)
- Implementation of machine learning models (LSTM, SVM) for stock price prediction
- Comparison of traditional and ML-based approaches
- Rigorous statistical analysis including White's Reality Check for data snooping bias

## Data
The dataset comprises historical stock data for Tesla, Inc. from June 29, 2010, to March 15, 2024, sourced from Yahoo Finance.

## Methodology
1. Technical Analysis:
   - Implemented trading strategies based on MA, MACD, RSI, and BB indicators
   - Applied various trading filters (band, time-delay, fixed-length)
   - Evaluated performance using Sharpe Ratio, Cumulative Return, and Annualized Return

2. Machine Learning:
   - Developed LSTM and SVM models for binary classification of price movements
   - Used technical indicators as input features
   - Compared performance with traditional technical analysis

3. Statistical Analysis:
   - Employed White's Reality Check to control for data snooping bias
   - Conducted Wilcoxon rank-sum tests for statistical significance

## Results
- Technical trading rules showed mixed performance, with better results in out-of-sample periods
- LSTM-based models, particularly LSTM-RSI-MACD, outperformed traditional techniques
- Machine learning models demonstrated better adaptability to changing market conditions

## Repository Structure
- `data/`: Contains the dataset and data preparation scripts
- `technical_analysis/`: Implementations of technical trading rules
- `machine_learning/`: LSTM and SVM model implementations
- `analysis/`: Scripts for performance evaluation and statistical tests
- `results/`: Outputs, figures, and detailed result analysis
- `notebooks/`: Jupyter notebooks for exploratory data analysis and visualizations

## Usage
[Provide instructions on how to run your code, including any dependencies]

## Contributors
- Eshaq Rahmani

## License
[Specify the license for your project]

## Acknowledgments
- Supervisor: Anqi Liu, Cardiff University
- [Any other acknowledgments]
