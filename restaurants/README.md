## Maven Analytics challenge: #mavenrestaurantchallenge 💰

# Disclaimer
This is a work in progress. Do not consider this project done yet

### Summary

>For the Maven Restaurant Challenge, you will be assuming the role of Lead Analyst at a firm that invests in new restaurant opportunities abroad. After conducting a study to learn about the restaurant market in several Mexican cities, you've been asked to analyze interesting patterns and trends in the data to help understand the market and make investment decisions.

>Your task is to share a single-page visual or dashboard that outlines what you'd be looking for in a restaurant to invest in and contains the supporting data from your analysis. [full details of the challenge](https://www.mavenanalytics.io/blog/maven-restaurant-challenge).
- Visualization type: **`report`**

<div class="img-left"><img src="https://image.freepik.com/vector-gratis/ilustracion-concepto-abstracto-critico-alimentos-analizar-comida-chef-restaurante-escribir-resena-calificacion-opinion-experto-espectaculo-culinario-invitado-encubierto-guia-viaje_335657-3512.jpg" width="400"></div>

### Questions to answer

- What type of demographics should we target?
- What service variables correlate best with a high service rating?
- What food type do low, medium and high budget customers that are generally satisfied with the food prefer?
- Does smoking allowance correlate with a low service rating?
- Are there low budget consumers that prefer a high budget restaurant?
- Is food percieved best if a restaurant is not a franchise?
- Do drinkers and smokers feel most at ease with drink and smoking allowance?

### Data nuances
Even though a thorough analysis will be conducted and conclusions will be made for the sake of practice, this dataset has a non representative sample size and does not ensure data is not biased since collection methods are not specified. For that reason, no investment strategies should be suggested by this data alone and additional information should be collected in order to ensure solid data driven investment decisions.

### Techniques applied

#### Visualization

#### Other

### Results


[Link to Tableau viz](https://public.tableau.com/app/profile/gonzalo3304/viz/Book1_16298609616200/age)

[Link to PDF]()

#### Conclusions

##### Suggested investment strategy

### Data description

Dataset has been provided by [Maven Analytics](https://www.mavenanalytics.io/data-playground). It contains 5 files: `consumer_preferences.csv`, `ratings.csv`, `restaurant_cuisines.csv`, `consumers.csv` and `restaurants.csv`. The parameters included are:

### consumer_preferences.csv
> - **`Consumer_ID`**: Identification number of the customer. (categorical)
> - **`Preferred_Cuisine`**: Customer's preferred cuisine. (categorical)

### ratings.csv
> - **`Consumer_ID`**: Identification number of the customer. (categorical)
> - **`Restaurant_ID`**: Identification number of the restaurant. (categorical)
> - **`Overall Rating`**: Overall rating the customer gives to the whole experience. (categorical)
> - **`Food Rating`**: Rating the customer gives to the food. (categorical)
> - **`Service Rating`**: Rating the customer gives to the service. (categorical)

### restaurant_cuisines.csv
> - **`Restaurant_ID`**: Identification number of the restaurant. (categorical)
> - **`Cuisine`**: Type of cuisine the restaurant serves. (numerical)

### consumers.csv
> - **`Consumer_ID`**: Identification number of the customer. (categorical)
> - **`City`**: Number of backers. (numerical)
> - **`State`**: City in which the review took place. (categorical)
> - **`Country`**: Country in which the review took place. (categorical)
> - **`Latitude`**: Latitude in which the review took place. (categorical)
> - **`Longitude`**: Longitude in which the review took place. (categorical)
> - **`Smoker`**: Wether the customer smokes or not. (categorical)
> - **`Drink Level`**: Frequency in which the customer drinks alcohol. (categorical)
> - **`Transportation Method`**: Customer's mean of transportation for that review. (categorical)
> - **`Marital Status`**: Marital status of the client. (categorical)
> - **`Children`**: Wether the client has kids or not. (categorical)
> - **`Age`**: Customer age. (numerical)
> - **`Occupation`**: Customer occupation status (student / employed / unemployed). (categorical)
> - **`Budget`**: Customer purchasing power segment. (categorical)

### restaurants.csv
> - **`Restaurant_ID`**: Identification number of the restaurant. (categorical)
> - **`Name`**: Name of the restaurant. (categorical)
> - **`City`**: City in which the restaurant is located. (categorical)
> - **`Smoking Allowed`**: Wether the restaurant allows or not smoking. (categorical)
> - **`Country`**: Country in which the restaurant is located. (categorical)
> - **`Zip Code`**: Current condition the project is in (as of 2018-01-02). (numerical)
> - **`Latitude`**: Latitude in which the restaurant is located. (categorical)
> - **`Longitude`**: Longitude in which the restaurant is located. (categorical)
> - **`Alcohol Service`**: Type of alcohol service (None / wine and beer / Full bar). (categorical)
> - **`Price`**: Restaurant price segment. (categorical)
> - **`Franchise`**: Wether the restaurant is from a franchise or not. (categorical)
> - **`Area`**: Wether the restaurant has an open area or not. (categorical)
> - **`Parking`**: Wether the restaurant has parking or not. (categorical)

### Relational Schema

![image](https://user-images.githubusercontent.com/52865532/132076974-c6b55497-f76a-44e6-a71b-62132c182372.png)
