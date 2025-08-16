 Online Courses Dataset - README

 Dataset Overview
This dataset contains information on 10,000 online courses across multiple platforms. 
It includes details such as course IDs, names, categories, duration, number of enrolled students, 
completion rates, prices, and ratings.

 Columns:
1. Course_ID - Unique identifier for each course
2. Course_Name - Title of the course
3. Category - Subject area of the course (e.g., Technology, Business, Office Tools, etc.)
4. Duration (hours) - Total duration of the course in hours
5. Enrolled_Students - Number of students enrolled in the course
6. Completion_Rate (%) - Percentage of students who completed the course
7. Platform - Platform offering the course (e.g., Udemy, Coursera, etc.)
8. Price ($) - Price of the course in USD
9. Rating (out of 5) - Average rating of the course

 Analysis Performed
- Descriptive Statistics: Summary of key metrics including enrollment, price, and ratings.  
- Distribution Checks: Normality tested using Shapiro-Wilk test.  
- Comparisons: Completion rates, prices, and enrollments compared across categories and platforms.  
- Statistical Testing: 
  - T-tests, Mann–Whitney U tests for group comparisons.  
  - ANOVA for category-wise differences.  
  - Correlation tests for numerical relationships.  
  - Chi-square and proportion z-tests for categorical proportions.  
- Visualizations: Bar charts, pie/donut charts, treemaps, heatmaps to represent trends.  

 General Findings
- Enrollment, pricing, and duration across categories and platforms appear fairly uniform.  
- Completion rates are generally low, which may reflect engagement challenges in online courses.  
- Ratings across platforms and categories show limited variation.  

 Disclaimer
This dataset appears to be synthetic/curated for educational purposes. 
The uniformity in enrollments, pricing, and durations suggests it may not be raw real-world data.  
As such, insights derived should be viewed as illustrative rather than reflective of actual market trends.

---
Prepared as part of exploratory data analysis and hypothesis testing project.
