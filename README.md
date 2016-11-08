# FinancialData

## This Julia program fetches financial data from Quandl/Yahoo Finance and forecasts short-term price ranges using a random forest.
The code is written in a Jupyter notebook and has been tested with Julia 0.5.0 on juliabox.com.

### Ensemble of Decision Trees  
Trees:      100  
Avg Leaves: 437.87  
Avg Depth:  29.88  

### 3-fold cross validation on regression forest  
Fold 1  
Mean Squared Error:     0.011898742016446409  
Correlation Coeff:      0.9553657542349979  
Coeff of Determination: 0.8928846736763904  

Fold 2  
Mean Squared Error:     0.009574085016148374  
Correlation Coeff:      0.9616806612315072  
Coeff of Determination: 0.9056793876115462  

Fold 3  
Mean Squared Error:     0.01076097791764666  
Correlation Coeff:      0.9596175522467734  
Coeff of Determination: 0.898666844470652  

Mean Coeff of Determination: 0.8990769685861961  

![History and forecast](output_27_0.png)

![1 year forecast](output_28_0.png)

![Volatility](output_30_0.png)

![Features used in model training](output_24_0.png)
