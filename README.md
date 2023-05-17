# project1_team5
# Electric Cars Industry
Repository for project 1 Data Analytics Bootcamp

## Introduction 
The objective of this project is to conduct an general analysis of data from the electric car industry to identify patterns or trends that can help any customer that want to by an electric car. The data is limited to low-cost electric vehicles in the UK and Germany. 

## Sources 

The electric car information on https://ev-database.org/ was scraped and made available in comma separated list format in the following source: https://www.kaggle.com/datasets/kkhandekar/cheapest-electric-cars?resource=download

## Process
- Once we had downloaded the database we were sure we could work with, we started to clean the data in Jupyter Notebook as a team. This code was uploaded to a shared Github repository which contains all the necessary information about the project and some folders that includes the individual work done by each member of the team (visualizations).

### Database Cleaning
- Separation of list data into columns
- Extract the first word from 'Model' column and create a new one with that word in the new column named 'Manufacturer'
- Removed unecessary values
- Removed currency symbols to have have number format
- Rename some colums 
![image](https://github.com/juanreyes97/project1_team5/assets/127918227/4c3d742c-b28f-4454-afd0-320e3e8d9a73)
![image](https://github.com/juanreyes97/project1_team5/assets/127918227/8ef98fda-62f3-46ff-8609-7fceffdedaa6)

## Collaboration/Team work
- Since the database did not have information about sales, but focused more on performance, cost and other characteristics of the models, we took the initiative to create different approaches for the analysis. That is, Juan combined some characteristics to obtain a rating and in this way make comparisons and obtain some graphs; Oswaldo made a more general approach taking the total information without creating any kind of rating and based more on the performance and quantities of various characteristics; and finally, Fernando created a comparative focused on costs for both Germany and the UK. 

- You can see the visualizations at: **Project1_ECar_Industry.pptx**

## Conclusion:
- We were able to obtain very valuable information with which we can continue working in a more personalized way depending on the needs we are looking for in the market. At the same time, we realized that there is a wide variety of manufacturers and models to choose from. In case someone would like to perform this type of analysis, I believe it would be feasible to keep checking the market constantly because the automotive chip crisis may start to improve, which would lead to a greater stock of products and, consequently, prices may suffer a change. But at this moment we believe that we obtained a satisfactory result and gave us a great perspective of how the market is currently working.
