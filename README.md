# National-Rail-Project
Project delving into NationalRail's data – uncovering key insights into train operations in England, Scotland, and Wales.

## Table of Contents
1. Introduction
2. Objectives
3. Data Description
4. Analysis and Results
5. Conclusion
6. Future Work
7. Requirements
8. Project Structure
9. Acknowledgements


## Introduction
Project delving into NationalRail's data – uncovering key insights into train operations in England, Scotland, and Wales.

## Objectives
1. Discovering busy routes 🛤️
2. Pinpointing peak travel times ⏰
3. Analyzing ticket revenues 💰
4. Assessing on-time performance ⏱️

## Data Description
The dataset contains mock train ticket sales for National Rail in the UK, covering the period from January to April 2024. It includes detailed information on:
* Type of Ticket: The category of each ticket sold.
* Journey Date & Time: The specific date and time for each journey.
* Departure & Arrival Stations: The starting and ending points of each journey.
* Ticket Price: The cost of each ticket.
* Additional Details: Any other relevant information associated with the train ticket sales.
The dataset was initially fairly clean but incomplete, lacking the coordinates for various railway stations.
These coordinates were obtained from the following source: https://github.com/ellcom/UK-Train-Station-Locations/blob/master/uk-train-stations.csv

## Analysis and Results
https://github.com/claudioen/National-Rail-Project/blob/main/nationalrailproject_.png
1. Number of Journeys: A KPI displaying the total number of journeys.
2. Revenues: A KPI showing the total revenue generated.
3. Number of Delays: A KPI indicating the total number of delays.
4. Peak Travel Time: A line chart illustrating the time ranges (e.g., 18:00 - 19:00) with peak travel activity.
5. Most Popular Routes: A table listing the most frequently traveled routes.
6. Number of Delays by Reason: A horizontal histogram presenting the total number of delays categorized by their reasons, also indicating if a refund request was made by the customer.
7. Ticket Price by Route: A table detailing the ticket prices for each route, segmented by Ticket Class (First and Second Class) and Ticket Type (Advance, Anytime, and Off-Peak).
8. Visual Map: A visual representation of all the routes, providing a geographic overview of the train journeys.


## Conclusion
* Most Popular Route: The route from Manchester Piccadilly to Liverpool Lime Street is the most popular, with 90.06% of trains arriving on time. The distance between these stations is approximately 50.19 km.
* Peak Travel Times: Peak travel periods are observed between 06:00 - 07:00 and 18:00 - 19:00.
Revenue: National Rail earned approximately £1 million from train ticket sales over the four-month period.
* Most Punctual Route: The route from Liverpool Lime Street to Leeds, approximately 103 km long, is the most punctual, with no recorded delays. This conclusion is supported by the number of journeys made on this route.

## Future Work
* Enhanced Data Collection:
    - Environmental Data: Integrate weather and environmental data to better understand the impact on train delays and service disruptions.
* Predictive Analytics:
    - Delay Prediction: Develop predictive models to forecast train delays based on historical data and real-time factors.
* Route Optimization:
    - Efficiency Analysis: Analyze and optimize train schedules to reduce travel times and improve punctuality.

## Requirements
- Excel
- Power BI
- Python

## Acknowledgements
Thanks to Maven Analytics, for providing access to the dataset that was essential for this analysis.
