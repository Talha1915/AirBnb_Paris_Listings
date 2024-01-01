# AirBnb_Paris_Listings
Impact of 2015 regulations on AirBnb listings in Paris

## Situation 
#### As AIRBNB is growing in popularity, it is increasingly become the focus of regulations designed to limit the number of properties listed in each city. I analyzed Paris listings with a focus on pricing. Stakeholders want a visual summary of factors affecting price and whether regulations adopted in 2015 impacted listings in the Paris market. I used Jupyter Notebook for the case study.
I completed and answered the following questions to get the data insights.
#### Objective 1: Profile & QA the data
#### The first objective is to read in the AirBnB listings data, calculate basic profiling metrics, change column datatypes as necessary, and filter down to only Paris Listings.
##### 1. Import/Open the Listings.csv file
##### 2. Cast any date columns as a datetime format
##### 3. Filter the data down to rows where the city is Paris, and keep only the columns ‘host_since’, ‘neighbourhood’, ‘city’, ‘accommodates’, and ‘price’
##### 4. QA the Paris listings data: check for missing values, and calculate the minimum, maximum, and average for each numeric field
#### Objective 2: Prepare the data for visualization
#### Your second objective is to produce DataFrames that will be used in visualizations by aggregating and manipulating the listings data in several ways.
##### 1. Create a table named paris_listings_neighbourhood that groups Paris listings by 'neighbourhood' and calculates the mean price (sorted low to high).
##### 2. Create a table named paris_listings_accomodations, filter down to the most expensive neighborhood, group by the ‘accommodations’ column, and add the mean price for each value of ‘accommodates’ (sorted low to high)
##### 3. Create a table called paris_listings_over_time grouped by the ‘host_since’ year, and calculate the average price and count of rows representing the number of new hosts
#### OBJECTIVE 3: Visualize the data and summarize findings
#### Your final objective is to build visuals to show the number of new hosts by year, overall average price by year and neighborhood, and average price for various types of listings in Paris' most expensive neighborhood.
##### 1. Create a horizontal bar chart of the average price by neighborhood in Paris, and make sure to add a title and change axis labels as needed.
##### 2. Create a horizontal bar chart of the average price by ‘accommodates’ in Paris’ most expensive neighborhood, and make sure to add a title and change axis labels as needed.
##### 3. Create two line charts: one showing the count of new hosts over time, and one showing average price. Set the y-axis limit to 0, add a title, and change axis labels as needed.
##### 4. Create a dual axis line chart to show both new hosts and average price over time.
