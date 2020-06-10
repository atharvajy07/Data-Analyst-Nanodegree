# Movies Data Exploration
## by Atharva J. Yeolekar


## Dataset

I have selected a dataset of my choice for this project.I have selected the movies on Netflix,Prime Video,Hulu and Disney+ from Kaggle.You can view the web page [here](https://www.kaggle.com/ruchi798/movies-on-netflix-prime-video-hulu-and-disney).This dataset originally consisted of 16744 rows which had to trimmed down to 16242 due to data inconsistencies and missing data.Several columns have also been dropped for our analysis.

## Summary of Findings

I had opted for this dataset as I was curious about the features of the data set which could be used to predict the IMDb and Rotten Tomatoes rating of a movie. However, due to large amount of missing data, I had to drop the rotten tomatoes column from the dataset. On performing several Univariate,Bivariate and Multivariate analyses,I observed that there is no feature in our dataset that has a significant impact on the IMDb rating of a movie.
One surprising yet obvious relationship that I observed was between Netflix and Prime Video. A strong negative correlation was observed between the two features which indicate that it is highly unlikely that a movie would be found on both the platforms.This obseravtion seems to be obvious as both these platforms are among the industry leaders.
After each step of the data analysis process I have taken feedback from my father who is a senior professional in a MNC and frequently does data analysis using several business analytics tools.

## Key Insights for Presentation
For the presentation ,I have mainly focused on the influence of several numeric and categorical variables on the IMDb rating of a movie.In the initial section, I have explored the distributions of the Year and IMDb columns of our dataset. 
In the following section, I have introduced Bivariate Relationships.The relationship between the IMDb rating with Year,Runtime and the OTT platforms has been explored using appropriate plots.I have also explored the relationships of the OTT platforms with each other using a correlation heatmap.
In the final section, I have touched upon multivariate relationships. I have distributed the movies as per their Country of production and their respective genres. After this segregation, I have analysed whether the runtime or the year of production have any impact on the IMDb rating of the movie on a granular level.All the relationships have been analyzed using appropriate plots and metrics.   

# Contents of this folder - 
 - __Exploration__ - The jupyter notebook in which data wrangling and data analysis has been performed.
 - __Slide_deck__ - Presentation of the various analyses performed for this project.
 - __Movies,Moviesonstreamingplatforms,genre,countries__ - Contain the data used for this project.