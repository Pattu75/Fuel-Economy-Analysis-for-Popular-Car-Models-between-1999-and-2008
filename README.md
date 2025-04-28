# Fuel-Economy-Analysis-for-Popular-Car-Models-between-1999-and-2008
Building Statistical Models in R: Linear Regression

Project Goal:

The goal of the project is tonalyze trends and relationships in fuel economy among 38 popular car models released consistently from 1999 to 2008, based on a subset of EPA data, with focus on:
	•	Comparing city vs highway MPG,
	•	Exploring the effect of vehicle characteristics (cylinders, displacement, drivetrain, transmission),
	•	Identifying improvement trends across years.

Data Highlights:

	•	Dataset: 234 observations, 11 features (city MPG, highway MPG, drivetrain, transmission, cylinders, etc.).
	•	No missing values detected.
	•	Covers major manufacturers (Audi, Toyota, Ford, Honda, etc.).

 Main Findings:
 
	•	City and Highway MPG are highly correlated (r ≈ 0.956).
	•	Simple Linear Model:
	•	hwy = 0.892 + 1.337 × cty
	•	R² = 91.38%, prediction error ≈ 7.48%.
	•	Adding number of cylinders (cyl) does not improve prediction (p = 0.466).
	•	Compact cars consistently showed better fuel economy than SUVs/trucks.
	•	4WD vehicles had lower MPG compared to front-wheel drive models.

 Model Assessment:
 
	•	Model Assumptions (Linearity, Normality, Homoscedasticity) were satisfied.
	•	Residuals randomly scattered (good linear fit).
	•	Residuals normally distributed (Q-Q plot).
	•	No severe influential points (Cook’s Distance < 1).
 	•	Manual transmissions slightly favored better MPG in smaller cars.
	•	Fuel economy improvements over time were noticeable in some compact models.
	•	Larger SUVs and trucks showed minimal improvement across the decade.

 Final Conclusion:
 
	•	City MPG alone is a strong predictor of Highway MPG.
	•	Simple model preferred over complex models.
	•	Fuel economy advancements were most prominent in compact vehicles.

 City MPG is a reliable indicator of a vehicle’s highway fuel efficiency. Compact, front-wheel-drive cars outperform larger, four-wheel-drive vehicles in fuel economy.
