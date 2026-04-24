# france choropleth map with plotly
# cmse_402_honors
This repository contains a tutorial for how to make an interactive choropleth map with plotly for specific regions, states, counties, or more in a different country that is not the United States. The tutorial can be accessed through the Jupyter notebook file named 'choropleth_tutorial.ipynb'. This tutorial focuses on France regional data, but the same techniques can be applied to many places in the world through changing the location of the .geojson file used. The data used for the choropleth shading is from the 'patient.csv' file contained in the repository, which contains the COVID cases reported in French regions in early 2020. This specific choropleth map does not update based on a time scale (i.e. year or month). For interactivity, it lists the region being hovered over and the amount of cases in that region. The final result obtained from the tutorial was saved as an html file, 'France_Choropleth.html', and is also accessible within the repository. 
- Data used: https://www.kaggle.com/datasets/lperez/coronavirus-france-dataset 
- This data was sourced from the Regional Health Agencies of France.
- Geojson files for multiple countries, continents, states, cities, counties, and more can be found in this public repository:
  https://github.com/codeforgermany/click_that_hood/tree/main/public/data
- Specific France Region file used: https://github.com/codeforgermany/click_that_hood/blob/main/public/data/france-regions.geojson 
