# Challenge

This challenge is designed to test your analytical skills.  

The challenge consist in deliverying a report about the food delivery scene in London. You will be evalued both: (1) the quality of the final report; (2) the quality of the code that generates such report. In the report you are require to complete very specific analysis in addition to a portion where you will showcase your creativity by asnwering a question you find interesting.  

# Software

You are required to use [R](https://www.r-project.org/about.html) to develop the report. R is the go to software when working on a number of tasks, such as data-manipulation, data-visualization, text-mining, statistical analysis, web-scraping, reporting, etc.

Follow these steps to set up R:

- Install [R](https://www.r-project.org)
- Install the [Rstudio IDE](https://www.rstudio.com). Rstudio has many features (e.g., tools for plotting or debugging) that makes working with R much easier. 

You can find learn more about R from the following introductory resources:  

- [R for data science](https://r4ds.had.co.nz)
- [Happy Git and GitHub for the useR](https://happygitwithr.com/index.html)
- [What They Forgot to Teach You About R](https://rstats.wtf)

# Data

Your analysis should exclusively use the following datasets:

- Restaurants information [download](data/resturants-mibe.rds)
- Restaurants delivery time [download](data/delivery-mibe.rds)

# Analysis

When developing the report, follow closely the structure presented in this section.

## Restaurants Information

In this section you will analyze the `Restaurant infromation` dataset with the objective of answering the following questions:  

- Present a column chart with the top 10 neghtborhoods by number of restaurant.
- Present a column chart with the top 10 neightborhoods by restaurant review score.
- Compute the top 10 biggest chains. Present the results in tabular format.
- Compute the average menu price and the number of menu items for each restaurant.
- Present in a barchar the number of items in the menu for the five most expensive and cheapest restaurants.

## Restaurants Delivery Times

In this section you will analyze the restaurants delivery times. To perform the following analysis you will need to join the `Restaurants information` and `Restaurants delivery time` datasets. Answer the following questions:  

- Count the number of neightborhoods where each restaurant delivers.
- Present in a barchart the top 15 neightborhoods by number of restaurants that deliver to.
- Compute the average delivery time for each restaurant.
- Present in tabular format the top 20 resturants by fasted average delivery time. In the same table also present the rating score, and postcode.

## Open Analysis

In this section you are invited to showcase your creativity as an analyst by developing an interesting analysis. You should open this section by stating a clear "business question," followed by a series of analysis (e.g., charts, tables) that investigate this question. You are also required to narrate your findings.


## Deliverables

- Report in PDF
- Rmarkdown code