# Microsoft-Movie-Studio-Business-Proposition

**Authors**: Anthony Warren, Edel Prado, Hatice Kastan, Justin Sohn, Marcelo Scatena

## Overview

Microsfot is creating a movie studio and wants business recommendations for it.  Information was gathered by cleaning and analyzing databases from Imdb, Rotten Tomatoes and Tmdb. With that analysis it was possible to gather which movies, studios, actors, writers, producers and genres were perfoming better at the box office. The recommendations for Mycrosoft Movie Studio that we suggest are to: Buy the Intelectual Property of the book franchise *Throne of Glass* and make a series of movies; Make an R Rated Call of Duty or Halo movie franchise; Work with actors or directors that have experience either writing franchise movies (e.g. Anthony and Joseph Russo), or that their names carry such a weight that it turns into a franchise (e.g. Ryan Reynolds, Dwayne Johnson, Vin Diesel, Keanu Reeves).

## Business Problem

Creating a startegy to develop a new studio demands data. To start a studio Microsoft needs to first come up with a plan of action, regarding which kind of movies to make, who to hire and what properties to use. With that in mind we will look into what are the movies that are currently performing better at the box office, which studios, actors, writers, producers are behind them, from which studio are they and which genre and rating. We'll also look into reviews to collect popularity information. The results of these findings will provide information on which steps Microsoft should take to be the most successful in their new endeavor.

***


## Data

This project analysed data from Imdb, Rotten Tomatoes and Tmdb. They provide crucial information regarding successful movies and correlate them to studio, crew and ratings. 
The data traces back from the 1920s to 2018. We sampled most information from the last ten years, since Microsoft needs current and relevant information.

***
Questions to consider:
* Where did the data come from, and how do they relate to the data analysis questions?
* What do the data represent? Who is in the sample and what variables are included?
* What is the target variable?
* What are the properties of the variables you intend to use?
***

## Methods

The datasets had to be cleaned and filtered. Small values that were not related to top grossing movies were dropped. NaN values were handled in a case to case basis, and all numbers were turned into integers.
The data was modeled to arrive in the top grossing movies, in the top grossing actors, writer and directors, popularity by rating, gross by genre.
With the information given to us by these visualizations, we can accurately reccommend a proposition to Microsoft that will mimic the wanted results.
***

## Results

The results indicate a clear movement towards franchise movies that have in-movie universes. Avengers, Star Wars, Jurassic Park, Fast and Furious and Harry Potter are all amongst the highest grossing movies of all time, most having multiple instances in it, and are all franchise movies.

***
Questions to consider:
* How do you interpret the results?
* How confident are you that your results would generalize beyond the data you have?
***

Here is an example of how to embed images from your sub-folder:

### Visual 1
![graph1](./images/viz1.png)

## Conclusions

Provide your conclusions about the work you've done, including any limitations or next steps.

***
Questions to consider:
* What would you recommend the business do as a result of this work?
* What are some reasons why your analysis might not fully solve the business problem?
* What else could you do in the future to improve this project?
***

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact **name & email, name & email**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                           <- The top-level README for reviewers of this project
├── dsc-phase1-project-template.ipynb   <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf         <- PDF version of project presentation
├── data                                <- Both sourced externally and generated from code
└── images                              <- Both sourced externally and generated from code
```
