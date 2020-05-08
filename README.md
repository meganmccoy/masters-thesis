# masters-thesis

This paper presents a replication of Flabbi 2010 on Current Population Survey (CPS) data collected in 1995 as well as a re-estimation with data from the German Socio-Economic Panel (SOEP) collected in 2017. An extension to Flabbi’s model is explored  in which employees experience an exogenous promotion shock that occurs to women at prejudiced employers less frequently than women at unprejudiced employers and men. An identification strategy for the extension utilizing features in the SOEP data is suggested.

The model is estimated through maximizing the log-likelihood function. Estimations were done in Python and the code is  available in this repository. The identifying functions in Flabbi 2010 were written by hand with minimal use of Python packages. The optimization was conducted by minimizing the absolute value of the log-likelihood initiated at the estimation values in Flabbi 2010 using the BFGS algorithm.
