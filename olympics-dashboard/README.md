## Maven Analytics challenge: #mavenolympicschallenge

Given a dataset with **271.116** athletes that participated into different Olympics editions **from Athens 1896 to Rio 2016**, I had to create a dashboard to capture the history of the Olympic Games. [full details of the challenge](https://www.mavenanalytics.io/blog/maven-olympics-challenge)

<div class="img-left"><img src="https://i.imgur.com/Vh35oZB.jpg" width="400"></div>

# Results

<img src="https://i.imgur.com/RfI1rhM.png" width=1000>

[Link to Tableau viz](https://public.tableau.com/app/profile/gonzalo3304/viz/Olympics_16264021893190/Dashboard_final)

[Link to PDF](https://drive.google.com/file/d/1anQkgX0dFgO7l5hu3n5KAOGlv7iXLW8n/view?usp=sharing)

---

# Data description

Dataset has been provided by [Maven Analytics](https://www.mavenanalytics.io/data-playground), it contains 2 files: `athlete_events.csv` and `country_definitions.csv`. The parameters included are:

### athlete_events.csv
> - **`ID`**: Unique number for each athlete. (categorical)
> - **`Name`**: Athlete's name. (categorical)
> - **`Sex`**: Male (M) or Female (F). (categorical)
> - **`Age`**: Athlete's age. (numerical)
> - **`Height`**: Athlete's height. (numerical)
> - **`Weight`**: Athlete's weight. (numerical)
> - **`Team`**: Team name. (categorical)
> - **`NOC`**: National Olympic Committee 3-letter code. (categorical)
> - **`Games`**: Year and season. (categorical)
> - **`Year`**: Year of the event. (numerical)
> - **`Season`**: Summer or Winter. (categorical)
> - **`City`**: Host city. (categorical)
> - **`Sport`**: Sport played. (categorical)
> - **`Event`**: Event played. (categorical)
> - **`Medal`**: Gold, Silver, Bronze, or NA. (categorical)

### country_definitions.csv
> - **`NOC`**: National Olympic Commitee 3 letter code. (categorical)
> - **`region`**: Country name. (categorical)
> - **`notes`**: Real country name if "Region" isn't an exact match. (categorical)
