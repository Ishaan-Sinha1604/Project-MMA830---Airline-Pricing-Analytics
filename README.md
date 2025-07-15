# Project-MMA860---Airline-Pricing-Analytics
Created a pricing strategy for an Airline to start selling tickets 100 days before the flight date.

## Overview
Demand over the selling period is uncertain. Ticket prices are supposed to vary based on the demand.
We need to tradeoff between sales today and expected sales in the future.
Tried 3 pricing strategies: Linear, Adaptive, and Dynamic.
Linear: Price is constant throughout the selling period
Adaptive: Price is proportional to the demand on the given day
Dynamic: Price is based on current demand as well as future expected demand
Used optimization model in Python to find the prices 
