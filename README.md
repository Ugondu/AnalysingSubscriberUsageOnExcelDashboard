# “Social Buzz” Customer usage Analysis.
*![image](https://github.com/Ugondu/SocialBuzzCustomerAnalysisUsingExcel/assets/113315492/24cf6d33-1d28-49ee-b498-b0360ddc0a7d)*
## Table of Contents.
- [Business Overview](#business-overview)
- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Data Processing](#data-processing)
- [Insights and Findings](#insights-and-findings)
- [Conclusion and Recommendation](#conclusion-and-recommendation)
## Business Overview.
“Social Buzz”, a social media company founded in 2008 with over 500 million active subscribers has evolved social media contents by keeping it users anonymous. The social media network emphasizes on the use of specific reactions rather than traditional likes, dislikes, and comments on a trending content on its platform. 
Over the past 5 years, they have scaled quicker than anticipated and need advisory firm to oversee its scaling process effectively.  Their rapid growth and digital nature have required that over 100,000 pieces of contents ranging from text, images, videos, and GIFs are posted on its platform.
The company is looking to understand the content category with highest popularity, the number of active users, and the most used reaction and category used by its subscribers.
## Project Objective. 
The aim of the project is to demonstrate the activity of Social Buzz subscribers on a PowerBi dashboard to help influence key business decisions by its leaders.
To achieve the business objectives.
1.	Examine the dataset for inconsistences, missing values, duplicates, and incorrect data type.
2.	Define the columns that are relevant to the analysis.
3.	Explore and merge the columns using the reaction table as the base of our data model.
4.	Figure out the top 5 categories with the largest popularity as discussed in the business brief.
## Data Sources.
The datasets were made available by Accenture group.
### Customer data features:
* Content ID: Unique identifier given to each content entry by each subscriber. 
* Type: Reaction type by each subscriber on each content. 
* DateTime: Date for each content entry.
* ContentType: The type of content by each subscriber.
* Category: The category of each content on the platform.
* Sentiment: Shows if a reaction is positive, negative, or neutral
* Score: The value assigned to each sentiment.
## Data Cleaning.
* Removing negative values: The negative values in “Quantity” and “Unit Price” columns were filtered and removed so no value is less than 1 and $0 respectively.
* Removing columns: “Customer ID”, “url” columns were removed from the dataset as they are not relevant to our analysis.
* Missing Values: The blank fields were removed from the dataset
* Duplicates: Duplicates values were removed from the dataset
## Insights and Findings.
* From the analysis, the top 5 most popular categories were animals, science, healthy eating, technology, and food in descending order.
* Animals had an aggregate popularity score of 74965. Food and healthy eating are in the top 5, showing that food is a highly engaging content category.
* Healthy eating ranks slightly higher than food, perhaps most subscribers are skewed towards healthy eating and health conscious.
* The pie chart shows % split of popularity between the top 5 categories. We observed there is not much difference between each category. 
## Conclusion and Recommendations
This showcases the effectiveness of visualisation tools in providing useful insights in business decisions. We are able to demonstrate that users of the platform like “real-life” and “factual” content as seen in the popularity of animals and science. In addition, food and healthy eating were popular with the subscribers. 
We recommend that the company could run a campaign with content focused on the popular categories to promote such brands.  

