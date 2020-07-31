
# Module 2 Final Project


## Introduction:

In this project, I have analyzed a dataset from Kaggle about Steam Games to determine which factors are most pertinent to developing a game that is highly rated on Steam.

A multivariate linear regression model was created in order to investigate which features are most relevant to a high "rating". Pandas, matplotlib, and Seaborn was used to aid in creating visualizations and analyzation of the data.

Scipy, sklearn, and statsmodels were used for hypothesis testing, modeling, and analysis of models.

After the whole process, I was able to draw several meaningful conclusions from my data about what influences "rating" 


## Data Overview:

Dataset initially contained 27075 games, collected on May 28th, 2019.

Target Variable (modified proportion of positive feedback over total feedback) was created using formula from: https://steamdb.info/blog/steamdb-rating/

Some base features were used such as pricing, # of achievements, and average playtime
Some features engineered were dummy variables of the various steam genres, categories, and available operating systems.

## Process:

1. Data Cleaning
2. Preprocessing
2. Exploratory Data Analysis
3. Feature Engineering
4. Hypothesis Testing
5. Modeling


## Recommendations:

- Build games capable of running on multiple operating systems.
- It is more favorable to make paid games than free-to-play. In-app Purchases are disliked.
- Be an indie developer making casual single-player games, preferably with the Action, Adventure, Simulation, and/or Strategy genre tag(s)
- Games with as much compatability with Steam tend to do better than stand-alone games, so for example encourage steam workshop modding, achievement hunting, collectibles/trading cards.
- Release games when no other notable titles are coming out at the same time.


## Future Work:

- Work with data from other video game distribution services like the Epic Store, GOG.com, GamersGate.
- Take a look into console or mobile game markets.
- Focus entirely on Indie game developers as opposed to including big game companies.
- Scrape for more data on Steam Store that may not have been covered here.


  








