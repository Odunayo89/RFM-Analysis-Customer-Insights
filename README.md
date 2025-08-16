[clean_superstore.csv](https://github.com/user-attachments/files/18270061/clean_superstore.csv)
[Superstore.csv](https://github.com/user-attachments/files/18270060/Superstore.csv)
# Project 1: Finding_valuable_customers
With growing demands and cut-throat competitions in the market, a Superstore Giant would like to design a customer loyalty program that strengthens its relationship with its' customers and incentivizes repeat purchases. The objective of the loyalty program is to increase customer retention and drive incremental sales by targeting customers with personalized promotional offers. The company's marketing manager has proposed to implement a tier-based marketing campaign where customers are offered cash rewards as incentives towards their first purchase following enrollment into the loyalty program. The proposed cash reward offers are as follows:

Get $200 on first purchase

Get $100 on first purchase

Get $25 on first purchase

The Superstore Giant is seeking our knowledge in identifying which customers should get what offer as this requires understanding the customers' buying behaviors. I have been provided access to the customer transaction database contained in the Superstore.csv file and asked to provide valuable insights into customer behavior by grouping customers into different segments based on their buying behavior and loyalty to the business.

In other to solve this problem, I have performed a value-based customer segmentation analysis (also known as RFM Segmentation) using customers' transaction histories to group the customer base into different value segments. The final output of my analysis is a table containing customer Ids, customer value segment and the cash reward recommendation.

As part of my effort to support the marketing team in the personalization of promotional offers, I have also developed a predictive analytics model which takes into account  the total expected profit from a customer in the value ranking. The model provide to the marketing team  how much profit could be expected from each customer in the next one year of transactions


### Dataset Overview
Below provides the description of columns contained in the Superstore.csv dataset.

1. Order ID: Unique Order ID for each Customer.

2. Order Date: Order Date of the product.

3. Ship Date: Shipping Date of the Product.

4. Ship Mode: Shipping Mode specified by the Customer.

5. Customer ID: Unique ID to identify each Customer.

6. Customer Name: Name of the Customer.

7. Segment: The segment where the Customer belongs.

8. Country: Country of residence of the Customer.

9. City: City of residence of the Customer.

10. State: State of residence of the Customer.

11. Postal Code: Postal Code of every Customer.

12. Region: Region where the Customer belongs.

13. Product ID: Unique ID of the Product.

14. Category: Category of the product ordered.

15. Sub-Category: Sub-Category of the product ordered.

16. Product Name: Name of the Product.

17. Sales: Sales of the Product.

18. Quantity: Quantity of the Product.

19. Discount: Discount provided.

20. Profit: Profit/Loss incurred.

# Project 2: Fitness Tracker Dataset                                      
[gym_members_exercise_tracking_synthetic_data.csv](https://github.com/user-attachments/files/18270463/gym_members_exercise_tracking_synthetic_data.csv)


## About Dataset
The Fitness Tracker Dataset contains detailed information about individuals' fitness metrics, exercise routines, and health parameters. This dataset is designed to provide insights into fitness trends, workout habits, and overall health patterns. It is ideal for exploratory data analysis (EDA), machine learning applications, and health analytics. The dataset can help identify relationships between physical activity, body metrics, and health outcomes.
Features:
Age: Age of the individual in years.
Gender:Gender of the individual (e.g., Male, Female).
Weight (kg): Weight of the individual in kilograms.
Height (m): Height of the individual in meters.
Max_BPM:Maximum heartbeats per minute recorded during exercise.
Avg_BPM: Average heartbeats per minute during a workout session.
Resting_BPM:Resting heartbeats per minute.
Session_Duration (hours):Duration of the workout session in hours.
Calories_Burned:Total calories burned during a workout session.
Workout_Type:Type of workout performed (e.g., Cardio, Strength, Yoga).
Fat_Percentage:Percentage of body fat.
Water_Intake (liters):Water intake in liters during or after the workout.
Workout_Frequency (days/week): Number of days per week the individual exercises.
Experience_Level:Level of fitness experience (e.g., Beginner, Intermediate, Advanced).
BMI:Body Mass Index, calculated as weight (kg) / height (m)^2.

### Usage:
This dataset is suitable for:

Analyzing the impact of fitness routines on health metrics.
Exploring trends in heart rate, calorie burn, and workout habits.
Correlating body metrics like BMI and fat percentage with exercise patterns.
Building predictive models for fitness and health analytics.
This is a synthetic dataset created for educational and analytical purposes and does not represent real-world data
### What I did
I analyzed the impact of fitness routines on health metrics by exploring how variables like workout frequency and session duration influence outcomes such as calories burned and BMI. Trends in heart rate variability, calorie burn, and workout habits were examined using visualizations like pair plots and heatmaps, which helped uncover patterns and outliers. I also investigated the correlation between body metrics, such as BMI and fat percentage, with exercise patterns to better understand their relationships. To build predictive analytics, I developed a Random Forest Regression model to estimate calories burned based on features like BMI, session duration, and workout frequency. The model’s performance was evaluated using Mean Absolute Error (MAE). It is important to note that this project used a synthetic dataset created for educational purposes, which does not represent real-world data but serves as a practical tool for demonstrating data analysis and machine learning techniques.








