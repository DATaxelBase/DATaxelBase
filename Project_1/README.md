👋 Hello everybody, </br>
*So let's start analysis on :taxi: `NYC Taxi Trip Duration `:taxi:*
Let's follow the plan :point_down:
## Project Steps
1. [Problem Definition](#problem-definition)
2. [Hypothesis Generation](#hypothesis-generation)
3. [Data Extraction](#data-extraction)
4. [Data Exploration and Transformation](#data-exploration-and-transformation)
5. [Predictive Modeling](#predictive-modeling)
---

## Problem Definition
We want to predict the total ride duration of taxi trips in New York City.</br>
<p align = "center"> <img  src = "https://media.istockphoto.com/id/518657226/fr/photo/les-taxis-sur-7th-avenue-at-times-square-new-york-city.jpg?s=612x612&w=0&k=20&c=QFtPEFxdprKsybWaYPYmMbogJx3svfMnuOQ67NBtUSA=" alt = "New York City Taxi">
</p>

Taxi company wants us to predict the duration of each trip at the point when the trip start. Now , why would NYC taxi company be interested in this? Because this help them plan their fleet in a much better manner. 


## Hypothesis Generation
*:thinking: What factors could impact Taxi trip?*
Let's separate context on:
- Environment
> Does the condition of the road affect the duration of the trip?</br>Does the weather affect the duration of trip?</br>Is the trip faster at night or during the day?

- Demographic
> Does the size of population groups in neighborhood affect the duration trip?

- Customer
> Does the number of passengers affect the duration trip? </br>Does the destination of passengers affect the taxi duration trip?</br>Does the distance between locations affect duration trip?

- Others
> Does the traffic at certain hours of day affect the duration trip?
[Back to plan](#project-steps)
---
## Data Extraction
The data of this project were provided into the Analytic Vidhya Machine Learning course. But you could find similar dataset on Kaggle or any other source. You will find in folder the dataset used.

## Data Exploration and Transformation
See notebook in repository :notebook:. 

---
### Predictive Modeling
See this part in NYC_Trip_Modeling notebook 📓. 
