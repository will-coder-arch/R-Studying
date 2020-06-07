# R-Studying
A first little project in R
#Se instalan las librerías quantmod, fPortfolio y lpSolve
install.packages("fPortfolio")
installed.packages("lpSolve")
install.packages("quantmod")

#Se llaman las librerías
library(quantmod)
library(lpSolve)
library(fPortfolio)

#Se busca analizar 6 activos, y en primer lugar construir un portafolio optimo según la teoría de Markowitz
#Los activos elegidos en base a la coyuntura son MKTX, AAPL, MSFT, ZM, MMM y CLCX


