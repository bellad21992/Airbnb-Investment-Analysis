# Airbnb-Investment-Analysis

This project is for a hypothetical real estate investing firm who is considering purchasing apartments in Boston and renting them out on Airbnb. 
- Analyzes the Airbnb data on rentals in the Rosalindale and JP neighborhoods and develops a final regression model that does the best possible job of predicting the nightly price of an Airbnb rental.
- Finds the estimated “Est. Monthly Payment” reported on Redfin for a property on sale in these neighborhoods (which includes mortgage, taxes, insurance and homeowner fees). Housing prices in Boston have increased 53% since the end of 2016 when this Airbnb data were collected. Converted this current mortgage cost to 2016 values to fit the data by multiplying it by 1/1.53 = 0.65.
- Uses the final regression G (after removing variables with |t|<1) to estimate the nightly rent you could charge for an apartment in this neighborhood.
- Calculated expected monthly profit as Monthly Airbnb Revenue - Estimated Monthly Payment (including maintenance and cleaning fees).
- Conclusion: It is profitable to purchase and rent an Airbnb in these neighborhoods. The expected monthly profit given it is rented out for 20 days is $1594.50. To break even on investment, the property would need to be rented out for 14 days each month.
