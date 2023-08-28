# Global YouTube Statistic Dataset Documentation

Name: Isaac Kobby Anni

Program: Data Science

Department: Computer Science


## Introduction

The "Global YouTube Statistic" dataset offers a comprehensive look into the world of YouTube stardom, providing statistics for some of the most subscribed YouTube channels. This meticulously curated dataset presents an opportunity to explore and gain insights from the leading creators on the platform. With detailed information on subscriber counts, video views, upload frequency, country of origin, earnings, and more, this dataset is a valuable resource for aspiring content creators, data enthusiasts, and anyone interested in the ever-evolving online content landscape.

### Dataset Information

- **Dataset Name**: Global YouTube Statistic
- **Dataset Source**: [Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023)
- **Dataset Size**: 995 rows and 28 columns

## Features

1. **rank**: The ranking of the YouTube channel.
2. **Youtuber**: The name of the YouTube channel.
3. **subscribers**: The number of subscribers to the channel.
4. **video views**: The total number of video views on the channel.
5. **category**: The category to which the channel belongs.
6. **Title**: The title or name of the YouTube video.
7. **uploads**: The number of video uploads on the channel.
8. **Country**: The country of origin of the YouTube channel.
9. **Abbreviation**: The country abbreviation.
10. **channel_type**: The type or category of the YouTube channel.
11. **video_views_rank**: The ranking of video views for the channel.
12. **country_rank**: The ranking of the channel within its country of origin.
13. **channel_type_rank**: The ranking of the channel within its category.
14. **video_views_for_the_last_30_days**: The total video views in the last 30 days.
15. **lowest_monthly_earnings**: The lowest monthly earnings of the channel.
16. **highest_monthly_earnings**: The highest monthly earnings of the channel.
17. **lowest_yearly_earnings**: The lowest yearly earnings of the channel.
18. **highest_yearly_earnings**: The highest yearly earnings of the channel.
19. **subscribers_for_last_30_days**: The number of subscribers gained in the last 30 days.
20. **created_year**: The year when the channel was created.
21. **created_month**: The month when the channel was created.
22. **created_date**: The exact date of channel creation.
23. **Gross tertiary education enrollment (%)**: Gross tertiary education enrollment percentage in the channel's country.
24. **Population**: The population of the channel's country.
25. **Unemployment rate**: The unemployment rate in the channel's country.
26. **Urban_population**: The urban population in the channel's country.
27. **Latitude**: The latitude coordinate of the channel's country.
28. **Longitude**: The longitude coordinate of the channel's country.

## Potential Use Cases

The Global YouTube Statistic dataset can be used for various analytical and research purposes, including:

1. **YouTube Channel Analysis**: Analyzing the subscriber counts, video views, and earnings of top YouTube channels.
2. **Content Strategy**: Identifying trends and insights to optimize content creation strategies.
3. **Geographical Analysis**: Exploring the distribution of YouTube channels and their characteristics by country.
4. **Economic Insights**: Investigating the relationship between YouTube success and economic indicators like unemployment rates and education enrollment.
5. **Content Creator Research**: Studying the growth patterns and strategies of successful content creators.

## Data Quality and Considerations

- Data quality is essential when working with this dataset. Ensure you understand the data source and any data cleaning or preprocessing steps that may be required.
- Missing data: Check for missing values in the dataset and decide on an appropriate strategy for handling them.
- Outliers: Be aware of outliers in numerical columns that may affect your analysis.
- Data exploration: Explore the data to identify interesting patterns and correlations.



## How to read in data
- Link: [https://docs.google.com/spreadsheets/d/e/2PACX-1vQHCxrtIVViKsYA1SsmpBaW3ovW369ku5IjIIgcAmRROKAnTQWrqNROhT6m6E2Hyi74XJvYtw22MpQ8/pub?output=csv](https://docs.google.com/spreadsheets/d/e/2PACX-1vQHCxrtIVViKsYA1SsmpBaW3ovW369ku5IjIIgcAmRROKAnTQWrqNROhT6m6E2Hyi74XJvYtw22MpQ8/pub?output=csv)


```R
### R

data <- read.csv("https://docs.google.com/spreadsheets/d/e/2PACX-1vQHCxrtIVViKsYA1SsmpBaW3ovW369ku5IjIIgcAmRROKAnTQWrqNROhT6m6E2Hyi74XJvYtw22MpQ8/pub?output=csv")
head(data)
```


```python
### Python

import pandas as pd
df = pd.read_csv("https://docs.google.com/spreadsheets/d/e/2PACX-1vQHCxrtIVViKsYA1SsmpBaW3ovW369ku5IjIIgcAmRROKAnTQWrqNROhT6m6E2Hyi74XJvYtw22MpQ8/pub?output=csv")
df.head() 
```

## Citation

- Dataset Source: "Global YouTube Statistic" on Kaggle (URL: [https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023](https://www.kaggle.com/datasets/nelgiriyewithana/global-youtube-statistics-2023))