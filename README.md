# Portfolio Management Project

## 1. Executive Summary
This project presents a comprehensive equity research study on **Axis Bank** combined with a portfolio optimization framework using Modern Portfolio Theory. The study integrates Fundamental Analysis (valuation), Technical Analysis (trading strategy), and Quantitative Portfolio Management (Markowitz model).

**Key Performance Highlights:**
-   **Portfolio Return:** +30.34% (Annualized based on strategy backtest).
-   **Valuation Verdict:** Axis Bank is **Undervalued** (Intrinsic Value > Current Market Price).
-   **Optimal Portfolio:** Identified via Maximum Sharpe Ratio on the Efficient Frontier.

## 2. Project Structure
-   `Data/`: Contains Excel models for valuation (DCF, Relative) and Portfolio Optimization.
-   `Reports/`: Full PDF research report.
-   `Results/`: Generated charts (Efficient Frontier, Covariance Matrix).

## 3. Fundamental Analysis: Axis Bank
We evaluated Axis Bank's financial health and growth prospects using:
-   **Economic Moat:** Strong retail loan growth (20% YoY) and digital transformation.
-   **Valuation Models:**
    -   **P/E Ratio:** 12.98 (vs Industry Avg 16.64) $\rightarrow$ *Undervalued*
    -   **PEG Ratio:** 0.706 $\rightarrow$ *Undervalued*
    -   **DCF Analysis:** Conservative intrinsic value of ₹839.13, with upside potential to ₹1482 based on relative metrics.

## 4. Technical Analysis Strategy
A trend-following strategy was implemented using:
-   **Indicators:** Moving Average Double Crossover (14/21 period) + RSI.
-   **Signals:**
    -   *Buy*: April 11 (MA Crossover + Oversold RSI)
    -   *Sell*: July 27 & Dec 28 (Bearish Crossover + Overbought RSI)
-   **Outcome:** The strategy captured the primary uptrend while avoiding stagnation periods.

## 5. Portfolio Optimization
Using historical returns of selected assets, we constructed an optimal portfolio:
1.  **Covariance Matrix:** Calculated to measure asset correlation.
2.  **Efficient Frontier:** Plotted to visualize the risk-return trade-off.
3.  **Allocations:**
    -   **Minimum Variance Portfolio:** Lowest possible risk.
    -   **Optimal Portfolio:** Maximize Sharpe Ratio (Excess return per unit of risk).

## 6. Visualizations
| Efficient Frontier | Covariance Matrix |
| :---: | :---: |
| ![Efficient Frontier](Results/Efficient%20Frontier.jpg) | ![Covariance](Results/Covariance%20Matrix.jpg) |

## Team Group 06
-   Aarush Gupta
-   [Add Team Members]
