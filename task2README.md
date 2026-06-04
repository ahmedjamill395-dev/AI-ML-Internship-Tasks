# Task 2: Stock Price Prediction

## Objective
Predict next day's closing price using historical stock data from Yahoo Finance.

## Stock Used
**AAPL (Apple Inc.)** - 2 years of historical data

## Features Used
- Open, High, Low, Volume
- Day of week, Month
- Price range (High - Low)
- Price change percentage
- 5-day and 10-day moving averages
- Volume change percentage

## Models Tested
| Model | MAE | RMSE | R² Score |
|-------|-----|------|----------|
| Linear Regression | $X.XX | $X.XX | X.XXX |
| Random Forest | $X.XX | $X.XX | X.XXX |

## Best Model
**Random Forest** - Achieved R² score of X.XXX

## Key Findings
- Most important feature: [e.g., Close price / MA_5]
- Average prediction error: $X.XX
- Model successfully captures price trends

## Visualizations Included
1. Actual vs Predicted (Linear Regression)
2. Actual vs Predicted (Random Forest)
3. Both models comparison
4. Prediction error distribution
5. Feature importance chart

## Next Day Prediction
- Today's price: $XXX.XX
- Predicted tomorrow: $XXX.XX
- Expected change: +$X.XX (X.XX%)

## Limitations
- Only uses historical price data
- Doesn't consider news, sentiment, or market events
- Stock prices are highly volatile

## How to Run
1. Open in Google Colab
2. Run all cells
3. Change `stock_symbol` to test different stocks

## Files
- `Task2.ipynb` - Complete implementation

## Author
[Ahmed Jamil]
AI/ML Intern - DevelopersHub Corporation
