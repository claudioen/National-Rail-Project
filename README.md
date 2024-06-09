# National-Rail-Project
Project delving into NationalRail's data – uncovering key insights into train operations in England, Scotland, and Wales.

## Table of Contents
1. Introduction
2. Objectives
3. Data Description
4. Methodology
5. Analysis and Results
6. Conclusion
7. Future Work
8. Requirements
9. Usage
10. Project Structure
11. Contributing
11. License
12. Acknowledgements


### Introduction
Project delving into NationalRail's data – uncovering key insights into train operations in England, Scotland, and Wales.

### Objectives
1. Discovering busy routes 🛤️
2. Pinpointing peak travel times ⏰
3. Analyzing ticket revenues 💰
4. Assessing on-time performance ⏱️

### Data Description
1. The data that was provided was fairly clean but not complete and needed some minor tweaks.
The only thing that is missing from the data was the coordinates of the different railway stations. Therefore, I went to search for it and got this website: https://github.com/ellcom/UK-Train-Station-Locations/blob/master/uk-train-stations.csv
I adjusted the reason for delay "Weather Conditions" to just "Weather"
I created a route column (departure location - arrival location), and multiple time tables to calculate time related metrics.
I scraped the web using OpenStreetMap API to get the route coordinates (best route) of the different routes for the route map visual.
