# cmse_402_honors
- Data used: https://www.kaggle.com/datasets/lperez/coronavirus-france-dataset (** get new data or rename counties)
- This data was sourced from the Regional Health Agencies of France
- Geojson files for multiple countries, continents, states, cities, counties, and more can be found in this public repository:
  https://github.com/codeforgermany/click_that_hood/tree/main/public/data
- France Region file: https://github.com/codeforgermany/click_that_hood/blob/main/public/data/france-regions.geojson 
- Gap filled: Plotly contains limited documentation or examples for chloropleth maps outside of countries in the world and the United States. It also only has built in built-in geometries for US States and countries. I am creating example documentation for making Plotly chloropleth maps outside of these. I have chosen France as my example country, but this tutorial format can be applied to any other country in the world, as long as it has a geojson file associated with it. 