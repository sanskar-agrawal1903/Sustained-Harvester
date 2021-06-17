# Sustained-Harvester



## MOTIVATION
Today, one of the major problem our environment is facing is that, though many people want to grow plants around them, but rare of those plants survive.
As there are various natural as well as synthetic factors affecting behind the growth . 
So to overcome this problem our project is suggesting strategic ways while cultivation.


## FUNCTIONALITY COVERED 
1) First functionality of this project is Crop Prediction.
In the study we have find that the sustainability of plant mostly depends on temperature and humidity of environment and the amount of nitrogen Phosphorus and potassium in the soil.

Therefore we will be taking name of states and city for temperature and humidity and amount of nitrogen Phosphorus potassium and then the crop prediction model will find which plant will be most suitable to grow in that particular area.

 we will use a random forest for the production

2)Second model is based on Fertilization Prediction. 
In this we are entering the amount of nitrogen, phosphorus and potassium present in our soil, and hence suggesting the best fertiliser for the aimed plant. 

Beside from this, it also guide the water requirement for any particular plant, provide do's and don'ts need to be kept in mind and other influencing factors.

3) The third model takes the picture of a plant and identify  the disease the plant have.  

Apart from this, it also predict it's cure .

Since a better planning results in better outcomes. So , is the case while cultivating plants. Strategic cultivation will not only lead us to better growth of a plant but also to well managed and sustained ecosystem. As it will cutdown the resources consumption by a plant in every aspect and hence will improve the ecological balance at a great extent. 

## DATA SOURCE
- [Crop recommendation dataset ](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset) (custom built dataset)
- [Fertilizer suggestion dataset](https://github.com/Gladiator07/Harvestify/blob/master/Data-processed/fertilizer.csv) (custom built dataset)
- [Disease detection dataset](https://www.kaggle.com/vipoooool/new-plant-diseases-dataset)

## Notebooks 
##### I have also published the corresponding code on Kaggle Notebooks.
- [Crop Recommendation](https://www.kaggle.com/atharvaingle/what-crop-to-grow)
- [Disease Detection](https://www.kaggle.com/atharvaingle/plant-disease-classification-resnet-99-2)



## DEPLOYMENT

#### Deployment is done using [deploy](https://github.com/Gladiator07/Harvestify/tree/deploy) branch
#### This website is deployed at [Heroku](https://www.heroku.com/)
#### You can access it [here](https://harvestify.herokuapp.com/)
#### Note: The website may take a minute to load sometimes, as the server may be in hibernate state

## How to use
- Crop Recommendation system ==> enter the corresponding nutrient values of your soil, state and city. Note that, the N-P-K (Nitrogen-Phosphorous-Pottasium) values to be entered should be the ratio between them. Refer [this website](https://www.gardeningknowhow.com/garden-how-to/soil-fertilizers/fertilizer-numbers-npk.htm) for more information.
Note: When you enter the city name, make sure to enter mostly common city names. Remote cities/towns may not be available in the [Weather API](https://openweathermap.org/) from where humidity, temperature data is fetched.

- Fertilizer suggestion system ==> Enter the nutrient contents of your soil and the crop you want to grow. The algorithm will tell which nutrient the soil has excess of or lacks. Accordingly, it will give suggestions for buying fertilizers.

- Disease Detection System ==> Upload an image of leaf of your plant. The algorithm will tell the crop type and whether it is diseased or healthy. If it is diseased, it will tell you the cause of the disease and suggest you how to prevent/cure the disease accordingly.
Note that, for now it only supports following crops

<details>
  <summary>Supported crops by our project
</summary>

- Apple
- Blueberry
- Cherry
- Corn
- Grape
- Pepper
- Orange
- Peach
- Potato
- Soybean
- Strawberry
- Tomato
- Squash
- Raspberry
</details>


## DEMO
https://github.com/sanskar-agrawal1903/Sustained-Harvester






