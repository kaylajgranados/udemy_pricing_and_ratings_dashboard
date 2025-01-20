# Udemy Projected Revenue and Ratings Dashboard

![Screen Shot 2025-01-20 at 2 36 30 PM](https://github.com/user-attachments/assets/49ea81ae-a4aa-4a1f-95be-ad93e62938f2)

## Dataset 

The data used for this project is the Udemy Course Data from Kaggle. https://www.kaggle.com/datasets/omarmohammed271/udemy-courses-2025. 

There were 12 columns: course_id, course_title, url, price, num_subscribers, num_reviews, num_lectures, level, Rating, content_duration, published_date, subject. 

## Research Question 
 
1. Which subjects and class levels should Udemy expand to increase projected revenue (calculated by subscribers and price)? 
2. What are Udemy’s course ratings and review response rate for courses with highest projected revenue? 

## Data Cleaning 
 
The data cleaning steps included: 
-Sorting to remove blank rows 
-Removing 90 duplicate course IDs
-Changing data types and correcting formatting

## Data Analysis 

I calculated the following fields: 
Review Response Rate = num_reviews / num_subscribers
Projected Revenue = price * num_subscribers 

Then, I used nested IF functions to create ranges for the following fields: course price, number of subscribers, ratings, review response rate, and projected revenue. For example, the formula below categorizes the number of subscribers into five levels (Very High, High, Medium, Low, and Very Low) based on defined criteria. 

<img width="755" alt="Screen Shot 2025-01-20 at 3 20 41 PM" src="https://github.com/user-attachments/assets/1704db87-ce31-4266-a4f2-6df75de44cc9" />

## Dashboard Creation

I created pivot tables and pivot charts to visualize:
-Top 10 subjects with highest projected revenue 
-Projected revenue by course level
-Average response rate by projected course revenue
-Average rating by projected course revenue 

This is the pivot table for Top 10 subjects with highest projected revenue. 

<img width="314" alt="Screen Shot 2025-01-20 at 3 20 08 PM" src="https://github.com/user-attachments/assets/0013f87d-f5e4-4cdd-a05a-f7802dc9833b" />

I added slicers to enable filtering across all four charts simultaneously. For example, this is the dashboard filtered for courses with a very high number of subscribers (>150,000). 

<img width="716" alt="Screen Shot 2025-01-20 at 2 49 51 PM" src="https://github.com/user-attachments/assets/27080020-d336-476c-a606-4e292657c4d6" />


## Conclusions and Recommendations 

Python subject area has the highest projected revenue, estimated at $31 billion based on price and number of subscribers. Beginner courses outperform intermediate and expert level courses in projected revenue. Udemy should expand their catalog for beginner-level Python courses to increase revenue and meet market demand. 

Additionally:
-Courses with the highest projected revenue (>1B) have the highest average rating (4.64)
-Courses with the highest projected revenue (>1B) have the highest review response rate (22.24%) 

This suggests that subscribers consider these courses a valuable investment, which could help drive future enrollment. Udemy should identify the key factors contributing to the high ratings and replicate this for other courses.


