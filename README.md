# Udemy Projected Revenue and Ratings Dashboard

![Screen Shot 2025-01-11 at 6 59 53 PM](https://github.com/user-attachments/assets/5e6ac95c-b2ac-441c-a84b-818400a77b7b)



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

