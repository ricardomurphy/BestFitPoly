# BestFitPoly
The MATLAB script BestFitPoly.m accompanies the paper by Murphy (2024). It was designed to find ’best-fit’ polynomials for data that might otherwise be analysed by one-way ANOVA. More precisely, the predictor (x) and response (y) are assumed to be quantitative variables on a continuous scale, with x representing some sort of applied treatment (>= 3 replicates per treatment level). For example, the different treatment levels (values of x) might represent radiation doses, drug concentrations, temperatures, voltages etc.. The control treatment level is then x = 0. Similarly y might be growth rate, rate of a biochemical reaction, body weight, latency of a behavioural response and so on. BestFitPoly.m attempts to find the ‘best’ polynomial y = f(x) according to various established selection criteria (MSE, PRESS, AIC, BIC and F-to-enter).  Bootstrapped P values and confidence intervals for model parameters are reported, as well as confidence and prediction intervals for the predicted response and effect size. Some diagnostic plots are also generated to help with the choice of the final model.
