
# Data Analysis on Movies

**Authors**: Eduardo Gonzalez, Lucas Kimball


##  Overview

For this project, completed an Exploratory Data Analysis(EDA) on Movie data. Through a thorough examination of the dataset, our aim is to offer customized recommendations to fledgling Movie Studio.

### Business Problem

Welcome to the world of Consideratum Studios. We've ventured into the movie industry, driven not by financial gain but by our passion for creating exceptional films. Having achieved success in various other ventures, we embark on this cinematic journey with a singular goal – to produce top-tier, award-winning movies that will stand the test of time.

Our mission is simple: we aspire to become the most decorated studio in the industry. To achieve this, we seek to unravel the secrets behind crafting award-winning films. We're keen to understand what makes a movie truly award-worthy, explore the genres that hold the key to success, and identify the factors that set exceptional movies apart from the rest.


***
Questions to consider:
* What are the most common genres of Award-Winning Movies?
* Who should be hired in order to maximize our chances at winning awards?
* What is the length of award-winning movies?
***

## Data

- [Academy Award](https://www.kaggle.com/datasets/theacademy/academy-awards) winners spanning from 1927 to 2015.
- [Golden Globe Awards](https://www.kaggle.com/datasets/unanimad/golden-globe-awards) victors from 1944 to 2020.
- IMDb's extensive film database.
- The Numbers, offering insights into movie financials.

## Methods

This project delves into an extensive exploratory analysis of Movie data to observe trends among Award winning movies. We paired the Academy Awards, Golden Globes, and IMDb databases on the names of movies. This was an important step in our analysis because we wanted to be able to compare our sample of award-winning movies to a larger population of movies. Once completed we were able to deliver a series of recommendations and visuals to Consideratum Studios.

## Results

![img](https://github.com/0xEduardoG/Movie-Studio-Data-Analysis/blob/main/Images/Top_Genres_Award_Winning_Vs_Total_IMDb.png)

![img](https://github.com/0xEduardoG/Movie-Studio-Data-Analysis/blob/main/Images/Comparison_of_movie_runtimes.png)

![img](https://github.com/0xEduardoG/Movie-Studio-Data-Analysis/blob/main/Images/Screenshot_2023-09-14_104635.png)

![img](https://github.com/0xEduardoG/Movie-Studio-Data-Analysis/blob/main/Images/Screenshot_2023-09-14_105047.png)


## Conclusions

Drama is far and away the winningest genre of movie, and should be the genre that Consideratum focuses on deciding what type of movies to make. 

The average runtime of award-winning movies is approximately 120 minutes, while the average runtime of a selected sample of movies from the IMDb database (all movies greater than 0 mins and less than 175 mins long) is approximately 84 minutes. Therefore the focus should be on making films around 2 hours in length.

Meryl Streep, Dustin Hoffman, and Tom Hanks are most awarded actors/actresses that are still working. Clint Eastwood, Oliver Stone, and Steven Spielberg are highly awarded directors, who also have a prolific catalogue of drama movies, and are still working. All of these individuals should be at the top of the list for Consideratum Studios to recruit for their first film.

### Next Steps

- Investigate the results of the Academy Awards and Golden Globes since 2015 and 2020, respectively. Incorporate that data into our previous analysis

- Collect salary data for the recommended team to predict future film budgets

- Create a model to predict how likely it is for an individual movie to win an award

## For More Information

Please review our full analysis in [our Jupyter Notebook](./EDA-Movie-Studios.pdf) or our [presentation](./Movie_Project_Presentation.pdf).

For any additional questions, please contact us:

**Eduardo Gonzalez & eduardo0591@gmail.com, Lucas Kimball & lucaskimball98@gmail.com**



## Repository Structure

```
├── images

├── EDA-Movie-Studios.ipynb
├── README.md
├── .gitignore
├── Movie_Project_Presentation.pdf
└── EDA-Movie-Studios.pdf
```










