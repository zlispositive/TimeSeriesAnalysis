
This is a book by [[]]

### Key concept
- [[stationarity]]
- [[autocovariance]]
- [[sample autocovariance functions]]

### Standard techniques
- [[trend]]
- [[seasonality]]
- Represent the data as a summation of [[trend]], [[seasonality]] and [[residual term]]
- [[Signal plus noise]]

### What to do with time series analysis
- [[Descriptive analysis]] provide the [[trend]], [[seasonality]] and [[residual term]]
- [[Seasonal adjustment]]
- [[Separation/filtering of noise]]
- [[Prediction]]
- [[Simulation Study]]

### How to do [[TOC Time series analysis ]]: some models
- [[Time series models]]

### General approach to time series modeling
- Plot the series and examine the main features of the graph. Check to see if there is
	- [[trend]]
	- [[seasonality]]
	- [[apparent change in behavior]]
	- [[any outlying observations]]
- Remove the trend and seasonal components to get [[stationary residual]]. 
	- Transformation of the data, taking the logirithm, difference 
- Choose a model to fit the residuals
- Forecasting is forecasting the residuals and inverting the transformation back to the original time series ${X_t}$.
- An alternative is to use Fourier 