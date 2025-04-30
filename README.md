This project uses a logistic regression model to predict the direction of Amazon’s stock movement after earnings announcements.
The model is trained on:
	•	EPS (Earnings Per Share)
	•	Earnings Surprise (Actual EPS --Expected EPS)

Each row in the dataset represents one of the last 9 earnings reports for Amazon.

Target
	•	1: Stock went up after earnings
	•	0: Stock went down or stayed flat

A logistic regression classifier from sklearn.linear_model is used to train on the EPS and surprise values, and then predict the likelihood of the stock going up after a new earnings report.
