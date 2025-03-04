# Disneyland Review Analysis in SQL  

## Overview  

This project analyzes Disneyland review data using SQL and PySpark to generate insights on user feedback across multiple Disneyland branches (California, Hong Kong, Paris). The analysis includes queries on ratings, review trends over the years, reviewer locations, and various aspects of customer experience (such as food, lines, and review length).  

The project provides valuable insights into customer satisfaction, highlighting key trends in ratings, review counts, and visitor sentiment.  

## Dataset  

The dataset used for this project is a collection of Disneyland reviews, including information such as:  

- **Rating**: Rating given by the reviewer (1-5 stars)  
- **Year_Month**: Year and month the review was posted  
- **Reviewer_Location**: Location of the reviewer  
- **Review_Text**: Text of the review  
- **Branch**: Disneyland location (California, Hong Kong, Paris)  

The dataset is loaded from a CSV file (`DisneylandReviews.csv`) from Kaggle (https://www.kaggle.com/datasets/arushchillar/disneyland-reviews), which contains review data across various years and Disneyland branches.  

## Technologies Used  

- **Python**: Data manipulation and analysis  
- **PySpark**: Running SQL-like queries on structured data  
- **pandas**: DataFrame manipulation  
- **Jupyter Notebook**: Data analysis and documentation  

## Queries and Analysis  

The following key analyses were performed using SQL queries in PySpark:  

1. **Which Branch Has the Highest Average Rating?**  
2. **How Has Review Count Changed Over the Years?**  
3. **Top 5 Most Common Reviewer Locations**  
4. **Which Months Have Higher Review Volumes?**  
5. **Review Count for Each Rating**  
6. **Percentage of Reviews Mentioning Food and Average Rating**  
7. **Percentage of Reviews Mentioning Lines and Average Rating**  
8. **Percentage of Reviews for Each Branch with Ratings Higher Than the Average Rating**  
9. **Average Rating and Review Length for Each Branch**  
10. **Correlation Between Review Length and Rating**
    
## Output
The notebook generates insights through SQL queries and displays results such as:
- Average ratings for each Disneyland branch.
- Trends in review counts over the years.
- Common reviewer locations.
- Distribution of ratings and mentions of specific topics like food and lines.
