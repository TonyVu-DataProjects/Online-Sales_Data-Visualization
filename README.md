# Online Office Department Store Sales - Data Visualization

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Installation](#installation)
- [Methodology](#methodology)
- [Visualizations](#visualizations)
- [Conclusions](#conclusions)
- [Future Work](#future-work)
- [License](#license)
- [Contact](#contact)

## Overview
The aim of this project is to visualize the online sales dataset and uncover the insights regarding: 
  1. How well the online sales do in each state and across categories?
  2. How does each region compared to others in term of profit ratio and is there a trend across ship modes and sub-categories?   

## Dataset
Provide details about the dataset(s) used in the project.
- **Source**: Conestoga college learning material.
- **Description**: The dataset contains data about online sales records of an office department store. Key features include Order Date, Profit, and Category. 
- **Preprocessing**: The data has been cleaned and ready for visualizations.

## Installation
Instructions for setting up the project locally. 

### Prerequisites
List any software, libraries, or tools required to run the project.
- [Tableau Desktop](https://www.tableau.com/products/desktop)

### Setup
Steps to install the necessary packages and set up the environment.

```bash
# Clone the repository
git clone https://github.com/TonyVu-DataProjects/Online-Sales_Data-Visualization.git

or download zip file

# Navigate to the project directory
cd Online-Sales_Data-Visualization

# Access Dashboards locally
Install Tableau Desktop > Double click "Online_Sales_Dashboards.twbx" file
```
## Methodology
- Visualizations used: 
1. Choropleth map / Geographical map: used for geographical visualizing with Profit Ratio demonstrated by size of a pie chart which is split across Segments.  
3. Text highlighted table: used for displaying the minimum and maximum profit ratio values across each Sub-Category and Ship Mode.
4. Heat map: used for displaying the extent of values of each subcategory in any Month of Order Date (Jan - Dec). Dimensions used to demonstrate the extent of values are size and color. Attributes being tracked include Sales and Profit Ratio. 

## Visualizations
- Tableau public link: [https://public.tableau.com/app/profile/tony.k.vu/viz/Online_Sales_Dashboards/OnlineSalesStory](https://public.tableau.com/app/profile/tony.k.vu/viz/Online_Sales_Dashboards/OnlineSalesStory)

## Conclusions
**Insights from visualizations:**
1. Ohio has the lowest profit ratio while District of Columbia has the highest profit ratio. 
2. The West Region have relatively higher profit ratio in the office supplies category across all ship modes.  
3. Tables has consistently lower profit ratio throughout the year.
4. Q4 has higher sales compared to other quarters. January and February have lowest sales among all months.

## Future Work
- Enhancements: 
1. Includes data from other data sources (e.g: average income by states, competitor exposures)
2. Includes correlated charting to visualize the correlation between:  
    a. Income and profit ratio.  
    b. Level of competition and profit ratio

- Further Analysis:
1. How does average income of a certain state affect the profit ratio for that state?
2. How does competition intensity affect the profit margin?  

## License
- MIT License

## Contact
- Name: Tony Vu
- Email: [tonyknvu1@gmail.com](mailto:tonyknvu1@gmail.com)
- LinkedIn: [linkedin.com/in/tonyknvu](https://www.linkedin.com/in/tonyknvu/)
