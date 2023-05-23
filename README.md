# Colombia_Water_VAT_Proyect
Colombia Water Demand Forecast Model, with equivalent compensated variation of VAT tax on the utility

I use an XGBoost algorithm on the Colombia's encuesta nacional de calidad de vida, which hyperparamets were set by a bayesian optimization algorithm, to forecast the aggregate water (utility) demand of Colombia's 13 main cities, using a block price loss function. When results where compare, it was observe with Kolmogorov Smirnov test that the predicted and real demand had the same distribution. Afterthat, I implemented a monte carlo integration in order to obtain a the compensated variation of a 19% VAT on this utility.
