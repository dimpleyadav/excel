# Indian Airlines Customer Reviews Analysis

This dataset contains customer reviews for Indian Airlines, providing valuable insights into customer satisfaction, loyalty, and areas for improvement. The data is sourced from Skytrax website.

The dataset includes key features such as review text, ratings, dates, feedback, and recommendations. These data points can be used for various purposes, including customer satisfaction analysis, sentiment analysis, topic modeling, predictive modeling, and competitive analysis. The specific features and level of detail may vary depending on the sources and methods used to collect the data.

Tools used: Excel & Python

Data Cleaning:

Used FIND() AND MID() to extract the month names from date column and used RIGHT() to extract year.

Used Python library textblob for sentiment analysis.

Segregated the polarity values from the sentiment analysis into 3 categories: Negative(<-0.1), Neutral(<=0.1), Positive(>0.1)


1. Which airline has the highest average rating?

Vistara has the highest average rating, with a score of 6.88.

2. What trend do we see in the number of reviews over the years?

The number of reviews increased steadily from 2016, with a peak in 2023 at 550 reviews. There was a slight decline in 2024 to 290 reviews.

3. Which airlines are most recommended by customers?

Vistara and Indigo are the most recommended airlines, with a significantly higher number of "yes" recommendations compared to others.

4. How is customer sentiment distributed among positive, neutral, and negative reviews?

The sentiment distribution is as follows:

Positive: 39.14%

Neutral: 32.94%

Negative: 27.92%


![image](https://github.com/user-attachments/assets/c31d9a92-2ec8-4a2c-932e-268a6c88943d)
