![graph1](./images/Tom-Cruise.jpeg)

# Tom Cruise Cannot Lose

**Authors**: Victor Kang

## Overview

In today's modern world, especially during and after the pandemic, the movie industry is mightily struggling to stay afloat and get back to normal. A single bad movie could spell the financial doom of an entire studio! That's why every decision a studio makes has taken on exponential weight and risk. That is why most movie studios are turning to data science to help guide their decision making! In this notebook, financial performance data from publicly-available online movie databases will be analyzed to identify only the most successful movies out of the most recent 5000 released movies to-date. Relationships, trends, and metrics will be explored to produce budget, genre, and cast and crew recommendations that will give a new movie studio their best chance at making their first financially successful debut movie!

***
## Business Problem

Microsoft has been suffering from a severe case of FOMO (Fear-Of-Missing-Out) as they've watched many of their competitors succeed in opening up their own movie studios and creating original video content! Microsoft wants in on the action and is now opening their own movie studio! I've been tasked with providing critical data-based market research to ensure that Microsoft's first movie will be a global success!

***
#### Primary Objectives and Qualifications:
1. Explore and analyze what **types** of films are **currently** doing the **best at the box office**.
* The key terms here in bold must first be defined. For this Project, they shall be defined as follows:
>* **Types**: There are many ways to classify or categorize films, most common being by Genre. We can also categorize movies by their budget range, ie. big budget vs small budget.
>* **Currently**: Because Microsoft asked for "currently", we know we should only consider modern movies in our upcoming analysis. Exactly how modern will be influenced by our available data. Specific Date Range To Be Determined! But we should at minimum aim to include movies released this year (2022)!
>* **Best at the Box Office**: "Best" will be defined solely by the financial performance of movies at the Worldwide Box Office. To measure financial performance, we will explore the Worldwide Box Office Gross of movies and compare it to their Production Budgets to calculate the *Profit/Loss* and *Return-On-Investment* metrics.  

* In short, our first objective is to determine which Genres and Budget Ranges of modern movies have produced the highest profit and return-on-investment for their movie studios! 

2. Provide **(3) actionable insights / concrete business recommendations** based on the analysis. 
* We plan to provide budget range recommendations and how budgets could have a relationship to financial success.
* Genre Recommendations
* Recommendations for cast and crew! Actor, Actress, Director, and Writer recommendations.
***

## Data

### Prelimary Data Exploration

Provided Data for Project:
* **Box Office Mojo**, compressed CSV file
* **Rotten Tomatoes**, 2 compressed TSV files
* **TheMovieDB**, compressed CSV file
* **The Numbers**, compressed CSV file
* **IMDB**, SQLlite database

In my search for up-to-date and current movie data, I was able to find (3) outside sources to supplement our datasets as follow:
> 1. **movie_gross_data.csv** : Maintained Box Office Mojo dataset; From Kaggle https://www.kaggle.com/
> 2. **movies budgets.csv** : Maintained comprehensive movie dataset including Budgets; From Kaggle https://www.kaggle.com/
> 3. Below files were the latest individual IMDB table downlaods. Data courtesy of IMDb. https://datasets.imdbws.com/
***only bolded files were used and included in the zippedData folder of the repository**
>* **name.basics.tsv.gz**
>* title.akas.tsv.gz
>* **title.basics.tsv.gz**
>* title.crew.tsv.gz
>* title.episode.tsv.gz
>* **title.principals.tsv.gz**
>* title.ratings.tsv.gz
***

## Methods

Describe the process for analyzing or modeling the data. For Phase 1, this will be descriptive analysis.

***
Questions to consider:
* How did you prepare, analyze or model the data?
* Why is this approach appropriate given the data and the business problem?
***

## Results

Present your key results. For Phase 1, this will be findings from your descriptive analysis.

***
Questions to consider:
* How do you interpret the results?
* How confident are you that your results would generalize beyond the data you have?
***

Here is an example of how to embed images from your sub-folder:

### Visual 1
![graph1](./images/viz1.png)

## Conclusions

In today's modern world, a movie's financial performance defines it's success. Studios are only interested in Profit and their Return-On-Investment. 

Based off the data analysis, I would recommend to Microsoft's new Movie Studio to secure a **production budget of ~$125M** to make the next **Action & Adventure** movie starring **Tom Cruise** and **Emma Watson**, with **Anthony Russo** directing a story written by **Christophr Markus**.

This combination is almost guaranteed to be the greatest movie of all time.
***

## For More Information

Please review the full analysis in [the Jupyter Notebook](./dsc-phase1-project-FINAL.ipynb) or the [presentation](./Tom Cruise Cannot Lose - Presentation.pdf).

For any additional questions, please contact **Victor Kang - mr.victorkang@gmail.com**

## Repository Structure

Describe the structure of your repository and its contents, for example:

```
├── README.md                                     <- The top-level README for reviewers of this project
├── dsc-phase1-project-FINAL.ipynb                <- Final narrative documentation of analysis in Jupyter notebook
├── dsc-phase1-project-template.ipynb             <- Dirty notebook showing previous work
├── Tom Cruise Cannot Lose - Presentation.pdf     <- PDF version of project presentation
├── zippedData                                    <- Both sourced externally and generated from code
└── images                                        <- Both sourced externally and generated from code
```
