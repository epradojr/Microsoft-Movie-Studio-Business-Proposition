# Microsoft-Movie-Studio-Business-Proposition

## Microsoft Make It Real - Turning Dreams into Reality

**Authors**: Anthony Warren, Edel Prado, Hatice Kastan, Justin Sohn, Marcelo Scatena

## Overview

Microsfot is creating a movie studio and wants business recommendations for it. Information was gathered by cleaning and analyzing databases from Imdb, Rotten Tomatoes and Tmdb. With that analysis it was possible to gather which movies, studios, actors, writers, producers and genres were perfoming better at the box office. The recommendations for Microsoft Movie Studio that we suggest are: 

* Buy the Intelectual Property of the book franchise *Throne of Glass* and make a series of movies
* Make R Rated movies of the popular Microsoft game franchises Call of Duty and Halo
* Work with actors or directors that have experience either writing franchise movies (e.g. Anthony and Joseph Russo), or that their names carry such a weight that it turns into a franchise (e.g. Ryan Reynolds, Dwayne Johnson, Vin Diesel, Keanu Reeves).
***

## Business Problem

Creating a startegy to develop a new studio demands data. To start a studio Microsoft needs to first come up with a plan of action, regarding which kind of movies to make, who to hire and what properties to use. With that in mind we will look into what are the movies that are currently performing better at the box office, which studios, actors, writers, producers are behind them, from which studios are they and which are their genre and rating. We'll also look into reviews to collect popularity information. The results of these findings will provide information on which steps Microsoft should take to be the most successful in their new endeavor.
***

## Data

This project analysed data from Imdb, Rotten Tomatoes and Tmdb. They provide crucial information regarding successful movies and correlate them to studio, crew and ratings. 
The data traces back from the 1920s to 2018. We sampled most information from the last ten years, since Microsoft needs current and relevant information.
***

## Methods

The datasets had to be cleaned and filtered. 
* Small values that were not related to top grossing movies were dropped
* NaN values were handled in a case to case basis
* All numbers were turned into integers

The data was modeled to arrive in the following visualisations:
* Top grossing movies
* Top grossing actors, writer and directors
* Popularity by rating, gross by genre
* Budget related to total gross
These visualisations will give us enoguh information to make accurate predictions of what Microsoft Movie Studio should aim to.
***

## Results

* The results indicate a clear movement towards franchise movies that have in-movie universe. Avengers, Star Wars, Jurassic Park, Fast and Furious and Harry Potter are all amongst the highest grossing movies of all time, most having multiple instances in it, and are all franchise movies
* The budget of big box office movies show positive correlation with total gross
* Rated R movies are amongst the better reviewed ones, but lack representation in the highest grossing ones
* Action, Adventure and Thriller are the public most well reviewd genres
***

Here is an example of how to embed images from your sub-folder:

### Visual 1
![graph1](./images/viz1.png)

## Conclusions

Given all the information we gathered and visualized, we came up with a few reccommendations:
***
* Buy the Intelectual Property of the book franchise *Throne of Glass* and make a movie series
The data suggest that big movie franchises are taking over the box office. The conclusion is to get into that area by acquiring the IP of a famous and well rated book series that would adapt well to the movie media.
*Throne of Glass* is a series with eight books from 2012 to 2018, best seller at the New York Times
***
* Make R Rated movies of the popular Microsoft game franchises Call of Duty and Halo
R rated movies are amongst the most popular movies by audience score. That shows a clear preference to it for a mature audience. They are underrepresented in the box office though. That is explained by a fewer number of people actually being able to buy and see those movies in the cinemas (over 18 year olds).
The video game franchises chosen are amongst the most popular ones ever made, and they're made for X-Box, which is Microsoft property, what would generate an even larger opportunity for marketization.
***
* Suggestion 3 open for discussion 
Work with actors or directors that have experience either writing franchise movies (e.g. Anthony and Joseph Russo), or that their names carry such a weight that it turns into a franchise (e.g. Ryan Reynolds, Dwayne Johnson, Vin Diesel, Keanu Reeves).

We reccommend as well, regardless of the which proposition is followed, to make a high budget movie, since the data shows a good correlation between that and total movie gross.
***

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact 
**Anthony Warren: anthonywarren6@gmail.com**
**Edel Prado: edel.prado.jr@gmail.com**
**Hatice Kastan: kastanhatice@gmail.com**
**Justin Sohn: jusohn2015@gmail.com**
**Marcelo Scatena: marcelo.oddo@gmail.com**

## Repository Structure


```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
