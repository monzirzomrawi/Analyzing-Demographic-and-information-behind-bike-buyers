# Analyzing-Demographic-and-information-behind-bike-buyers

# Scenario

In this project, I will create Charts and Dashboards in Microsoft Excel using demographic and information behind bike buyers. I will use PivotTables to look at discrete trends in the data, which I will then represent as graphs. Towards the end of the project, I will summarize the bike buyers data creating a dashboard composed of the different graphs to provide a global picture of the data that can help design marketing strategies.

# Cleaning the Data

- The dataset consists of 1026 rows and 13 columns

- I added a filter to each column so that I can better understand the data.

- I found that there were 26 duplicates in the "ID" column, and I deleted them.

- The "Martial Status" column has two categories M and S. I replaced them with Married and Single, so they can easily be understood when creating graphs.

![Screenshot (49)](https://github.com/monzirzomrawi/Analyzing-Demographic-and-information-behind-bike-buyers/assets/172976501/2e52490f-c4b2-45fd-9984-482701258bc9)

- The "Gender" column has two categories M and F . I replaced them with Male and Female

  - I checked that the "Income" column is formatted as currency
 
  - In the "Age" column, there are many ages, so I changed the age column into categories by adding a new column named "Age_categories" so that the visualization will be easier to understand . I used this formula.
=IF(L4>54, "Old", IF(L4>=31,"Middle_age", "Adolescent"))

![Screenshot (54)](https://github.com/monzirzomrawi/Analyzing-Demographic-and-information-behind-bike-buyers/assets/172976501/86168c71-c392-4802-9edd-cb8ef8fc9a31)

Now, the data is ready for analysis.



# Analyzing and Visualizing the data

I utilized pivot tables to effectively analyse and visualise my data.

- I computed the average income for female and male who bought and didn't buy the bikes.

![Screenshot (61)](https://github.com/monzirzomrawi/Analyzing-Demographic-and-information-behind-bike-buyers/assets/172976501/78deb220-bda8-42ee-bb0f-b4397e6e2ae2)
 
Men make more money than women.

The people who bought the bike make more money than those who didn't. 

- I created a graph displaying the number of purchased bikes by commuting distance.

![Screenshot (62)](https://github.com/monzirzomrawi/Analyzing-Demographic-and-information-behind-bike-buyers/assets/172976501/fcd650d3-b514-4671-ad9d-115fbcfe9836)
 
The people who commute 0-1 and 2-5 purchased more bikes.

- I created a graph displaying the number of purchased bikes by age categories.

![Screenshot (74)](https://github.com/monzirzomrawi/Analyzing-Demographic-and-information-behind-bike-buyers/assets/172976501/71850764-dc02-4263-bbdb-f0cc5a84d8c3)

Middle aged people purchased more bikes.

- Now, I created the dashboard and inserted slicers to filter it.

![Screenshot (63)](https://github.com/monzirzomrawi/Analyzing-Demographic-and-information-behind-bike-buyers/assets/172976501/70d9b083-fc56-44e2-99cf-fd9ebdcba0a5)

 







