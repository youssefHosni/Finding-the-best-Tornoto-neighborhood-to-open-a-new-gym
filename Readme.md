# Finding the best neighborhood to open a new gym

Finding the best neighborhood  to open a new gym, given the demographic and geogrpahic and venues information data.

### Data

The datasets used to solve these problem are as the following:
The demogrpahics data: The demographic dataset contains the total population, the 15-45 poulation, the number of educated people and the number of employers in each neighborhood. The dataset is downladed from the Toronta data portal. https://open.toronto.ca/dataset/neighbourhood-profiles/
The dataset look as the following after cleaning and preprocessing: 
![demogrpahics data](https://user-images.githubusercontent.com/72076328/109423870-ed451300-79e9-11eb-8089-b8ac372bf00a.PNG)
The graphical data (lat,long) for each neighborhood is used to get the venues information for each neighborhood from Foursquare API.
The Neighbourhood Crime Rates.csv is downloaded from the toronta open data portal. https://open.toronto.ca/dataset/neighbourhood-crime-rates/
The data is preprocessed by removing the unneeded part and convering it from strings into float. The data is then merged with the demogrphics data as shown in the figure below:
![demogrpahics _graaphical data](https://user-images.githubusercontent.com/72076328/109423972-5d539900-79ea-11eb-93b8-370b7f657a5f.PNG)
The neighbourhoods on the map are shown in the figure below
![neighborhood_map](https://user-images.githubusercontent.com/72076328/109424179-4bbec100-79eb-11eb-9a71-6557010e2ee3.PNG)
From the Foursquare API the number of venues per each neighbourhood and the number of Gym/Fitness centers per each neighbourhood were calculated and then merged with the demographics data and the final data used is as the shown in the figure below.
![total_data](https://user-images.githubusercontent.com/72076328/109424261-a9530d80-79eb-11eb-807c-49864647abc6.PNG)


## Dependices 

