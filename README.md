# UTAGL_EnsembleTechniques
Ensemble models use a collection of machine learning models to make predictions, rather than individual models.

The purpose of this project is to develop a deep understanding of different ensemble methods like bagging, boosting, and stacking and to implement these algorithms for classification and regression problems. 

Link to Jupyter notebook: https://github.com/kwajpaige/UTAGL_EnsembleTechniques/blob/main/PaigeSingleton_EnsembleTechnique_TravelPackage082022.ipynb

## Background
The Policy Maker of a tourism company wants to enable and establish a viable business model to expand the customer base.
One of the ways to expand the customer base is to introduce a new offering of packages.
Currently, there are 5 types of packages the company is offering - Basic, Standard, Deluxe, Super Deluxe, King. Looking at the data of the last year, we observed that 18% of the customers purchased the packages.
However, it was difficult to identify the potential customers because customers were contacted at random without looking at the available information.
The company is now planning to launch a new product i.e. Wellness Tourism Package. Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance or kick-start a healthy lifestyle, and support or increase one's sense of well-being.
The company wants to harness the available data of existing and potential customers to target the right customers.

## Data Dictionary
- CustomerID: Unique customer ID
- ProdTaken: Whether the customer has purchased a package or not (0: No, 1: Yes)
- Age: Age of customer
- TypeofContact: How customer was contacted (Company Invited or Self Inquiry)
- CityTier: City tier depends on the development of a city, population, facilities, and living standards. The categories are ordered i.e. Tier 1 > Tier 2 > Tier 3. It's the city the customer lives in.
- Occupation: Occupation of customer
- Gender: Gender of customer
- NumberOfPersonVisiting: Total number of persons planning to take the trip with the customer
- PreferredPropertyStar: Preferred hotel property rating by customer
- MaritalStatus: Marital status of customer
- NumberOfTrips: Average number of trips in a year by customer
- Passport: The customer has a passport or not (0: No, 1: Yes)
- OwnCar: Whether the customers own a car or not (0: No, 1: Yes)
- NumberOfChildrenVisiting: Total number of children with age less than 5 planning to take the trip with the customer
- Designation: Designation of the customer in the current organization
- MonthlyIncome: Gross monthly income of the customer

## Objective
Predict which customer is more likely to purchase the newly introduced travel package.

## Takeaways
I would use the model as a means of predicting but I would use it with caution. I would recommend that the business also consider the EDA analysis and utilize this to target customer groups in their sales process. Fortargeting customer groups, I would rely heavily on Monthly Income data to determine which products to pitch to potential clients. The median monthly income data combined with Age group analysis and other slightly less dominant features can act as a guide toward product being pitched to customer groups. Additionally, I would train my sales people on ideal pitch durations and number of follow-ups as these also appear to be a driver of success.
