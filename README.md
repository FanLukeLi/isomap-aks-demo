This project demonstrates some isochrone analysis or travel time analysis results. The algorithm I developed for this service is a product at my previous position, which is why it cannot be published. 
In this project, I deployed a slightly improved version of the product to Azure Kubernetes Service configuring 3 replica, based on an image I built with docker and registered to Azure Container Registry. 
Using Jupyter notebook, geopandas and folium, I created these maps
>>> Isochrones map from 6 Garda Stations located in the 40 electoral divisions with highest population density in Dublin, Ireland
>>> Isochrones map from 4 metro stations located in the 30 census tracts with highest population density in Washington DC, US
>>> Isochrones map from 6 rail stations located in the 2 SA2 (Statistical Area 2) areas with highest rail station count in Wellington, New Zealand -- well, these rail stations are not distributed in the most populated areas :)

Since the algorithm is a private product and there's a continuous cost on Azure, I quickly deleted the service. So the API's URL in the code is not effective. 
