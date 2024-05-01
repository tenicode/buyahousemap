## Project Name: i want to buy a house map

### Introduction:
This project showcases an interactive map visualization created using Jupyter Notebook. The project utilizes various Python libraries such as pandas, geopandas, and folium for data analysis and visualization.

### Data Sources:
- **Local Authority Boundaries:** The shapefile for local authority boundaries was obtained from [UK Government's Geoportal](https://geoportal.statistics.gov.uk).
- **Electric Vehicle Data:** Electric vehicle charging device statistics for January 2023 were sourced from [UK Government Statistics](https://www.gov.uk/government/statistics/electric-vehicle-charging-device-statistics-january-2023).
- **Mean House Price Data:** Mean house price data used to create the choropleth map was obtained from [Office for National Statistics (ONS)](https://www.ons.gov.uk/economy/inflationandpriceindices/bulletins/housepriceindex/december2023#:~:text=The%20average%20UK%20house%20price,to%20£190%2C000%20(3.3%25)).

### Data Analysis:
1. **Electric Vehicle Data Cleaning:** The electric vehicle data was cleaned to remove any inconsistencies and prepare it for analysis. The cleaned data can be found in the `data` folder of the project repository.
2. **Mean House Price Analysis:** Mean house price data was used to create a choropleth map, visualizing the variation in house prices across different local authorities in the UK.
3. **Interactive Map Visualization:** Using the cleaned electric vehicle data and the choropleth map of mean house prices, an interactive map visualization was created using folium.

### Folder Structure:
- `data`: Contains the cleaned electric vehicle data, and the other data used in this project

### Usage:
To run the project:
1. Clone the repository from GitHub.
2. Install the required Python libraries (`pandas`, `geopandas`, `folium`).
3. Open the Jupyter notebooks in the `data` folder and execute the cells.
4. Can also click on the 'iwanttobuyahousemap' for the HTML file.

### Conclusion:
This project demonstrates the use of data analysis and visualization techniques to explore relationships between different datasets. The interactive map visualization provides insights into electric vehicle distribution and house prices across various local authorities in the UK.

### Author:
Teni Balogun

### License:
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
