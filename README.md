# Udemy Projected Revenue and Ratings Dashboard

![Screen Shot 2025-01-20 at 2 36 30 PM](https://github.com/user-attachments/assets/09c14621-6d87-446c-b67c-2dde0dba0ee4)



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


## Data Analysis 

I calculated the following fields: 
- Review Engagement Rate = num_reviews / num_subscribers
- Total Course Revenue = price * num_subscribers 
- Lectures Viewed = num_lectures * num_subscribers

## Conclusion 

