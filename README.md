# Micah-Citi-Bike

A data science project using SQL for Data Visualization, Data Analysis, and Data Science Using Google Cloud Platform to visualize New York Citi Bike Statistics

![319946027_833657294564915_1498816948370156560_n](https://github.com/pimicah/Micah-Citi-Bike/assets/144563378/983e1783-8092-4520-95ae-5b12d3d73631)

## __1.0 Business Problem__
With a sudden boom in alternative quick and easy transportation taking off in the early 2010's, New York's Citi bike became the premium go to option for New York residents.  Officially opening in May 2013 Citi Bike made a splash starting with 332 stations and 6,000 bikes across the Bronx, Brooklyn, Manhattan, and Queens, as well as Jersey City and Hoboken, New Jersey.  By October 2017 annual expansions brought the totals to 706 stations and 12,000 bikes, making the service the largest bike sharing program in the United States. Further expansions for Citi Bike are planned to extend its service area across the Bronx, Brooklyn, Manhattan, and Queens, and increase the number of bikes to 40,000.  

By visualizing statistical data, more effective business decisions can be made through transparency of information.  Decisions about expansion can be made by identifying the most popular bikes, collecting user information, and popular start locations.

## 2.0 Business Assumptions
The strategy to have greater transparency on Citi Bike hotspots and needs can help Citi Bike efficiently grow.

## 3.0 Solution Strategy
My solution to solve this problem will be the development of a data science project.  This project will have a variety of interactive data delivery devices.  
### Step 01. Data Description: 
In this first section data provided by Google Big Query will be aggregated and studied.  
### Step 02. Feature Engineering: 
In this section, a mind map will be created to assist the creation of the hypothesis and the creation of new features. These assumptions will help in exploratory data analysis and may improve the model scores.
### Step 03. Data Filtering: 
The following will be aggregated into columns within the table: date will be the converted start time, the number of trips will be the total number of trips for the date, the toal duration minutes will be the total sum of all the trip durations converted to minutes and rounded to two decimals place, and lastly the number of bikes will be the distinct count of bikes used for the date.
### Step 04. Feature Selection:
Three more aggregates will be prepared prior to construction of the visualization, all with a date dimension.  
### Step 05. Conclusion:
This is a conclusion stage which the generation capacity model is tested using unseen data. In addition, some business questions are answered to show the applicability of the model in the business context.
![Screenshot 2023-09-16 at 1 35 05 PM](https://github.com/pimicah/Micah-Citi-Bike-Dashboard/assets/144563378/534000f0-988f-487b-a7cc-cdd85f32de6e)

## 4.0 Top 2 Data Insights
- #### When comparing the average bike trip duration, subscribers have shorter bike trips than subscribers. In all of 2015, the female customers duration is nearly 2/3 double the subscribers and for males nearly 20% more.  There are numerous explanations, one could be that the customers are tourists and site seeing on bikes rather than going straight to their destination 
![Screenshot 2023-09-16 at 1 35 24 PM](https://github.com/pimicah/Micah-Citi-Bike-Dashboard/assets/144563378/5e12db5c-0d78-48f2-b653-d3e75bb1e83f)
- #### The top three most used start sites are located in Manhattan.  Unsurpisingly the hotspots are located in very populated areas. Vanderbilt Ave & E 42nd St located near the Empire State Building and Bryant park, 8 Av/W 31 St next to Madison Square Garden, and Mobile 1 near the Financial district.
- ![Screenshot 2023-09-16 at 2 01 54 PM](https://github.com/pimicah/Micah-Citi-Bike-Dashboard/assets/144563378/7b3d9849-d4eb-46b0-90c2-1846fdf885b5)

## 5.0 Business Results
