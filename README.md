# Stock Performance and Portfolio Analysis

## Project Overview
This project analyzes the historical performance of five Indian stocks from different sectors and evaluates multiple portfolio strategies based on risk and return.

## Objectives
- Compare stock price trends
- Analyze normalized performance
- Calculate total returns and volatility
- Examine stock correlations
- Evaluate risk-return relationships
- Compare portfolio strategies

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Stocks Analyzed
- HDFC Bank (Banking)
- HINDUNILVR (FMCG)
- Infosys (Information Technology)
- Maruti Suzuki (Automobile)
- Reliance Industries (Energy, Retail & Telecom)

## Key Findings

- A ₹100 investment in Maruti grew to approximately ₹178, making it the best-performing stock among the selected companies.
- Maruti achieved the highest total return of 78.07%, while HINDUNILVR recorded a negative return of -1.92%.
- Infosys exhibited the highest annualized volatility (24.66%), whereas HINDUNILVR showed the lowest volatility (20.36%).
- Correlation values ranged from approximately 0.18 to 0.37, indicating low to moderate relationships between stocks and supporting diversification benefits.
- The Growth Portfolio generated the highest annual return of 9.99% with a volatility of 16.54%.
- The Equal Weight Portfolio achieved a return of 6.66% while maintaining the lowest volatility of 14.41%.
- Despite allocating more capital to lower-risk stocks, the Conservative Portfolio returned only 6.09% with a volatility of 14.44%, offering no significant risk reduction compared to the Equal Weight Portfolio.

## Visualizations
<img width="800" height="700" src="https://github.com/Mann0405/Stock-Performance-and-Portfolio-Analysis-using-Python/blob/main/Normalized%20Stock%20Performance%20Snapshot.PNG" />
<img width="600" height="500" src="https://github.com/Mann0405/Stock-Performance-and-Portfolio-Analysis-using-Python/blob/main/Portfolio%20Strategies%20Snapshot.PNG" />

<p align="center">
  <img src="https://github.com/Mann0405/Stock-Performance-and-Portfolio-Analysis-using-Python/blob/main/Risk%20vs%20Return%20Snapshot.PNG" width="48%">
  <img src="https://github.com/Mann0405/Stock-Performance-and-Portfolio-Analysis-using-Python/blob/main/Correlation%20Snapshot.PNG" width="48%">
</p>

<table>
  <tr>
    <td>
      <img src="https://github.com/Mann0405/Stock-Performance-and-Portfolio-Analysis-using-Python/blob/main/Risk%20vs%20Return%20Snapshot.PNG?raw=true" width="700" />
    </td>
    <td>
      <img src="https://github.com/Mann0405/Stock-Performance-and-Portfolio-Analysis-using-Python/blob/main/Correlation%20Snapshot.PNG?raw=true" width="700" />
    </td>
  </tr>
</table>

## Portfolio Strategies

### Equal Weight Portfolio
20% allocation to each stock.

### Growth Portfolio
- Maruti: 45%
- Reliance: 30%
- Infosys: 10%
- HDFC Bank: 10%
- HINDUNILVR: 5%

### Conservative Portfolio
- HDFC Bank: 30%
- HINDUNILVR: 25%
- Reliance: 20%
- Maruti: 15%
- Infosys: 10%


## Insights

- Diversification across stocks from different sectors helped reduce portfolio risk compared to investing in individual stocks.
- Stock selection alone was not sufficient; portfolio allocation played a significant role in determining risk and return.
- Higher risk did not consistently translate into higher returns, highlighting the importance of evaluating both metrics together.
- An equal-weight allocation proved more effective than a conservative allocation in achieving a balanced risk-return tradeoff.

## Conclusion

By analyzing stock performance, risk metrics, correlations, and portfolio strategies, this project demonstrated the importance of balancing return and risk in investment decisions. The results showed that diversification helped reduce portfolio volatility and that higher risk did not always lead to higher returns. Among the strategies evaluated, the Equal Weight Portfolio offered the most efficient balance between risk and return, highlighting the value of disciplined portfolio construction.
