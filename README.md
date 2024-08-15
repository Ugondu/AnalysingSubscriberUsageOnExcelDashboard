# Analysing Subscriber Usage on a Social Media Platform Using Excel Dashboard


![image](https://github.com/user-attachments/assets/3b030998-9287-4b9a-bf4c-917158d9eae7)



## Table of Contents
- [Business Overview](#business-overview)
- [Data Source](#data-source)
- [Development](#development)
  - [Data Cleaning](#data-cleaning)
  - [Data Modelling](#data-modelling)
- [Visualization](#visualization)
  - [Results](#results)
- [Analysis](#analysis)
  - [Findings](#findings)
  - [Insights](#insights)
- [Recommendation](#recommendation)


# Business Overview

“Social Buzz”, a social media company founded in 2008 with over 500 million active subscribers has evolved social media contents by keeping it users anonymous. The social media network emphasizes on the use of specific reactions rather than traditional likes, dislikes, and comments on a trending content on its platform. 
Over the past 5 years, they have scaled quicker than anticipated and need advisory firm to oversee its scaling process effectively.  Their rapid growth and digital nature have required that over 100,000 pieces of contents ranging from text, images, videos, and GIFs are posted on its platform.


- What is the pain point?

The company is looking to understand the content category with highest popularity, the number of active users, and the most used reaction and category used by its subscribers.

- What is the ideal solution on offer for the client?

Creating s visualization using Excel would be ideal for extensive understanding of the metrics required. The visualization would include;

- Top 10 reactions by popularity
- Top 5 popular categories by Score
- Category popularity by percentage
- Total number of active users
- Unique categories
- Month with highest number of post by subscribers


# Data Source

The dataset would include the following features;
- Content ID
- Type
- DateTime
- ContentType
- Category
- Sentiment
- Score

The dataset is made available in an Excel format and can be accessed here, [see here to find it](https://github.com/Ugondu/AnalysingSubscriberUsageOnExcelDashboard/blob/main/Assets/dataset/Cleaned_Data_Solution.csv)


# Development

- How best can we approach this and create a detailed analysis for the client?

1. Requirement gathering
2. Explore dataset using Excel
3. Clean and transform data using Excel functions
4. Visualize insights on Excel dashboard
5. Present findings to end user


## Data Cleaning

The cleaned data should meet the required criteria:

- All irrelevant columns are removed from the dataset
- No blanks and duplicates in the dataset
- All data types should be appropriate for the fields in each column

## Data Modelling

The reaction table served as the base table, relevant columns from content and reaction type dataset are joined using vlookup formula. 

# Visualization

## Results

The final dashboard will show the metrics vital to the providing solutions to the end user.

![image](https://github.com/user-attachments/assets/70de38d5-c80c-4e50-bec7-4cd1b5f7bbe1)

# Analysis

## Findings

#### 1. What is the Top 10 reactions by popularity

| Rank | Reactions              | Number of reactions    |
|------|------------------------|------------------------|
| 1    | Heart                  |   1622                 | 
| 2    | Scared                 |   1572                 |
| 3    | Peeking                |   1559                 |
| 4    | Hate                   |   1552                 |
| 5    | Intrested              |   1549                 |
| 6    | Adore                  |   1548                 | 
| 7    | Dislike                |   1548                 |
| 8    | want                   |   1539                 |
| 9    | Love                   |   1534                 |
| 10   | Disgust                |   1526                 |

#### 2. What is the top 5 popular categories by Score

| Rank | Reactions              | Number of reactions    |
|------|------------------------|------------------------|
| 1    | Animals                |   74965                | 
| 2    | Science                |   71168                |
| 3    | Health Eating          |   69339                |
| 4    | Technology             |   68738                |
| 5    | Food                   |   66676                |


## Insights

From the data made available, there are 16 unique categories of post which includes Food, science, animals etc. From the animal category, there were 1897 reactions from the users on Social Buzz showing connection of your users to nature.
January showed the highest number of active users which could be associated to seasonality obviously after christmas. 

Furthermore, detailed analysis show that categories such as animals, science, health eating, and food were very popular amongst your users. This shows that majority of active users on the platform are keen on healthy eating, interested in contents that are educative as seen in the posts on science and technology.

# Recommendation

Given the traffic generated by food and health eating enthusiasts, running a commerical with brands that focus on such content will boost the revenue and traffic on the platform positively.
