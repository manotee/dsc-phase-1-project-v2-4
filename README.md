# Phase 1 Final Project

This repository includes all files for the final submission for the Phase 1 project.

## Project Overview

For this project, we used movie data to determine what types of films have been performing best at the box office and then provide recommendations to the stakeholder.

* [Presentation Link](https://github.com/manotee/dsc-phase-1-project-v2-4/blob/master/Presentation.pdf) - Presentation slides for this notebook.

* [Repo Link](https://github.com/manotee/dsc-phase-1-project-v2-4) - Location of project repository.

## Business Understanding

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. We are charged with exploring what types of films are currently doing the best at the box office. 

In this project, we will attempt to answer the questions:

* What type of movies with the most absolute profit?
* What months are best to release movies?
* What do customer viewing trends look like in recent years?
* What is the best runtime for movies? 

## Data Understanding and Analysis

### Source of Data

* [The Numbers](https://www.the-numbers.com/) - Used to retrieve movie financials including budgets/revenues and release dates.

* [IMDB](https://www.imdb.com/) - Used to retrieve basic movie info to sort genres and runtimes.

![movie data erd](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project-v2-4/master/movie_data_erd.jpeg)

### Description of Data

For this analysis, the movie population will consist of:

* Movies released from 2010-2019.
* Movies with worldwide gross revenue over $20 million.
* Movies will be grouped into nine high-level genres for comparison purposes. 

Additional expenses such as Distribution/Marketing were not included in this analysis.

The nine high-level genre types include:

*Action/Adventure*     - Examples include Superhero movies, Star Wars, etc. <br>
*Action/Thriller*      - Movies like James Bond, Mission Impossible, etc.  <br>
*Biography/Historical* - Based on real people/events, could have elements of other genres. <br>
*Comedy*               - Standard comedic movies, with little genre crossover. <br>
*Crime/Mystery*        - Heist/Drug movies and Police/Detective/Lawyer themed movies. <br>
*Drama*                - High Drama movies with little genre crossover. <br>
*Dramedy*              - Movies that cover serious topics with humerous elements. <br>
*Family/Animation*     - Family friendly movies, typically aimed at younger audiences. <br>
*Horror*               - Movies like Saw, The Quiet Place, The Purge, etc. <br>

### Visualizations

* Genres with highest total profit from 2010-2019.

![total_profit](https://github.com/manotee/dsc-phase-1-project-v2-4/blob/master/images/Total_Profit.png)

* Best Average Profit by Release Month

![release_month](https://github.com/manotee/dsc-phase-1-project-v2-4/blob/master/images/Release_Month.png)

* Customer viewing trends by genre per year. 

![viewing_trends](https://github.com/manotee/dsc-phase-1-project-v2-4/blob/master/images/Viewing_Trends.png)

* Movie Profit by Runtime 

![runtime](https://github.com/manotee/dsc-phase-1-project-v2-4/blob/master/images/Runtime.png)
         
## Conclusions

Action movies had the hightest total revenue, but also higher risk of losses. Horror movies had the greatest profit percentage. The viewing trends showed clear increases for 'experience' movies such as Horror, Action, heavy special-effect - types of movies that are best seen in theater environment. Summer/Holiday releases have the best average profits. Minor relationship between profit/runtime, but best chances of profits is to remain with averages of the dataset.

### Recommendations

* Focus on experiences that cannot be duplicated at home. Headlined Action and Horror genres.
* Movie releases should be focused in Summer months (May, June, July) and Holiday months (November, December).
* Movie runtimes should be in line with established averages for best results: 90-130 minutes



