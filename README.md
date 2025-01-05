# Udemy Pricing and Ratings Report

<img width="1043" alt="Screen Shot 2025-01-04 at 6 35 32 PM" src="https://github.com/user-attachments/assets/8b3835d4-1a3d-4df0-b6a7-9cdc0325a774" />


## Dataset 

I found the Udemy Course Data on Kaggle: https://www.kaggle.com/datasets/omarmohammed271/udemy-courses-2025 

There were 12 columns: course_id, course_title, url, price, num_subscribers, num_reviews, num_lectures, level, Rating, content_duration, published_date, subject. 

## Research Question 
 
- What are the top revenue-generating subjects calculated by subscribers and price? 
- How are Udemy’s course ratings for the top revenue-generating subjects? 
- What are potential opportunities to increase revenue? 

## Data Cleaning 
 
The data cleaning steps included: 
- Sorting to remove blank rows 
- Removing 90 duplicated course IDs
- Changing data types and correcting formatting

## Summary Statistics 

I calculated average, sum, min, max, median, and standard deviation for price, number of subscribers, number of reviews, number of lectures, rating, and content duration. 

<img width="678" alt="Screen Shot 2025-01-04 at 6 36 10 PM" src="https://github.com/user-attachments/assets/05b4c868-f976-45c3-ace5-5dd6a463c9eb" />

## Data Analysis 

I calculated the following fields: 
- Review Engagement Rate = num_reviews / num_subscribers
- Total Course Revenue = price * num_subscribers 
- Lectures Viewed = num_lectures * num_subscribers

I used a pivot table to identify the top 10 subjects based on the total course revenue grouped by subject. 

<img width="647" alt="Screen Shot 2025-01-04 at 6 36 30 PM" src="https://github.com/user-attachments/assets/6ae17dac-b97e-49b8-96f4-a520e940b033" />

<img width="512" alt="image" src="https://github.com/user-attachments/assets/269a71e9-9031-4d25-a902-f6f9bdd273b5" />

## Conclusion 

The subject area with most subscribers and most total course revenue is Python. The highest rated courses in the top 10 revenue-generating subjects are in the CSS subject area. 

Moving forward, Udemy could consider the following to generate revenue: 
Offer additional courses in Python to meet the high demandr. 
Seek to increase enrollment in CSS courses given the high ratings. 

Additionally, it’s important that they keep a careful watch on the Python courses rating and number of subscribers as that is a large portion of their subscription revenue. 

