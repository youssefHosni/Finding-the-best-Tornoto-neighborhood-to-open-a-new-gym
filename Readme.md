### introduction 

A bussines man that owns a series of gyms/Fitness centers would like to expand his series to Toronto city in Canada he would like to know which neigborhoods in Tornotno city are the best to open a new Gym/Fitness center in it. So the main problem is finding the best neighborhood to open a new gym in Toronto city, Canda.
The best neighboorhood is the one that will lead to highest profit and more clinets when a new gym open in it. Therefore it will be important to find the neighboorhoods that have a vacant to open new gym and to be sure that in the same time it will be able to attract customers to it. So it will be important to study the deomographics of the neighboorhoods and to know which neighboorhod had the highest population and the percentage of youth in this population, level of education, and the percentage of employers. The propulation with these properties are more expected to use the gym more, therefore more profit. Also studing the veneus in each neighborhood as the more activites in the neighborhood the more it will attract customer to the gym/training center as there will be alot pf services in this area in addition to the gym to atttract customers. The number of gyms also are used as an important feature as it will be better to Focus on the neighborhoods that donot have gyms already existed in it. 
The analysis would be helpful also for any service that based on youth, such as cinemas, resturants, shoping mall but some modifications are required. The analysis would be also helpful to healtcare providers because the neighboorhods that are best for gym/training centers would be the least needed for hospitals.

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

