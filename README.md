The aim of this project is to forecast bitcoin price using a partial differential equation model. Is based on the academic paper "Using networks and partial differential equations
to forecast bitcoin price movement", by Yufang Wang and  Haiyan Wang.

The project incorporates the utilization of Google Trend Index and chainlets data. Additionally, 
it requires an embedding of chainlet clusters, particularly employing spectral clustering. In 
order to solve the differential equation the Crank-Nicolson method is involved and later the
trapezoid method for integral calculation.

It is coded in Python and uses libraries such as yfinance, pandas, scikitlearn, matplotlib, 
numpy, scipy and more.
