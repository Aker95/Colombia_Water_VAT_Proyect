# Colombia_Water_VAT_Proyect
Colombia Water Demand Forecast Model, with equivalent compensated variation of VAT on the utility

I use an XGBoost algorithm on the Colombia's encuesta nacional de calidad de vida, which hyperparameters were set by a Bayesian optimization algorithm, to forecast the aggregate water (utility) demand of Colombia's 13 main cities, using a block price loss function. When results were compared, it was observed with Kolmogorov Smirnov test that the predicted and real demand had the same distribution. After that, I implemented a Monte Carlo integration to obtain the compensated variation of a 19% VAT on this utility.
