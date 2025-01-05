# Udemy Pricing and Ratings Report

## Dataset 

I found the Udemy Course Data on Kaggle: https://www.kaggle.com/datasets/omarmohammed271/udemy-courses-2025 

There were 12 columns: course_id, course_title, url, price, num_subscribers, num_reviews, num_lectures, level, Rating, content_duration, published_date, subject. 

## Research Question 
 
- What subjects should Udemy offer more courses for based on revenue calculated by subscribers and price? 
- How are Udemy’s course ratings for the top revenue generating subjects? 
- What are potential opportunities to increase revenue? 

## Data Cleaning 
 
The data cleaning steps included: 
- Sorting to remove blank rows 
- Removing 90 duplicated course IDs
- Changing data types and correcting formatting

## Summary Statistics 

I calculated average, sum, min, max, median, and standard deviation for price, number of subscribers, number of reviews, number of lectures, rating, and content duration. 

Screenshot of table


## Data Analysis 

I calculated the following fields: 
- Review Engagement Rate = num_reviews / num_subscribers
- Total Course Revenue = price * num_subscribers 
- Lectures Viewed = num_lectures * num_subscribers

I used a pivot table to identify the top 10 subjects based on the total course revenue grouped by subject. 

Screenshot of pivot table

Screenshot of chart


## Conclusion 

The subject area with most subscribers and most total course revenue is Python. The highest rated courses in the top 10 revenue-generating subjects are in the CSS subject area. 

Moving forward, Udemy could consider the following to generate revenue: 
Offer additional courses in Python to meet the high demandr. 
Seek to increase enrollment in CSS courses given the high ratings. 

Additionally, it’s important that they keep a careful watch on the Python courses rating and number of subscribers as that is a large portion of their subscription revenue. 

