## Maven Analytics challenge: #mavencrowdfundingchallenge

### Summary
Given a dataset with over 375.000 projects uploaded to Kickstarter, had to analyze which factors may predict projects success. [full details of the challenge](https://www.mavenanalytics.io/blog/maven-crowdfunding-challenge?utm_source=linkedin&utm_campaign=mavencrowdfundingchallenge_li_maven).
- Visualization type: **`report`**

<div class="img-left"><img src="https://user-images.githubusercontent.com/52865532/129091636-c7faaeba-9112-43c3-8381-8fdce79c5659.jpg" width="400"></div>

### Conclusions
#### Success factors

Three main success factors have been identified in this analysis.
- **Category** explains most of the success probability, with only three of them having more than half of all projects accomplishing the goal.
- **Project goal** is the second best predictor of the odds of raising enough money. Unsurprisingly, the less ambitious projects are, the most likely they are to being fully funded.
- **Launch quarter** is the weakest projects success predictor of all, being the second and third quarters slightly (up to 8%) better for fundraising.

#### Other conclusions
The 10 most backed (by % pledged) projects come exclusively from the categories **GAMES** and **DESIGN**, so, these two may be good to look for outstanding startups.

Finally, there has been an steady improvement in the project success rates in the past 4 years and the trend is expected to continue. **Hypothesis**: better policies for publishing projects within Kickstarter, which would explain the steep decline in $0 pledged projects starting on 2014.

#### Suggested investment strategy
Strategy should have the objective of maximizing profitability, by diversifying investment into three tiers, taking into account success factors above mentioned. All projects should be selected from those having the category LIVE.
- **10% High risk**, high investment (*TECH* category). Suggested goal: **25K**.
- **30% Mid risk**, mid investment (*DESIGN, GAMES*). Suggested goal: **10K**.
- **60% Low risk**, low investment (*DANCE, THEATER, COMICS*). Suggested goal: **5K**.

Ideally, projects should be selected from those starting on **Q2** and **Q3**.

### Techniques applied

#### Visualization

- `Scatter plot`
- `100% stacked bar chart`
- `100% stacked area chart`
- `Pie chart`
- `Bar chart`
- `Boxplot`

#### Other
- `LOD calculations`
- `Outliers removal`

### Results

<div class="img-left"><img src="https://i.imgur.com/S3UuZWK.png" width="1000"></div>

[Link to Tableau viz](https://public.tableau.com/app/profile/gonzalo3304/viz/Kickstarter_16228395867440/Dashboard1)

[Link to PDF](https://drive.google.com/file/d/1day1huyMf7Z8D3zEOljj7dLH_E4g78Uk/view?usp=sharing)

### Data description

Dataset has been provided by [Maven Analytics](https://www.mavenanalytics.io/data-playground). It contains 1 file: `kickstarter_projects.csv`. The parameters included are:

### kickstarter_projects.csv
> - **`ID`**: Internal kickstarter ID. (categorical)
> - **`Name`**: Name of the project. (categorical)
> - **`Category`**: Project category. (categorical)
> - **`Subcategory`**: Project subcategory. (categorical)
> - **`Country`**: Country the project is from. (categorical)
> - **`Launched`**: Date the project was launched. (numerical)
> - **`Deadline`**: Deadline date for crowdfunding. (numerical)
> - **`Goal`**: Amount of money the creator needs to complete the project (USD). (numerical)
> - **`Pledged`**: Amount of money pledged by the crowd (USD). (numerical)
> - **`Backers`**: Number of backers. (numerical)
> - **`State`**: Current condition the project is in (as of 2018-01-02). (numerical)
