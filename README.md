# Gaussian-Copula-For-Extreme-Value-Theory

Gaussian Copula Model Overview:
1. Data Collection:
Historical daily stock price data for MRNA and AMAT is collected.
2. Data Transformation:
Daily returns are calculated to understand how much the stock prices change from one day to the next.
The returns are transformed to a uniform distribution to simplify the modeling process.
3. Modeling with Gaussian Copula:
A Gaussian Copula is a statistical tool used to model the dependence structure between random variables.
In this case, it's used to model how the daily returns of MRNA and AMAT are related.
4. Parameter Estimation:
The model estimates a parameter (correlation coefficient) that quantifies the strength and direction of the relationship between the returns of MRNA and AMAT.
5. Joint Probability Estimation:
The model calculates the joint probability, which represents the likelihood of specific events happening together. For example, it estimates the probability of both MRNA and AMAT stocks dropping on the same day.
6. Visualization:
The script creates visualizations to help understand the results:
A 3D Bell Chart illustrates the joint probability and correlation between the two stocks.
A Heatmap displays the correlation matrix, showing how much the returns of MRNA and AMAT are correlated.
7. Interpretation:
The correlation coefficient helps interpret the strength and nature of the relationship between the stocks:
A positive coefficient (e.g., 0.15) suggests a weak positive relationship.
The closer the coefficient is to 1, the stronger the positive relationship.
8. Insights:
The model and visualizations provide insights into how the stocks move in relation to each other and help assess the likelihood of specific joint events.
9. Limitations:
While Gaussian Copula is a powerful tool, it assumes a linear relationship and may not capture all complexities in the data.

