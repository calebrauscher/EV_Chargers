# EV_Chargers

This is a report on Electric Vehicle (EV) chargers and the anticipated need for more chargers as EV adoption rates increase. Since there is limited data on EV registrations on a zip code basis some additional estimation was performed. First a k-means clustering algorithm was used to determine similar zip codes based on various factors. After the zip codes were grouped, zipcodes that did have regsitration data were used to predict the EV registrations for zip codes that did not have the registration data.

Each cluster then use a Linear Regression model to predict the EV adoption rate. Based on the current number of chargers in the zip code and the adoption rate it was determined if the current amount of EV chargers would meet the need of the expected amount of EVs or not.
