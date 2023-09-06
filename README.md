# citibeats
In this project I will try to model the population of France using economic data and other measures.

The main findings are:

* We can model the population with an ARIMA(1,3,1) model; or
* Using a VAR analysis, we can model the population with:  
```math
\hat{p}_{t} = 1.65 p_{t-1} + 0.65 m_{t-1} -0.65 p_{t-2} + 3165.04 c_{t-2} - 1034143.59
```
where $\hat{p}$ is population prediction, $p$ is population, $m$ the net migration, and $c$ the monthly consumer confidence.

## Contets of repo:

**cb_assesment.ipynb** is the ipython notebook that walks through the analysis.

**profilereport.html** is a report with summaries of each time series.

**projectsummary** is an executive summary of the project.

The remaining files are the datasets provided by Citibeats.

